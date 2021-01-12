# Module-5-Challenge-PyBer_Analysis

# PyBer_Analysis
Berkeley Bootcamp - Module 5

## Project Overview
Use data visualization techniques to give insight into the data from a ride sharing company called PyBer.

## Resources
- Data Source: city_data.csv, ride_data.csv

## Challenge Overview
You’ve been asked by your CEO to create an overall snapshot of the ride-sharing data. In addition to your scatter and pie charts, she would like to see a summary table of key metrics of the ride-sharing data by city type, and a multiple-line graph that shows the average fare for each week by each city type.

## Results 

Between January 2019 and May 2019, there were 1,625 rides in urban cities, 625 rides in suburban cities, and 125 rides in rural cities. The figure below highlights how rides in Urban cities contributed the most to PyBer's overall rides during this five-month period.

![% of Total Rides by City Type](Analysis/Fig6.png)

On a similar pattern, there was also a larger volume of drivers in urban cities compared to suburban and rural cities. There were 2,405 drivers in urban cities, 490 drivers in suburban cities, and 78 drivers in rural cities. Again, the figure below depicts the significance of drivers in urban cities during this time period.

![% of Total Drivers by City Type](Analysis/Fig7.png)

Given that there is a greater usage of PyBer in urban cities, the total fares are consequently also higher than suburban and rural cities. PyBer transactions in urban cities totaled nearly $40,000 whereas transactions in urban cities and rural cities totaled at least $19,000 and $4,000, respectively. The figure below demonstrates where the majority of PyBer's revenue occurred during this time period: urban cities.

![% of Total Fares by City Type](Analysis/Fig5.png)

In terms of costs, it appears that riders in rural cities pay on average almost $10 more for PyBer than riders in urban cities. The average fare per ride is about $35 in rural cities whereas the average fare per ride is about $25 in urban cities. Suburban cities' average fare per ride falls just in between - at about $31. While it may not be good news for riders in rural cities, it is a better market for drivers in this type of city. The average fare per driver is about $55 in rural cities, whereas the average fare per driver is about $17 in urban cities. Suburban cities' average fare per driver is about $40.

![PyBer Summary](Analysis/PyBerSummaryDF.png)

The multiple-line chart "Total Fare by City Type" further supports the PyBer Summary DataFrame by providing trends of total fares in rural, suburban, and urban cities between January 2019 and April 2019. The yellow trend shows how fares in urban cities totaled from around $1,600 to $2,300 from beginning to end during this five-month period. In contrast, the blue trend shows how fares in rural cities totaled around $300 from beginning to end during the same time period. The orange trend shows how the total fares in suruban cities fall in between urban and rural cities: around $700 to $1,300 from beginning to end during this time. The chart further demonstrates similar peak times in all these types of cities. One noteworthy peak in total fares among urban, suburban, and rural cities occurred sometime at the end of February 2019.

![Total Fare by City Type](Analysis/Fig8.png)

### Implications:
* There is a larger use of PyBer ridesharing in urban cities.
* There are more drivers in urban cities than rural cities.
* As a result, the majority of PyBer's revenue occurs in urban cities.
* On the other hand, the costs for using PyBer is greater among riders in rural cities than urban cities. This could discourage potential riders from using PyBer given the high average fare per ride. 
* Drivers in rural cities are earning more than drivers in urban cities. This could discourage discourage potential drivers from working with PyBer given the low average fare per driver.
* There is an another opportunity for further analysis to determine other factors that are contributing to the high ride costs in rural cities and low driver fares in urban cities. Perhaps, travel distance is a key factor.
* Overall, PyBer ridersharing services significantly differs in rural, suruban, and urban cities given the number of rides, drivers, and fares. Data supports that there is higher usage of PyBer ridesharing services in urban cities.


## Challenge Summary
1. Write a summary in your README.md file for the data in the summary DataFrame.

- The dataframe summary for ridesharing tells us a number of things. There are significantly more rides in Urban cities than Suburban or Rural. The number of drivers also follows that same pattern with more drivers being in Urban cities. The average fare per ride and average fare per driver are actally most expensive in the rural areas and cheaper in the Urban cities.  This tells us that as a ride share service has more drivers available the ride expenses or fares become cheaper on average. However, it is interesting to note that a missing piece of crucial data is the length of the ride. Its possible that since rural areas might require longer rides, that the data is skewed by the duration of the ride causing an increase in fares.

2. Write a summary in your README.md file on what the multiple line graph tells you about the fares for each city type over time.

- The multiline graph gives a nice visualiation of the ride share data. It clearly shows that all city types (Urban, Suburban, and Rural) are fairly consistent in total fares over time. There are a few spikes in the data here and there but overall quite consistent. It also shows that the majority of the money comes from Urban cities followed by Suburban and Rural last... It is clear from both of the summary dataframe and graph that even though the average fair of a Rural ride is higher, more money is made from Urban rides in total.
