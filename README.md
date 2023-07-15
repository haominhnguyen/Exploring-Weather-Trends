# Ford GoBike Data Analysis
## by haonm

## Data set
* At this session, i will download data of ford go bike system from 1-2019 -> 12->2019 to analyze it. Ford GoBike is the Bay Area's bike share.
* Initially I see the data has 2506983 records , after cleaning invalid data of duration_sec I see data set reduced to 2506944 records and 15 columns


## Summary of Findings

* After analyzing and removing unnecessary data, I found the peak travel time was around 550s and confirmed that the trips were mostly short trips.
* Subscribers take trips in the early morning and late afternoon on weekdays. The trend of the majority of trips made during the week and weekend is less.
In general, customers are like subscriber, trips do the same, but I see a lot of traffic on weekends. The morning moves seem to me to see less. The conclusion is that cycling is also clearly affected by the season as shown in the chart. Customers have popular usage in December, and subscribers are the opposite.
*  Iam most interested in the travel time of each trip. Based on the user type, I want to analyze the preferences, average travel time and bicycle usage frequency of different types of users (Subscriber & Customer)
* Information about the date, time and duration of the ride helps me see how long the ride will take. By analyzing the travel time of the trip (starting and ending) I was able to calculate the average of the trips and from that I was able to analyze the preferences, frequency of use by group information. message of type user
* Bicycle usage increases from 7am to 9am in the morning and decreases from 10am to 3pm, then increases again from 4pm to 6pm and continues to decrease again from 7pm onwards. Bicycle usage peaks at 8am and 5pm
* Bike usage is high during the week and decreases on the weekend.
* With monthly analytic, December is probably the month with the least use of bicycles. The two months with the most use of bicycles are March and July.


## Key Insights for Presentation

* In my presentation, I am starting from the variable duration_sec (In seconds) and then analyzing in detail in other aspects: hours, days, months. Based on that, I will analyze the frequency, interests, ... by type of user and give specific data between subscribers and customers,