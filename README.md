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

From the Total fare by City type per week chart, the results are from January 1, 2019 to April 28, 2019. We can see the points in time where there have been less total fares.

## Summary

### Three business recommendations
1. Based on the fact that the rural total fares and total rides are the lowest of all city types, there may not be enough incentive for people to ride taxis in rural cities. One business recommendation could be increasing the incentive for people to take the taxis, for example, getting a discount coupon on subsequent rides after their first ride, as well as a referral program and contest for referrals to Pyber.
2. Urban cities is the only area where total amount of drivers is greater than the amount of rides. That could mean there are too many drivers for the demand. A business recommendation would be to cut some drivers and therefore lowering overhead costs for the company.
3. Based on the chart for total fare by city type per week, a business recommendation would be to target the weeks with the dips and lowest amount of fares and increase promotions, deals, and offers to incentivize people to ride.
