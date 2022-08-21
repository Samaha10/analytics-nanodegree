# Ford GoBike System Data Exploration
## by Amro Samaha


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in February 2019 for approx 175,000 ride (after cleaning).
Preliminary Wrangling involved dropping null rows and converting to proper types (ex: time columns to datetime, ids to ints). Further created columns as member_age, weekday and hour to assist in easier investigation


## Summary of Findings

> In the exploration, found that most users are Subscribers with a number of Customers. When further investigating gender, found that majority of Users were Males then second Female then Other. Distribution of ages illustrate that most common age range is between 24 to 37 years old, with two peaks at 26 and highest at 31 years old. Counts of ages below 23 seem to be low with even lower counts above 40 years old. Looking at time, found that highest rides frequency is during weekdays with lowest on weekends. Ride counts across days of the month vary a lot between ups and downs with sharpest drop on day 9 of the month. majority of subscribers are Male. Older ages are more likely to be subscriber than customer. Majority of subscriber are not in bike share for all, as users in bike share for all form a very small proportion. Further, found that subscribers in bike share for all are younger on average than subscribers who are not. Looking at duration distribution by user type, found that Customers tend to have longer rides than Subscribers. Presumably, Subscribers use rides for day-to-day rides while Customers use rides for non-frequent long rides.


## Key Insights for Presentation

> For the presentation, I focus on the main features duration, frequency of rides over time and User types especially subscriber, in terms of effect and factors. 
I start off by introducing disrtibutions of main features, then factors affecting and how they affect main features. Further focus on gender and time frequency effects on user types. Illustrated as well interaction between duration and time frequency in terms of day hour.