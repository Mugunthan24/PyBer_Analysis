# PyBer_Analysis
Performing an exploratory analysis for a ride share company.

## Overview of the Analysis
As a Data Analyst at a Python based ride-sharing app company called Pyber, I have been given the assignment of performing an exploratory analysis using large CSV files. To aid this process, several types of visualizations have been created to communicate a compelling story about the data. To create these visualizations the following below was used:
- Python scripts
- Pandas libraries
- Jupyter Notebook
- Matplotlib

The visualizations created help explain the relationship between the type of city and number of drivers and riders, as well as the percentage of total fares, drivers, and riders by type of city. The end goal is to help Pyber improve accessability for users and determine affordability for underserved neighbourhoods.

## Results
The subsequent paragraphs will elaborate upon what information can be gathered from the 6 visualizations.

![image_name](https://github.com/Mugunthan24/PyBer_Analysis/blob/main/analysis/Fig1.png)

The scatterplot above plots the relationship between Total Number of Rides (Per City) vs. Average Fare ($). The size of each dot correlates with the driver count per city. Based on the graph, it is clear that on average, those living in rural areas pay higher fare prices than those living in suburban and urban type cities. This may be because the less rides in a city, the higher the average fare price is. 

Another key piece of information to note is that the dots in the rural cities are usually a lot smaller than those in the Suburban and Urban cities. The reason for higher fare price can also be because rural cities have fewer drivers available, while urban cities appear to be abundant with drivers. Suburban cities have about 6.3x as many drivers compared to rural cities, while urban cities have 30.8x more.

![image_name](https://github.com/Mugunthan24/PyBer_Analysis/blob/main/analysis/Fig2.png)

The median or 50th percentile number of drivers in urban communities is 24, around 17 in suburban, and lastly 6 in rural. There appears to be an outlier in the number of rides in urban communities where the number of rides is 39. For urban cities, the mean and median are roughly the same, and almost always, urban cities have more drivers than rural cities. 

![image_name](https://github.com/Mugunthan24/PyBer_Analysis/blob/main/analysis/Fig3.png)

The pie graph above shows the percentage of total fares by city type. Urban city types contribute to 62.7% of the fare, suburban cities contribute to 30.5% of the fare, while rural cities contribute the remaining 6.8%. Something important to note is that even though the rural communities on average pay higher fare prices (Rural: $34.62, Suburban: $30.97, Urban: $24.53), they contribute the lowest to the percentage of total fare because they have significantly less rides. Suburban cities relative to rural cities have 5x as many rides, while in urban cities it is 13x. 

![image_name](https://github.com/Mugunthan24/PyBer_Analysis/blob/main/analysis/Fig4.png)

The pie graph above shows the percentage of Total Rides by City Type. Urban has the highest percent with 68.4%, suburban cities contribute to 26.3% of total rides, while rural cities contribute 5.3%. The percentage of total rides per city type is likely influenced by population size, where cities with higher populations like urban cities will likely have more rides whereas rural cities with lower populations will have less rides.

![image_name](https://github.com/Mugunthan24/PyBer_Analysis/blob/main/analysis/Fig5.png)

Urban cities have the most drivers with 80.9%. Suburban and rural cities have significantly less with the percentage of drivers being 16.5% in suburban and 2.6% in rural. Just like with the percentage of total rides, the number of drivers in each city is likely correlated to its population. Rural communities have a lower population than suburban and urban communities so it will have a lower amount of drivers. Urban cities are heavily populated so those cities will be abundant with drivers.

![image_name](https://github.com/Mugunthan24/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)
The graph above shows the total fare by city type over a 4 month period (January 1, 2019 to April 28, 2019). On any given day, the total fares paid by Urban cities is higher than Suburban and Rural cities, and the total fares paid by Suburban cities is higher than Rural cities on any given day.

## Summary
After reviewing the information provided by the visualizations, it is clear that rural communities are both underserved, and users usually experience higher fare costs relative to suburban and urban communities. Some potentials solutions that can be used to combat these disparities are:
1. Instead of making rides cheaper if there are more total rides in a city, rides can be cheaper if a greater percentage of the population in a city is using Pyber. For example,if the population of a urban city is 1000, and there are 400 rides in one day compared to a rural city with a population of 500 with 250 rides a day, the fare in rural cities will be cheaper because there is a greater percentage of rides relative to the cities population.
2. Rural cities do not have as many drivers. Perhaps there can be a pay increase for drivers who serve these communities. This will incentivize drivers from other cities to serve rural cities and reduce the fare for rides.
3. Rural communities are paying more in fare than their urban and suburban counterparts despite its citizens on average having lower incomes. Perhaps, those who reside in these communities can be given a discount to reduce how much they are paying to make their average fare more identical to that of urban and suburban cities.