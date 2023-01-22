# PyBer Analysis

## Overview
### Purpose
After analyzing part of the Pyber data, our team was tasked with creating a summary DataFrame of the ride-sharing data by city type. After the data frame was created, we were asked to create a multiple-line graph using Pandas and Matplotlib that shows the total weekly fares for each city type.

### Resources
+ Data Sources: city_data.csv and ride_data.csv
+ Software: Python 3.6.1, Anaconda Navigator 2.3.2, and Jupyter Notebook 6.5.2

## Results
### Summary DataFrame
The Summary DataFrame was created by calculating total rides, total drivers, and total fares. With that information, we were able to calculate the average fare per ride for each city type and the average fare per driver for each city type:

![image](https://user-images.githubusercontent.com/113741694/213937258-b7c2290d-d4b2-40dd-8834-661e31799153.png)

+ Rural areas have less rides and less drivers, making the average fare per ride and average fare per driver much higher than suburban and urban cities.
+ The average fare per rides in urban areas in smaller than suburban and rural areas, likely as a result of shorter commutes in urban areas.
+ Urban cities have more drivers than rides, making the average fare per ride andd average fare per driver much lower than suburban and rural cities.

### Multiple-Line Graph
The Summary DataFrame was used to create a pivot table, which was filtered to show the total weekly fares for each type of city:

![image](https://user-images.githubusercontent.com/113741694/213936118-1c43db54-856f-459c-818b-f96141d3b6ed.png)

+ All three city types show an increase in fares in the latter weeks of February and a dramatic decrease at the start of March.
+ Urban fare totals fluctuate significantly starting at the end of February and going through March.
+ Suburban fares peak in February, decline in March, and stay low through April.

## Summary and Recommendations
+ Incentivize urban drivers to seek more riders in suburban and rural areas with a bonus or perk.
+ Research why the uptick in fares occurs in February in all city types and see if there are any marketing opportunities for this timeframe.
+ Survey drivers to see how many hours each driver works, how often they work, and the duration of a typical shift. This information could be used to update the average fare per ride and the average fare per driver.
