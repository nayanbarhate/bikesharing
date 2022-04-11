# bikesharing
Tableau to create visualizations exploring NYC bike-sharing program data.

## Overview
This Tableau story can be seen, in its entirety, [at this link](https://public.tableau.com/app/profile/nayan.barhate/viz/NYCCityBikeChallengeAnalysis/NYCCityBikeAnalysis?publish=yes).

The framework for this project was to analyze bikeshare data from CitiBike in New York City for presentation to investors looking to begin a bikeshare program in Des Moines, Iowa. While Des Moines is a long way away from the hustle and bustle of NYC, this analysis might help answer a few key questions:
- Who uses bikeshare programs?
- What area of a city sees the most bikeshare usage?
- What time of day are bikes used the most and the least?
- How much are the bikes used and by whom?

## Results
While the demographics of Des Moines may be different from the make up of the citizenry of NYC, a cursory look at the makeup of CitiBike riders may shine light on who bikeshare might appeal to, regardless of locale.
***
![NYC CitiBike Customer Description](https://github.com/nayanbarhate/bikesharing/tree/main/blob/Images/Customer_description.png)

In the above image we can see that more than 3/4 of the users are **Subscribers**, who make regular use of the bikes and are a predictable source of income for the program. Bikeshare program users are also predominantly male, at approximately 5/8 to only about 1/4 female. The remaining 1/8 gender is unknown or undeclared.
***
![NYC CitiBike Peak Use Hours](https://github.com/nayanbarhate/bikesharing/tree/main/blob/Images/August_peak_hours.png)

This chart displays the number of bike rides initiated during each hour of the day, totaled across the entire month of August. We can see peak usage during morning rush hour and end-of-workday commute times. What is also of note is the low-usage hours between 2 AM and 5 AM. These hours would be the best times to conduct **bike repairs** and **redistribution** of bikes from full stations to less-full stations.
***
![NYC CitiBike Total Rides by Time](https://github.com/nayanbarhate/bikesharing/tree/main/blob/Images/Bike_repair.png)

To see what proportion of the bikes get heavy usage, we can look at this stepped-level heatmap. This tiling shows each individual bike in the fleet, sized, colored, and sorted by its **degree of usage** during the month. In red we can see a small number of bikes that get heavy usage, which will require more regular repair, or possibly even replacement. In shades of green, we can see all the other bikes that get much lower levels of use, and will probably not need to be repaired as often.
***

![NYC CitiBike Checkout time for user](https://github.com/nayanbarhate/bikesharing/tree/main/blob/Images/Checkout_times_by_user.png)

This graphing of number of trips by duration show that the vast majority of trips taken on CitiBike bikes are under an hour in length. More specifically, most trips are under a half-hour in length, with a swift dropoff in number of rides over an hour in length.
***
![NYC CitiBike Trip Duration by Gender](https://github.com/nayanbarhate/bikesharing/tree/main/blob/Images/Checkout_times_by_gender.png)

This breakdown of number of rides by duration, separated by gender, makes it even more apparent how many more rides are taken by male-identifying customers.
***

![NYC CitiBike Trips by weekday per hour](https://github.com/nayanbarhate/bikesharing/tree/main/blob/Images/Trips_by_weekday_perhour.png)

In this heatmap showing weekly stoptime with the per hour.
***

![NYC citibike Trips by gender](https://github.com/nayanbarhate/bikesharing/tree/main/blob/Images/Trips_by_gender.png)

A heatmap also helps show weekly usage patterns. Once again we can see the heavy bike usage during **weekday commute times**, and weekend usage is spread throughout the middle of the day. An interesting anomaly is the relatively low bike usage during Wednesday's end-of-day commute. It could be useful to explore reasons for this (system outage, Wednesday holidays in August, something less obvious?), but it could just be an arbitrary anomaly. Also, we can still see that low-usage time in the early morning hours, every day of the week.
***


![NYC CitiBike Trips by User Type, by Day, by Gender](https://github.com/nayanbarhate/bikesharing/tree/main/blob/Images/User_trips_by_gender_by_weekday.png)

Lastly, this heatmap reinforces how much of the userbase is dominated by male-identifying, subscribing users. Why this is the case is unclear and warrants additional study.
***

## Summary
In conclusion, bikeshare services are remarkably popular in busy metropolitan areas, where occupied real estate is densely packed and parking spaces may be scarce. The user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem a reliable market. And main usage seems focused around morning and evening commute times.

If I were to pursue additional lines of inquiry for analysis and visualization, given the data provided, I would explore:
- trip starting and ending locations during morning and evening rush hour time-windows, to display the flow of traffic between neighborhoods at peak hours;
- average trip duration, by birth year, by gender, to explore if there was any difference in male or female or un-gendered riders as they age.








