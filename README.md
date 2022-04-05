# PyBer_Analysis

## Overview of Analysis:
Client requested an analysis of ride-sharing data by examining subjects such as driver count, ride count, and fare amount. Client's primary concern is a comparison of the city types urban, suburban, and rural to determine the differences between these markets. 

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.10 (64-bit), Jupyter Notebook 6.4.8

## Results

The provided data was grouped by city type the sum of rides, drivers, and fares was calculated. These variables were then used to calculate fare per ride and fare per driver. Below is a description of each variable as well as the graph representing the data.
- Total Rides

  Urban has the largest number of rides which was followed by suburban. This makes sense due to the denser population and the desire to not drive in more dense traffic.

- Total Drivers

  Urban has the largest number of drivers which was followed by suburban. Like number of rides, this makes sense due to denser population. It should be noted that for urban cities, there were more drivers then rides. This indicates that you had some drivers registered with the service that did not provide a ride in the time that the data covers. It would be advantageous to adjust the database to report number of active drivers in the given timeframe. This will provide more accurate data in the future. If this data is accurate and you have roughly 800 active drivers with no ride requests then that is a separate issue that would also need addressed.
  
- Total Fares

  Urban has the largest fare amount for the data provided which was followed by suburban. 

- Average Fare per Ride

  Rural has the highest fare per ride which is followed by suburban. This is most likely due the increased distance that the ride travels in less populated areas.

- Average Fare per Driver

  Rural has the highest fare per driver which is followed by suburban. However, due to the issue raised in total number of drivers, it is unclear if this data is reliable.  


<p align="center">
  <img src="https://github.com/justinkirk8/PyBer_Analysis/blob/main/Analysis/pyber_summary.png" width="700" />
</p>

- Total fare price per week over four months.

  The data was then broken down further to examine the total fare amount per week over a four-month period. In the graph below, we can see that the fare amounts are consistently distinct between the three categories. Urban consistently earns the most overall while suburban is consistently earning more fares then rural. It should be noted that both urban and suburban has more variance in fare per week then rural. 

<p align="center">
  <img src="https://github.com/justinkirk8/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png" width="1000" />
</p>
  
## Summary
From the data provided, I will make the following recommendations:
- it is clear that the urban market is your most profitable market. Due to this, it would be adventitious to focus your marketing towards this market.
- Despite the above recommendation, it is would still be advantageous to continue operating in suburban and rural areas since they are still assumably making a profit. 
- Update your database to report both total drivers and total active drivers in order to obtain more reliable data for a given time period.

