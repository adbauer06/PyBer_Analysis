# PyBer_Analysis

## Project Overview
The purpose of this project was to analyze and compare ride-sharing data for different city types for a time period.  The specific city types we compared were rural, suburban, and urban.  

The first part of this analysis involved creating a dataframe that included the following metrics for each individual city type:
1.  Total rides
1.  Total drivers
1.  Total fares 
1.  Average fare per ride
1.  Average fare per driver

The analysis was then taken a step further by creating a graph to show total fares by individual city type for a specified period of time.


##  Resources
The following resources were used to complete this analysis:
- Data Sources:  
    - city_data.csv, containing information for cities with drivers
    - ride_data.csv, containing individual ride data for a time period
- Software:  Jupyter Notebook, Visual Studio Code, 1.58.2


## Analysis Results

### Summary by City Type

This deliverable gives a good view of the differences between the various city types with respect to utilization of these types of services, the availability of drivers, and the revenue generated.  We also can see the average fare per ride in order to gage afforability, as well as average fare per driver in order to gage income potential. 

![summary_by_city_type](https://github.com/adbauer06/PyBer_Analysis/blob/main/analysis/summary_by_city_type.PNG)

Some key obervations would be:
- Urban areas have a much higher utilization of these types of services, much more than rural and even suburban cities, resulting in higher total fares/revenue.
- There are a much higher number of urban drivers then the other two areas.  
- The number of urban drivers is higher than the number of total rides for this time period, as opposed to the other two areas which both have more rides reported than drivers.  This metric is reflected in the average fare per driver, showing that rural and suburban drivers will tend to have more income potential than urban drivers.
- Average ride fare is highest in rural cities, lowest in urban cities, and in the middle for suburban cities.


### Total Fares by City Type

This deliverable gives a graphical representation of the total weekly fares for each individual city type over a period of time, in this case January 1, 2019 through April 29, 2019.  In addition to seeing how the different city types compare as far as total fares at points in time, we can look at where each city's total fares trend higher or lower over time and how those increases and decreases match up with other city types. 

![Fare_by_City_Type](https://github.com/adbauer06/PyBer_Analysis/blob/main/analysis/Fare_By_City_Type.png)

Like the previous deliverable this graph clearly shows how total fares are highest in urban areas, lower in suburban areas, and lowest in rural areas.  Other obvervations to note would be:
- While there are many fluctuations during this period, for the most part, total fares do not appear to be significantly rising or falling.
- In January, the trends for urban cities and rural cities are opposite, meaning when urban total fares trend up, rural fares are trending down.  They look more similar staring in February. 
- At the end of the time period for this report, there appears to be a sharp increase in the suburban data, while the urban and rural are falling slightly.  It might be worthwhile to extend out the timeframe to ensure this is not a continuing trend that needs to be addessed.


 ## Summary
 Based on the two deliverables above, I would have the following recommendations:
 1.  I would suggest looking into ways to promote these types of services more in both rural and suburban areas.
 2.  I would suggest looking for ways to even out the average fare per driver metrics, making sure the number of drivers more accurately support the amount of services needed.
 3.  I would suggest looking for ways to bring the average fare per ride down in rural and surburban areas to be more in line with the average fare per ride in urban cities and make the use of these services more attractive to people in rural and suburban cities.
 
 
