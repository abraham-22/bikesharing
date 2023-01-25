# Citi Bike in DM

## Overview of the statistical analysis:

During her visit to NYC, Kate noticed the benefit of the CitiBike program. After her visit to NYC, Kate got motivated to develop a bikesharing business in Des Moines, Iowa that mimics NYC Citibike. The purpose of this statistical analysis is to help Kate develop a proposal to create a bike-sharing program in Des Moines. In order to impress potential investors, we need to collect information on how the bikesharing business works in DM. Before that, Kate decided to study how the bikesharing business works in DM. In order to accomplish that, we analyzed NYC Citibike the bikesharing business data for the month of August to come up with a baseline information.

## Resources
* Data Source: [Citi Bike Data](https://citibikenyc.com/system-data), [201908-citibike-tripdata.csv.zip](https://s3.amazonaws.com/tripdata/index.html)
* Software: Python 3.11.1., Anaconda Navigator 2022.10, Jupyter Notebook 6.5.2, Tableau Public 2022.1
* This Tableau story can be seen: [Tableau Link](https://public.tableau.com/app/profile/aavram.abate/viz/CitiBike_data/Users)

## Results:
The total number of trips in August was 2,344,224. When we see the proportion of short-term customers of the bike service to the annual subscribers, there are 157,671 who short-term riders and 1,900,359 annual subscribers. The majority (81%) of the customer of NYC Citibike are annual subscriber this indicates the business will have strong income foundation by attracting long term customers. When we see Gender breakdown, 65.2% of the customers are male and 25% of them are females.  Chart shown below.

![image](https://user-images.githubusercontent.com/114262970/214548126-59b77b32-9b76-4f8a-950e-54467a954cc9.png)![image](https://user-images.githubusercontent.com/114262970/214548743-6944e0cb-6e94-4351-9668-ce95aaccbf01.png)

The relationship between birth year and trip length can be seen in graph below, Average trip duration by birth year. As indicated below, the general trend is younger riders tend to use the bikes for longer periods of time compared to other age groups.

![image](https://user-images.githubusercontent.com/114262970/214557726-68d20094-914e-4fb5-b49f-1e2e4ab08117.png)

In order to estimate how many bikes needed in Des Moines and to have a preventive mainetance program schedule, we analyzed the data to figure out the peak hours for bike tripes. As it can be seen below on the chart, the peak usage hours is in between 5:00 pm ato 7:00 pm. This is the period where we need the most bikes. AN on the other hand the least active riding times is in between 2:00 am to 5:00 am, this is the time fewer bikes are needed which makes it an ideal time for bike maintenance. 

![image](https://user-images.githubusercontent.com/114262970/214537086-e0d4633e-51c8-4f7e-8a82-0b1bc5e4a470.png)

CitiBike customers are using bikes in highest-traffic locations. NY Citi Bike cutomers prefered starting and ending location for a bike rental journey closer to the commercial  and high tourist area of Manhattan. The demand for bike ride in high trafic location is very high. Maps shown below. 

![image](https://user-images.githubusercontent.com/114262970/214549360-e6ffe6de-9704-4393-9231-fd3f47886ffa.png)
![image](https://user-images.githubusercontent.com/114262970/214550116-dadfd689-4952-4eb8-800d-29304c3a48f6.png)

A heatmap shown below helps show weekly usage patterns. We can see the heavy bike usage during weekday commute times, and weekend usage is spread throughout the middle of the day. Most weekday rides are around 7:00 AM to 9 AM and 5:00 PM to 7:00 PM. Weekend rides are highest from 10:00 AM to 7:00 PM.Those rides are mostly taken by male users.

![image](https://user-images.githubusercontent.com/114262970/214553398-ec261b2f-405e-4224-82b6-fbc3965889b2.png)

The graph below indicates the number of trips by duration, it shows that the majority of trips taken on CitiBike bikes are under an hour in length. ANd in addition, most of the bikes were taken by male customers who has a significantly higher number of rides unlike others.

![image](https://user-images.githubusercontent.com/114262970/214555394-59bf04eb-3047-4296-9b94-e7aa60e555ac.png)


## Summary
In conclusion, The bikeshare data analysis shows bikeshare services is popular in high traffic/busy areas of New York mostly during the month of August 2019 due to the nice weather(Higher number Tourists).
The majority of the rides were concentrated in the tourist location and commercial area of Manhattan. Most of the rideshare customers are male users and they rent the bikes  during morning and evening rush hours. This implies that Citi Bike services are used as an alternative to public transportation by commuting workers.

Due to the seasonality of this business, it is recommended to have additional statistical analysis and visualization to compare data for different months to determine trends across the year and also weather impact analysis to check the correlation between weather and rides.
