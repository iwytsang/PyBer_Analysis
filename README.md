# PyBer Analysis

## Overview

### Purpose
PyBer is a ridesharing app company and the CEO of the company has given us a new assignment. Since we are a data analyst at Pyber, the purpose of our assignment is to use Python to create a summary DataFrame of ride-sharing data by city type and Matploblib to create a multiple-line graph showing the total weekly fares for each city type. Our analysis can allow PyBer to make business decisions based on the differences between the data by each city type (urban, suburban, and rural).

## Results

### Summary DataFrame
![image](https://user-images.githubusercontent.com/108503112/192298177-33c66564-767b-4be8-896f-872bfd5af6ad.png)

From the summary data frame above, we can see that the data is broken down into the three rows of urban, suburban and rural city types. The most rides and drivers are from the urban city type, with 1,625 rides and 2,405 drivers, while the least is the rural city type, with 125 total rides and 78 total drivers. There is a positive correlation with the total fares and number of total rides, as the more rides there are, the total dollar amount of fares increases. However, there is a negative correlation between the number of total drivers and the average fare per ride and average fare per driver. We can see that the nunber of total drivers is the lowest out of the three city types at 78 drivers, and therefore the average fare per ride and average fare per driver is the highest, at $34.62 per ride and $55.49 per driver. Meanwhile, with the urban city type, the opposite is true with the total drivers being the highest out of all three city types at 2,405 but the average fare per ride and per driver is the lowest at $24.53 per ride and $16.57 per driver.

### Multiple-line Chart
![image](https://user-images.githubusercontent.com/108503112/192298723-32b62b54-16f5-40c6-b903-e169d0a029d5.png)

From the Total fare by City type per week chart, we can see that the timeframe of the results are from January 1, 2019 to April 28, 2019 along the x-axis, and along the y-axis are the total fares in $USD. With this multiple-line chart, we can see the points in time where there were peaks and dips in fares for each type of city based on the different line colors, with yellow being urban, red being suburban, and blue being rural. Overall, we can see that urban fares are the highest across all points in time, while suburban is the 2nd highest, and rural being the lowest in total fares. With both urban and suburban, we can see the highest fare amount being sometime in the last weeks of February while for rural, the highest fare amount peak was at the start of April. For urban and suburban, we can see that the lowest fare amounts are both at the start of January, while for rural, the lowest point in time was at the first few weeks of January.

## Summary

### Three business recommendations
1. Based on the fact that the rural total fares and total rides are the lowest of all city types, we can determine that there may not be enough incentive for people to ride with PyBer in rural cities. One business recommendation could be increasing the incentive for people to take more rides, for example, getting a discount coupon on subsequent rides after their initial ride, as well as a referral program and contest for referrals to ride with PyBer.

2. The Urban city type the only one where the total amount of drivers is greater than the total amount of rides. That could potentially mean that there are too many drivers for the demand of rides in urban cities. A business recommendation would be to cut out some drivers (ie. drivers with lowest driver ratings, etc.) to reduce overhead costs for the company and to increase the quality of drivers and rides for PyBer.

3. Based on the multi-line chart for total fare by city type, we can determine that the rural total fares over January to April 2019 is the lowest and the point in time for the lowest dip and highest peak does not match with the urban or suburban time frame. A business recommendation would be to do further analysis to determine whether or not it is profitable to keep PyBer rides in rural city types, as the demand seems to be low. If it is not profitable to continue PyBer operations in the rural city types, more focus can be placed onto increasing total fares for urban and suburban city types. If it is profitable to still continue with rural PyBer operations, a recommendation would be to target the weeks with the dips and lowest amount of fares to increase promotions, deals, and offers to incentivize rural people to ride with PyBer.
