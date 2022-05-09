# Bikesharing with NYC CitiBike data

## Overview
Have created two Tableau deliverables for:
1. Module 14- 
2. Challenge for Module 14- 

The guideline for this project was to analyze bikeshare data from CitiBike in New York City for presentation to investors looking to begin a bikeshare program in Des Moines, Iowa. While Des Moines is a long way away from the hustle and bustle of NYC, this analysis might help answer a few key questions that would help them to make a decision.
For this, Tableau was used to present detailed worksheets and dashboards and story was created from those worksheets to emphasize on decision parameters.

## Approach
### Deliverable 1: Change Trip Duration to a Datetime Format
Per the ask, using Python and Pandas function, changed the data type of "tripduration" column in csv file from an integer to a datetime in Jupyer notebook to get the time in hours, minutes, and seconds (00:00:00) and leveraged it for creating worksheets in Tableau.

### Deliverable 2: Created 5 Worksheets highlighting below Visualizations
1. Checkout Times for Users
2. Checkout Times by Gender
3. Trips by Weekday for Each Hour
4. Trips by Gender (Weekday per Hour) 
5. User Trips by Gender by Weekday 

### Deliverable 3: Created a Story and Report
Story 1: Created using 5 Worksheets- https://tabsoft.co/3kQKE0D

Story 2: Created 2 Dashboards first and used them to create a story- https://tabsoft.co/3ypxe3D


## Results:
1. **Checkout Times for Users** - 
This graphing of number of trips by duration show that the vast majority of trips taken on CitiBike bikes are under an hour in length. More specifically, most trips are under a half-hour in length, with a swift dropoff in number of rides over an hour in length.

2. **Checkout Times by Gender**
This breakdown of number of rides by duration, separated by gender, makes it even more apparent how many more rides are taken by male-identifying customers.

3. **Trips by Weekday for Each Hour**
A heatmap also helps show weekly usage patterns. We can see the heavy bike usage during weekday commute times, and weekend usage is spread throughout the middle of the day. An interesting anomaly is the relatively low bike usage during Wednesday's end-of-day commute. It could be useful to explore reasons for this (system outage, Wednesday holidays in August, something less obvious?), but it could just be an arbitrary anomaly. Also, we can still see that low-usage time in the early morning hours, every day of the week.

4. **Trips by Gender (Weekday per Hour)**
5. **User Trips by Gender by Weekday** 
This heatmap reinforces how much of the userbase is dominated by male-identifying, subscribing users. Why this is the case is unclear and warrants additional study.

There are one or two additional charts available in the Tableau analysis, but they tell pretty much the same story that has already been displayed above.

## Summary
In conclusion, bikeshare services are remarkably popular in busy NYC metropolitan, where occupied real estate is densely packed and parking spaces may be scarce. The user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem a reliable market. And main usage seems focused around morning and evening work commute times.

If I were to pursue additional lines of inquiry for analysis and visualization, given the data provided, I would explore:
Trip starting and ending locations during morning and evening rush hour time-windows, to display the flow of traffic between neighborhoods at peak hours;
average trip duration, by birth year, by gender, to explore if there was any difference in male or female or un-gendered riders as they age.


