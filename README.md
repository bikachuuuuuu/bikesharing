# bikesharing

## Overview


In this analysis, bike-sharing data from NYC Citi Bike August 2018 is transformed such that the columns are the appropriate data types (namely datetime). After this, the data was uploaded to Tableau to create an extensive analysis of the riders of these bikes and their habits.
[Link to Tableau Dashboard](https://public.tableau.com/app/profile/rebecca.palmer4103/viz/NYCCitiBikeDataVisualization_16687350623240/NYCCitiBikeDataVisualization)

## Results

### August Peak Hours
![img1](https://github.com/bikachuuuuuu/bikesharing/blob/main/resources/augustpeakhours.JPG?raw=true)

We explored peak hours for the time period August 2019. Number of rides were sorted by each hour of the day.

The two peaks of usage was between hours 7 and 10 (7:00 am to 10:00 am) and hours 16 and 19 (4:00 pm and 7:00 pm).
Om contrast, the low point of usage was between hours 0 and 5 (12:00 am to 5:00 am).

### Top Starting Location
![img2](https://github.com/bikachuuuuuu/bikesharing/blob/main/resources/topstartinglocation.JPG?raw=true)

We plotted the density usage of starting location rides on a map of New York City. The larger and darker the color dot, the higher the density usage.

We found that many rides are started from locations such as Manhattan and the Empire State Building, with less usage around areas such as Greenpoint and Williamsburg.

### Checkout Times for Users
![img3](https://github.com/bikachuuuuuu/bikesharing/blob/main/resources/checkouttimesforusers.JPG?raw=true)

We visualized the distribution of bike rides by plotting how many bikes were rented for a certain time against the length of a ride by minutes.

We saw that the average trip length was approxiamately 5 minutes. The vast majority of rides were less than 30 minutes.

### Checkout Times by Gender
![img4](https://github.com/bikachuuuuuu/bikesharing/blob/main/resources/checkouttimesbygender.JPG?raw=true)

We visualized the distribution of bike rides by plotting how many bikes were rented for a certain time against the length of a ride by minutes, but this time we broke it down by gender. 

We found that those who identify as men are the majority of our riders, with their average ride being approxiamately 5 minutes.
Those who identified as women were our next largest group, whose average ride was approxiamately 6 minutes.
Our last group was the collection of people whose indentified gender was not known. Their average time seemed to be between 5 and 25 minutes.

### Trips by Weekday per Hour
![img5](https://github.com/bikachuuuuuu/bikesharing/blob/main/resources/tripsbyweekdayperhour.JPG?raw=true)

This heatmap shoows trips by weekday, per hour. We wanted to see which days and times have the heaviest usage of bikes, as well as which days and times have the lightest.
We can see that Thursday mornings and evenings have the heaviest usage of the bikes. However, we can see that for Monday through Friday, the bikes are commonly used between 7:00AM to 9:00AM, and 4:00PM to 7:00PM.

### Trips by Gender 
![img6](https://github.com/bikachuuuuuu/bikesharing/blob/main/resources/tripsbygender.JPG?raw=true)

This heatmap shows that men utilize the bikes the most. This information correlates with the fourth chart, as shown above

### User Trips by Gender by Weekday
![img7](https://github.com/bikachuuuuuu/bikesharing/blob/main/resources/usertripsbygender.JPG?raw=true)

This analysis was trips by gender, by weekday and user type (customers and subscribers). The chart shows that the customers' genders are relatively spread out. However, for subscribers, we can see that a majority of the subscribers are men, followed by women, then unknown.

## Summary

In conclusion, males most commonly rent these bikes in short periods before and after work or throughout the day on weekends. Females typically have similar patterns as the men, but in lower numbers. If NYC Citi would like to combat this difference, they would do best to advertise to women in the city during these hours.

An additional analysis to run is a map of where female users are renting their bikes from to ensure the accuracy of these advertisements.
Another would be make this same analysis for the end station of female users is. If there is a notable pattern with the end station as there is with the start station, advertising along this route would prove to be effective.
