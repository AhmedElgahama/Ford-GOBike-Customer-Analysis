# FordGoBike Customer Analysis
## by Ahmed Elgahama


## Introduction

Bay Wheels(FordGoBike) is a regional public bicycle sharing system in the San Francisco Bay Area, California. Beginning operation in August 2013 as Bay Area Bike Share, the Bay Wheels system currently has over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose.  The system is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States.

Bay Wheels is a public bicycle system, or bike-share scheme, in which bicycles are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" and return it at another dock belonging to the same system. Docks are special bike racks that lock the bike, and only release it by computer control. The user enters payment information, and the computer unlocks a bike. The user returns the bike by placing it in the dock, which locks it in place. Other systems are dockless. For many systems, smartphone mapping apps show nearby available bikes and open docks.


## Dataset

> Here we wrangle and explore Baywheel's trip data which it makes available for public use. Baywheel's trip data is anonymized and includes:

- Trip Duration (seconds)
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type (Subscriber or Customer)
- Rental Access Method ( App - Clipper )
- Bike share for all trips ( Yes - No )



## Summary of Findings

- When we related duration with weekdays, we saw that people are likely to go for long rides on weekends although most bikes get rented on weekdays.

- When we related duration with months, we saw that people have liked to go out on long rides and enjoy in summers from April till July. But after september, whenwinter starts people again start taking shorter rides.

- When we related duration with hours, we saw that there was an interesting pattern. During the early morning hours form 1a.m. to 4 a.m., people have less liked to rent bikes and also the ones who rented were also for short duration. While most number of bikes around 2 p.m. were rented for high duration of around 10 minutes.

-there is an interesting observation that customer user type are regular with renting with the same number all week on the other side subscriber user type decrease over weekends

- it seems that subscribers use the bikes neerly for the same time all days
on the other way customers tend to use the bikes for longer time on weekends
and that customers uses the bikes on average for longer times than subscribers all days

-Almost all the two rental access method groups show similar trend in terms of for what average duration they rented the bikes on each weekday
and that app users uses the bikes for longer times than clipper users all days

-it seems that subscribers use the bikes neerly for the same time all months
on the other way customers tend to use the bikes for longer time in the first half of the year
and that customers uses the bikes on average for longer times than subscribers all months

- Almost all the two rental access method groups show similar trend in terms of for what average duration they rented the bikes on June and July but they show the opposite trend in the months November and December where we can see that app users renting time decrease while clipper users time increase
and in general app users uses the bikes for longer times than clipper users all months




## Key Insights for Presentation

> People are likely to use bikes for in the beggining and ending of the wroking hours.
> Compared to the subscriber, the customer has a higher duration .
> people tend not to share bikes for all trips.
  
  
  
## RESOURCES
1. [Matplotlib Documentation](https://matplotlib.org/)


2. [Plots using FacetGrid Object](https://seaborn.pydata.org/generated/seaborn.FacetGrid.html)


3. [Pointplots](https://seaborn.pydata.org/generated/seaborn.pointplot.html)


4. [Countplots](https://seaborn.pydata.org/generated/seaborn.countplot.html)


5. [FordGoBike Data](https://www.lyft.com/bikes/bay-wheels/system-data)
