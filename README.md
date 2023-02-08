# Bikesharing

[link to dashboard](https://public.tableau.com/app/profile/andres.martin.rosas/viz/Bike_Challenge_16645726211920/NYCBikeStory "link to dashboard")

## Goal and Findings
The goal is to create patterns and trends in data of the previous location of the business and use it to manage expectations of a potential new location. Many implications were made through the data such as expecting more subscribers than customers, possible hours of maintenance, and the demographic.

## Overview
In an attempt to create a bike-sharing program in Des Moines, a story is created to demonstrate to investors that this idea is a strong business proposal. The data used is based off the CitiBike data of New York City to see what potential patterns and trends that may occur. To create a story with strong visualization, the data needed to be reformatted using pandas. After, Tableau Public was used to make visualizations that will make the data easy to comprehend.

## Results
![Generic_charts](/Images/Generic_charts.png)
In these charts show a general data analysis of the data. The line graph demonstrates durations of each trip. Based on this data, it shows a large peak for the first 20 minutes, with the tip of this peak going over 140K for a short while. By the time the first hour is completed, the number of bikes checked out is approaching zero. This implies that the bike-sharing program in Des Moines should expect a similar trend where most bikes are out for about an hour.

The heatmap on the right side shows the start times of the trips over the course of a week. The general pattern here is that there are high points of activity at 7AM to 9AM and 4PM to 7PM on weekdays, but on the weekends the high points of activity are from 11AM to 6PM. Because of the times that occur on the weekdays, there is some suggestion that people use the bike-sharing program for transportation from and to work or appointments while weekends are most likely using the bikes as a leisurely activity.

![GenderCharts.png](/Images/GenderCharts.png)
In this story point, the same charts as before are redisplayed, but separated by genders. In the top-left a pie graph was created to quickly show the distribution between male, female, and unknown. Looking at it shows use that approximately two-third of the users are male and about a quarter are female; the rest are of a undetermined gender. The pie graph is reflected in the rest of the charts, where the male has the highest peak (over 100K bikes) and the female count is lower (highest peak is about 30K). The heatmap also shows a higher number of male users by having a darker red color than the female category. However, in addition to the visual display of the diversity, the graphs demonstrates that the patterns between males, females, and unknown are the same. The line graphs still demonstrate the idea that peak duration times are within the first 20 minutes and approaches zero before the first hour. The heatmap shows the same pattern between genders as well but the male category is better shown because of the stronger contrast in colors as a result of the higher number of male customers. These trends show that ride-share program in Des Moines will likely have a strong male presence but females will utilize it similarly to men but in smaller numbers.

![Customer_vs_Subscribers.png](/Images/Customer_vs_Subscribers.png)
This heatmap compares the amount of subscribers vs customers in the bike-sharing program and then breaks it down to gender categories, similar to the previous charts. This strongly demonstrates that there are a lot more subscribers than there are one-time customers, shown by both females and males. Oddly, the people whose gender is undetermined have higher rate of being a customer than a subscriber. A pie chart is also placed to the side to demonstrate how much more subscribers there are then customers, which it seems a little less than 25% are customers.

![Start_vs_EndMap.png](/Images/Start_vs_EndMap.png)
![Start_vs_EndPoints.png](/Images/Start_vs_EndPoints.png)
The last story points show some the top starting vs top ending locations and five randomly point to see how they compared. The graph covering all the information demonstrates that the starting and ending locations are very similar throughout all of New York City. To get in more depth with this, the five points were select and compared. This comparison shows less than a 1,000 count difference, demonstrating a high return rate for an undetermined reason. If Des Moines is able to replicate this, it will save a lot of financial cost on reobtain bikes and distributing then to stations.


## Summary

When creating the bike-sharing program for Des Moines, there will be several expected patterns that will likely occur based on the New York City Citibike data. One expectation is that most riders will ride for about 20 minutes and will likely not exceed an hour, suggesting that there bike relatively small window time before a bike is returned to a station. This may be used to potentially determine how many bikes will be needed. The trends also indicate the high points in which people utilize the bikes depending if it is a weekday or weekend which shows that the best time for bike maintenance/inspections would be on the weekend from 5A, to 7AM. In addition to this trend, it also shows that a possible large demographic for this business will be people who need transportation to work. The bike-sharing program should also expect a lot more subscribers than customers as well as expect a heavy male user presence. Lastly, it could be expected that a similar amount of bike will leave a return from stations, particularly popular ones.    

![Bike_Utilization.png](/Images/Bike_Utilization.png)

In addition to these graphs, to further inspect the data to optimize the change of success. The chart above shows bike utilization, showing how much each bike, based on a Bike Id number, is used, with larger circles representing heavier utilization. This information does not tell too much on its own except which bike are utilized more, which is why it was not added to any of story points. It could be used to track the route of the heavily used bikes, which may tell why these bikes are used so often and may potentially suggest redistributions of the bikes so they are more evenly utilized. It would also be advisable to look at the age demography to see who is utilizing the bikes. This may be used to determine who we are missing and potentially make them into customers or subscribers.
  
