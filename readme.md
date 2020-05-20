# Analysis Bay Area Bike - Udacity Project
## by Sara Vicente

[Project Rubric](https://review.udacity.com/#!/rubrics/1795/view)

**Bay Wheels** offers a fun, easy and inexpensive transportation option for everyone. Bay Wheels stations and bikes are available in the Lyft app throughout San Francisco, East Bay, and San José.

In [this page](https://www.lyft.com/bikes/bay-wheels/system-data) I found the **Bay Wheels travel data** for public use. This data has benn provided in accordance with the Bay Wheels License Agreement.

### Structure of the dataset
The [data](https://s3.amazonaws.com/baywheels-data/index.html) contains several anonymous ride trip made in a bike-sharing system covering the greater San Francisco Bay area. Each of them including:

- **duration_sec:** Trip duration (seconds)
- **start_time:** Start date and time
- **end_time:** End date and time
- **start_station_id:** Identification of the station of departure
- **start_station_name:** Name of departure station
- **start_station_latitude:** Departure station latitude
- **start_station_longitude:** Starting station length
- **end_station_id:** End station identification
- **end_station_name:** End station name
- **end_station_latitude:** End station latitude
- **end_station_longitude:** End station length
- **bike_id:** Identification of the bike
- **user_type:** User type (subscriber or consumer - "Subscriber" = Member or "Consumer" = Casual)
- **member_birth_year:** Member's year of birth
- **member_gender:** Member's gender
- ( * ) bike_share_for_all_trip: No information given

Preliminary Wrangling: This dataset required some data wrangling in order to make it tidy for analysis.


# Ford GoBike Data Analysis for the City of San Francisco in 2018

## Key Insights 

> 1.  Most riders are male subscribers.
> 2.  The number of subscribers is much higher than the number of customers. For both, the months with the highest number of riders go from May to October. When it comes to weekly trend, it is curious how on the weekends, for subscribers, the number of rides decreases considerably while for customers it increases slightly. 
> 3. The customers rides last an average of approximately 26 minutes, while the subscribers rides last an average of 11 minutes. The longest trips are made by young people between 10 and 20 years old, again, this might be due to the fact that these use the service to take a leisurely ride around the city and not to go to work or run errands (taking this less time). The users for whom the rides take least time are those between 30 and 40 years old.
> 4. For subscribers: it is clear that the large volume of rides occurs at two peak hours (8am and 5pm) and this happens from Monday to Friday. During the weekend, the number of rides decreases sharply. For customers: on the contrary, the number of rides is larger on weekends and this occurs in a distributed manner over time from 10 in the morning to approximately 7 in the afternoon. From Monday to Friday occurs something similar to what has been described for subscribers, but with a slight difference: subscribers use the bike a bit more at 8am than at 5pm, while customers ride a bit more at 5pm than at 8am.
> 5. Rides duration range is longer for subscribers than for customers. For subscribers: The highest average duration of rides by age range and by month was given for users between 10 and 20 years old in the months of April and May. For subscribers: The highest average duration of rides by age range and by month was given for users between 10 and 20 years old in March. The lowest average duration took place in December for users between 30 and 40 years old.
> 6. There is a clear trend between subscribers and customers can be differentiated in all of the most popular stations. Subscribers always take the bike an average of an hour earlier than customers.