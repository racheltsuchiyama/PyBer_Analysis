# PyBer_Analysis
## Project Overview

The purpose of this project was to analyse data to help improve the accessibility and affordability of the ride-sharing app PyBer. I compared the fares, number of drivers, and number of riders in the urban, suburban, and rural cities. With this data, I was able to assess the disparities between the city types and determine ways to minimize these disparities.


## Resources
### Data
city_data.csv

ride_data.csv

### Software
Python 3.6.1

Jupyter Notebook 6.3.0

## Results

I compared the ride-sharing data between urban, suburban, and rural city types and summarized the results in the table below.

### Total Rides

![Fig6](https://user-images.githubusercontent.com/83552696/120411904-7847e900-c30a-11eb-8453-ea756da0bd8d.png)

Urban cities had the highest number of total rides while rural cities had the lowest number of total rides. Suburban cities had 500 more rides than rural cities, but still much less than urban cities. However, urban cities had a slight advantage because the majority of the city types were urban and only a small number of the cities were rural.


### Total Drivers

The number of drivers was much higher in urban cities when compared to suburban and rural cities, as displayed in the pie chart below:

![Fig7](https://user-images.githubusercontent.com/83552696/120411921-7ed66080-c30a-11eb-9ae8-40fe226762ce.png)

However, due to the higher number of urban cities it may be more helpful to examine the box and whisker plots for the city types:

![Fig4](https://user-images.githubusercontent.com/83552696/120423926-43df2780-c320-11eb-8970-7d89080fb6be.png)

The number of drivers for urban cities varied drastically, while the number of drivers for suburban and rural cities covered a much smaller range. Some urban cities had the same number of drivers as suburban and rural cities, but the majority had of urban cities had a higher number of drivers.


### Total Fares

As shown in the table below, the urban cities had the highest total fares. However, the urban cities had the highest driver and rides count, so this conclusion was expected. It was more illuminating to insepct the box and whisker plot:

![Fig3](https://user-images.githubusercontent.com/83552696/120424490-5148e180-c321-11eb-9f81-edbecd9aa703.png)

The plot showed that, on average, rural cities had higher fares than suburban and urban cities. Suburban cities had slightly higher fares than urban cities, but otherwise their plots were very similar. The fares of rural cities covered a wider range and had the highest values.

### Average Fare per Ride and per Driver

The total rides, total drivers, and total fares for each city type were used to determine the average fare per ride and average fare per driver:

<img width="580" alt="Screen Shot 2021-06-01 at 5 48 48 PM" src="https://user-images.githubusercontent.com/83552696/120407292-b42a8080-c301-11eb-8629-17fad52216be.png">

Rural cities had the highest average fare per rider and per driver. Although urban cities had the highest number of total rides, total drivers, and total fares, they had the lowest fares per ride and driver. The average fare per driver of rural cities was much higher than the average of urban cities.

### Total Fare by City Type

The total fares per week were graphed:

![PyBer_fare_summary](https://user-images.githubusercontent.com/83552696/120425000-4f335280-c322-11eb-8592-4472542dccfb.png)

All city types had an overall small increase in fares from January to February with a small peak in the last week of February. The decline in fares in March may be due to warmer weather. The fares of the city types roughly followed the same pattern.

## Summary

There were many more drivers and rides in urban cities compared to suburban and rural cities. The limited availability of the drivers in rural and suburban cities may have discouraged patrons from ordering rides. Therefore, a redistribution of drivers from urban cities to suburban and rural cities may increase the number of rides in those city types.
Also, the fares of rides in rural cities was higher than suburban and rural cities. Lowering the fares of rides in rural cities may encourage more rides. This, along with the increase in drivers, would make the average fare per ride and average fare per driver more equal amoung the city types. There was a small decrease of rides in suburban and rural cities in mid-February. I theorized that more people are likely to take rides in the winter months due to the colder weather, which was demonstrated by the urban cities. During this time, PyBer should capitilize on the cold and offer small discounts to encourage more rides in suburban and rural cities.
