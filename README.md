# bikesharing
## Project Overview
The purpose of this project is to analyze NYC Citibike data to determine if a similar business would be successful in Des Moines, Iowa. The data was quite extensive and provided details on several relevant parameters such as gender, age, duration, time of day, days, weeks, and months. I used Pandas and created many visual illustrations which clearly shows distinct patterns. 
## Resources

- Dataset: [Citi Bike Data](), [201908-citibike-tripdata.csv.zip]()
- Software: Python 3.9.7, Anaconda Navigator 4.13.0, Tableau Public 2022.2.0, Jupyter Notebook 6.4.5, Tableau Public 2022.2.0

## Results

### Deployed Tableau Analysis
[Link to dashboard](https://public.tableau.com/app/profile/mlsclky/viz/NYCCitiBikeAnalysis_16580910263370/NYCCitiBikeAnalysis?publish=yes)

### New York Citi Bike data for August 2019

- In NYC, there were over 2.3 million rides for the month of August 2019.
- The subscribers were %81.07. The male users were %65.28. The female users were %25.10.
- In a wide range of the age users, younger users tend to have a longer trip duration.
- The most popular places for Citibike customers start and end their rides at the same locations.

![Dashboard.png]()

### August Peak Hours

- 5:00 PM and 6:00 PM are highest activity hours.
- 2:00 AM to 4:00 AM are low activity hours.

![August_Peak.png]()

### Checkout time for Users :

Most usage occurs at 5 minutes and 146,752 bikes were checked out for NYC Citibikes in August 2019. 1,122 Citibikes were checked out at 59 minutes.

![Checkout_Timesforusers.png]()

### Checkout times by Gender :

- There were 34,151 female Citibike users have 6 minutes duration at peak usage.
- There were 108,087 male Citibike users have 5 minutes duration at peak usage.

![Checkout_Timesbygender.png]()

### Trips by Weekday per hour :

Most of the rides from Monday through Friday occur during commuting hours of 8-9 AM and 5-7 PM.  The least usage between 12-5 AM Sundays through Saturdays.

![TripsbyWeekdayperHour.png]()

### Trips by Gender (Weekday per Hour) :

Both males and females users rides around 8 AM and 5 PM - 6 PM Monday through Friday. The rides are mostly taken by male users.

![TripsbyGender.png]()

### User Trips by Gender by Weekday :

The highest usage day was on Thursday for subscribers and the highest usage was on Saturday for non-subscribers.

![UserTripsbyGender.png]()

## Summary

There were several clear patterns in the data. Male riders significantly outweighed female riders and majority of the riders were subscribers. Day of the week was also important to analyze; the data shows most riders use the bikes during the week, Wednesdays being the worst performer which was strange to me. One can also see clearly most popular times for bike usage was during early morning (6am-9am) and late afternoon (5pm-8pm), which would lead me to think majority of the riders may be using the bikes to commute back and forth from work. The duration of rides averaged around 30mins, again another indicator majority of users may be commuting. 

I think it is a good idea to analyze and visualize the trends for NYC Citibike business model, but we have to factor in the population density of New York City area where close to 10 million reside in a relatively small acreage of land. Des Moines, Iowa may be a growing city and a new bike sharing business may be profitable, but these 2 cities are very different from each other in every sense of the word. 