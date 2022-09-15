# bikesharing

### Overview of the analysis
An exploration of a dataset from a New York City bike share program in order to learn insights that might be applied to the creation of a similar business investment in Des Moines, Iowa. Pandas was used to convert one of the datatypes from the dataset, and then several visualizations were built in Tableau with this updated dataset.

### Results
![image](https://user-images.githubusercontent.com/107162310/190486933-610fda49-98dc-4e62-b148-e84a3b7fa9e3.png)

This first visualization is a map of NYC showing the top starting locations for bike rentals. The larger and darker blue the dot, the more popular the location. Understanding where most rentals take place in NYC can inform where to setup locations in the proposed Iowa business venture. For instance, if bikes are often rented at college campuses in NYC, it makes sense to place more bikes for rental on campuses Des Moines.

![image](https://user-images.githubusercontent.com/107162310/190487886-fec2a4ba-c49c-42ac-81a9-5919a76b3cc9.png)

This chart shows how long users are checking out their bikes. Notably, the vast majority of rides are completed in about half an hour. And certainly very few take longer than an hour.

![image](https://user-images.githubusercontent.com/107162310/190488161-616630e9-daf3-403b-b473-4d0543d7b182.png)

This chart is the same as the last but it breaks down the users by gender. You can see that, overall, more male riders take longer rides than do female riders.

![image](https://user-images.githubusercontent.com/107162310/190488371-87d2f9e3-da94-4b52-84dd-ad766db61cc6.png)

This visualization is the same map from our first image but now it's showing the top ending locations for bike rentals. This can help determine where most bikes might end up when riders are finished with them in Iowa.

![image](https://user-images.githubusercontent.com/107162310/190488565-1cefc34b-8f29-4c0f-b733-99f63728d797.png)

This heat map shows the number of bike trips by weekday per hour. The darker the color, the higher the count of biketrips on that day/at that hour. Thursday from 5-6pm appears to have the highest amount of trips.

![image](https://user-images.githubusercontent.com/107162310/190488664-b13a6a80-65d3-44ea-b2ef-9f08de52990a.png)

This heat map breaks down the prior heatmap further by introducing gender. It's clear that male users utilize the bikes at the busiest time on Thursday far more than female users.

![image](https://user-images.githubusercontent.com/107162310/190488719-fad53222-1ef6-4876-b915-82bac44bb2ca.png)

This final visualization is another heat map that splits up the usertype by customer or subscriber, and then analyzes how often the gender of both usertypes uses a bicycle per weekday. The darker blue, the more frequent. It's immediately clear that male subscribers are taking more trips than female subscribers.

### Summary
Tailoring the proposed bike share service in Des Moines to the same sorts of locations as the most popular trip starting points in NYC (landmarks, tourist attractions, densely populated neighborhoods, campuses, etc.) should help increase the chances that the venture is a success. It's likely that the user base, and particularly the subscribers, will skew male. Target marketing towards potential female customers to bolster the number of female riders.

Given the information available in the dataset, I would suggest the following additional visualizations:

1. Using the Checkout Time for Users as a starting point, I'd bring in the birth years of users and bucket them into perhaps 20 year increments. This could help get a sense of the duration of a ride by the age bracket of the user.
2. Recreating the maps showing the top starting locations/ending locations to limit this to only the busiest hours of the day, typically morning or evening commutes. This can help determine the most frequent journeys bicycles take in NYC and what to expect in Des Moines.
