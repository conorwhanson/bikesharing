# Citibike Bikesharing in Des Moines, IA
![bike](https://github.com/conorwhanson/bikesharing/blob/main/resources/citi.png)

### Purpose & Overview
The purpose of this analysis was to draw on Citibike bikesharing data gathered from New York City in August of 2019. The dataset contains helpful demographic information, average trip duration, the most popular times to get a bike, and the kind of user (whether a generic customer or a subscriber), among other helpful data. Based on this data [a Tableau dashboard](https://public.tableau.com/views/CitibikeChallenge_16567013206560/CitibikeinNewYork?:language=en-US&:display_count=n&:origin=viz_share_link) was created to visualize the NYC data to assist in replicating this business in Des Moines, IA.

### Results

Beginning with a geographical overview of Manhattan helps visualize the most popular starting and ending locations for bike rentals. Both starting and ending locations are heavily clustered to the south of Central Park. This suggests that there are perhaps locations or attractions which are highly sought after or desirable to visit. | 
:-------------------------------------------------:|
![Starting_Locations](https://github.com/conorwhanson/bikesharing/blob/main/resources/top_starting_locations.png) ![Ending_Locations](https://github.com/conorwhanson/bikesharing/blob/main/resources/top_ending_locations.png)

Demographic data is key so as to offer a service to those who would really enjoy and utilize it. Not only do males represent the majority of bike users, but an overwhelming majority of the subscribers are males. Clearly, males utilize Citibike most often and are more likely to be paying subscribers of the service. Not only this, but Thursday between 5-6pm is the most popular day to rent a bike, with Saturday between 11-6pm having a steady stream of an average of 25,000 - 30,000 users per hour. |
:------------------------------:|
![Trips_by_gender](https://github.com/conorwhanson/bikesharing/blob/main/resources/trips_by_weekday_gender.png)
![Usertype_trips](https://github.com/conorwhanson/bikesharing/blob/main/resources/usertype_weekday_gender.png) ![Trips_weekday_hour](https://github.com/conorwhanson/bikesharing/blob/main/resources/trips_by_weekday_hour.png) 


Knowing how long a user rents a bike will help to make sure enough bikes are available. Further, it will aid in understanding how the bikes are utilized (short trips or long trips). The overwhelming majority of bikes are used for short duration trips of roughly 5 minutes. Additionally, these short trips are done by males at a rate of 3 to 1 compared to females. Short trips mean faster bike turnover between users, increasing the need for bike availability as well as maintenance to keep bikes road-ready. |
-------------------------------|
![checkout_duration](https://github.com/conorwhanson/bikesharing/blob/main/resources/Checkout_Duration.png)
![checkout_duration_gender](https://github.com/conorwhanson/bikesharing/blob/main/resources/Checkout_durationgender.png)

Finally, maintenance will be key to ensure smooth operation of daily bike rentals. Tracking bike usage by bike ID helps to know when a bike is due for maintenance, as well as which bikes get the most use and therefore will need more frequent maintenance. |
--------------------------------|
![bike_trips_by_ID](https://github.com/conorwhanson/bikesharing/blob/main/resources/bike_repairs.png)

### Summary & Recommendations
Based on the NYC Citibkie data a number of conclusions may be tentatively drawn to apply to a bike sharing business in Des Moines. 

1. Males use the service most. The overwhelming amount of bike rentals are by males and the majority less than 30 minutes. Further demographic research of Des Moines is needed to find out the area where the population density of males is highest. Not only this, but I would recommend a further data visualization that breaks down the ages of all genders, as this could impact the location of bike rental hubs (closer to colleges, nature preserves, etc) and would help create a more granular picture of bike usage.

2. 