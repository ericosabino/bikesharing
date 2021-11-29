# Bikesharing

# Overview of the analysis

The purpose of this analysis is to push the CitiBike Data Reports one step further to provide more data to potential investors and solidify the business proposal.

Pandas was used to change the "tripduration" column from an integer to a datetime datatype, and a set of new visualizations was created, using the converted datatype.

# Results

The data in the file contains a total of 2,344,224 rides. Most of these rides had durations lower than 1 hour, and, in fact, 145,752 rides had a durations of only five minutes, as we can see below:

![](/Images/01_Checkout_Times.png)
##### Fig 01. Checkout Times for Users

From these 145,752 rides, 108,087 are male riders, as they represent the biggest part of the total users:

![](/Images/02_Checkout_per_Gender.png)
##### Fig 02. Checkout Times per Gender

In terms of starttime, the most popular time to start the rides is at 6 PM at Thursdays.

![](/Images/03_Trips_by_Weekday.png)
##### Fig 03. Trips by weekday for Each Hour

When comparing starttime by gender, 11,336 female and 30,746 male riders started their trips at Thursdays 6 PM. 
Among the ones with gender classified as "unknown", the most popular time to start a ride is Saturday 12PM, where 5,669 riders started their trips.

Trips by Gender - Female | Trips by Gender - Male
:-------------------------:|:-------------------------:
![](/Images/04_Trips_by_Gender_female.png)  |  ![](/Images/04_Trips_by_Gender_male.png)
##### Fig 04. Trips by Gender

In terms of subscribers, both male and female riders that have a subscription are more active. The users with gender classified as unkown are more active as indicidual customers than subscribers.

![](/Images/05_Subscribers.png)
##### Fig 05. User Trips by Gender (Subscribers vs Customers)

Lastly, data shows that the most popular places to start and end rides is in Manhatan, most probably due to the large number of people workintg in the area.

Top Starting Locations | Top Ending Locations
:-------------------------:|:-------------------------:
![](/Images/06_Starting_Locations.png)  |  ![](/Images/07_Ending_Locations.png)
##### Fig 06. Top Starting and Ending Locations


## Resources:

The report where the screenshots above were captured can be found at
[this link](https://public.tableau.com/app/profile/ericosabino/viz/CitiBikeTripData-Challenge/NYCCitibikeAnalysis).



# Summary

## Conclusions in a nutshel

The main conclusions of this analysis were, in a nutshel:

1. There was a total of 2,344,224 rides registered. 145,752 rides had a durations of only five minutes, where 108,087 are male riders.

2. 11,336 female and 30,746 male riders started their trips at 6 PM on Thursdays, which is the most popular time to start a ride.

3. Subscribers are more active than customers.

4. Manhatan is where most trips happen.


## Recommendations to expand the analysis

As we always can go a step further, I would create some extra visualizations to expand the analysis and provide additional insights.

1. Number of rides per week: that would give insights about seasonality affects the numer of trips.

2. Duration per location: that would help us to understand what places have users that spend more time on their rides.