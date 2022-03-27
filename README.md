# Bikesharing

## Overview

The purpose of this analysis is to examine New York City bike sharing data as a starting point to understand what might be required for establishing a bike share system in Des Moines, Iowa. The New York Citibike system shares data relating to the number, location, duration, and type of trip. We used Tableau to examine trip data from August 2019 to see what we can learn about operating a bike share system.

## Results

The full [NYC Story](https://public.tableau.com/app/profile/sophie2348/viz/citibike_16483903590760/NYCStory) is published on Tableau.

Looking at the checkout times (trip duration) we can see that most trips are short, at around 5 minutes long.

![Checkout Times for Users](<./screenshot1.png>)

The same pattern applies for both males and females:

![Checkout Times by Gender](<./screenshot2.png>)

However, it differs by user type. Subscribers mostly take short trips, whereas customers take just as many trips between about 5 minutes and 30 minutes in duration.

![Checkout Times by User Type](<./screenshot3.png>)

There is a distinct usage pattern during the week compared to weekends. Most trips coincide with commuter hours.

![Trips by Weekday per Hour](<./screenshot4.png>)

This pattern is consistent between males and females, but again we see that most users are male.

![Trips by Gender (Weekday per Hour)](<./screenshot5.png>)

The most popular day for subscribers is Thursday, and the most popular day for customers is Saturday.

![User Trips by Gender by Weekday](<./screenshot6.png>)

Looking in more detail we can see that non-subscriber customers use the system more during 10am and 6pm on weekends.

![Customer Trips by Weekday](<./screenshot7.png>)

Considering bike repairs, most bikes in the NYC area have completed between 50 and 300 trips.

![Bike Repairs](<./screenshot8.png>)

In NYC, most trips start in midtown or downtown Manhattan.

![Top Starting Locations](<./screenshot9.png>)

## Summary

From the data we can see that subscribers are the primary customers for the New York bike sharing system, with non-subscriber customers using the bikes more on weekends than during the week. Subscribers tend to take short rides and the usage pattern is correlated with commuters. Males represent the majority of subscribers and users of the system.

Based on these results I would recommend that any new bike share system focus on providing services useful for commuters and tourists, with many stations located close together supporting short trips. Marketing could focus on commuters but should also target females as a potentially underserved market.

Some additional analysis that might help includes:
* Does usage change during the month? We could plot the number of rides per day of month and look for patterns.
* Does the starting or ending location pattern differ for subscribers vs. non-subscriber customers?
