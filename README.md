# bikesharing_


[link to dashboard](https://public.tableau.com/app/profile/kyle.kato/viz/NYC_Citibike_Challenge_16547386086170/Story1)


## Overview of Analysis
The pupose of this analysis is to provide investors with insights for investment in a potential bike-sharing buisness idea in Des Moines. We demonstrate:
* Length of time bikes are checked out
* Number of bike trips for all riders and genders, per hour
* Number of bike trip for each type of user, per hour

We analyzed the trip duration for each instance a bike was utilized. We analyzed the elapsed time aginst how long the bikes were check out, the gender of rider, the hour of the day, and days of the week.

## Results

#### Trip Duration of every observation recorded:

![tripduration_hour](https://user-images.githubusercontent.com/99375741/173982109-793a8f0c-cf98-45db-934b-f3be8e548955.png)

The line graph shows how many bikes are checkout and how long they have been checkout for. We see a steep rise and falls, showing almost every bike is returned within an hour.




#### Trip Duration of every observation recorded by Gender:

![tripduration_hour_gender](https://user-images.githubusercontent.com/99375741/173977664-3cb4806a-f1cc-4ad8-8b71-61f4b82fc15a.png)

This line graph is similar to the previous elapsed line graph, but this graph breaks down the number of bikes based on gender. We can see 3x as many men take trips on the citi-bikes than do women.




#### Stoptime Heat Map:

![stoptime_heat](https://user-images.githubusercontent.com/99375741/173977869-042013bd-43d1-45e1-b152-eef17e59d359.png)

This heat map show the times of the day and day of the week which the riders stop riding. The number of trips greater from 7am - 8am and 5pm - 6pm, most likely used in a commute. On weekends, they are most used from 10am to 5pm.




#### Stoptime Heat Map by Gender:

![stoptime_heat_gender](https://user-images.githubusercontent.com/99375741/173977885-ffc958b4-8c52-49c4-b358-5719cba3c42d.png)

This heat map is very similar to previous heat meat map, but instead of one heat map, we created 2, one for each gender. We can conclude the patterns are very similar, but the males use the bikes more often.




#### Trips by Gender by Weekday:

![trip_gender_weekday](https://user-images.githubusercontent.com/99375741/173978119-c1741d3f-66de-4da0-8bd5-52b07f1ed228.png)

2 heat maps show the days of the week with the most activity based on wether or not the user is subscriped to the citibike program and depending on their gender. Customers do not use the bikes often. Subscribers are much more likely to use bikes. Men, again, are more likely to use the bikes, especially on Monday, Tuesday, Thursday, and Friday. 




#### Top Start Locations:

![top_start_locations](https://user-images.githubusercontent.com/99375741/173978153-e90c46ae-906f-4065-b536-b029a7616d3c.png)

Heat map shows the most popular locations to start a bike ride. The larger and more red the point is, the more popular of a start location that point is.




#### Avg Trip Duration by Birth Year:

![avg_tripduration_birthyear](https://user-images.githubusercontent.com/99375741/173978271-eac989f5-87f4-4e1d-b4d8-4e818421237d.png)

Area graph doea not provide great insights. 




## Summary

In conclusion, men that are subscribers are far more likely than women and/or customers to use the citibikes. These citibikes are also used to commute to and from work for many subscribers. The bikes are also enjoyed on the weekends but not to the extent as thay are used for commute.

In a future analysis, I would like to vizualized the most popular road/routes with a heat map. Using the start and end point, we would be able to map the path. Aggregating the data will show us the most popular roads for citibikes.

I would also like to compare the routes everyday to see how many consistent starting and end points happens everyday. If a start point and end point are the same everyday within 30 minutesm you can determine how moany people are using the bikes regularly for commute.

