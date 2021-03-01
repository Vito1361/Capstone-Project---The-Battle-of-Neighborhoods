# Capstone-Project---The-Battle-of-Neighborhoods
This is my final assignment of the Applied Data Science Capstone Course by IBM on Coursera
Introduction
Houston is the most populous city in the U.S. state of Texas, fourth-most populous city in the United States, most populous city in the Southern United States, as well as the sixth-most populous in North America, with an estimated 2019 population of 2,320,268. Houston's demographics show that it is a large and ethnically diverse city. An estimated 600,000 illegal immigrants resided in the Houston area in 2017,comprising nearly 9% of the city's metropolitan population.

This final project explores the best locations for seafood restaurants throughout the city of Houston. The seafood diet is based on the principle of health and longevity. Seafood is not only tasteful and mouth-watering but also offers various health benefits. Now when the idea of a healthy lifestyle conquered the minds of people all over the country, seafood restaurants became extremely popular, as they offer a healthy alternative to regular American eating habits. That's why potentially the owner of the new East European restaurant can have great success and consistent profit. However, as with any business, opening a new restaurant requires serious considerations and is more complicated than it seems from the first glance. In particular, the location of the restaurant is one of the most important factors that will affect whether it will have success or a failure. So my project will attempt to answer the questions “Where should the investor open a seafood restaurant?” and “Where should I go If I want great seafood?”

Data
In order to answer the above questions, data on Houston neighborhoods, districts to include boundaries, latitude, longitude, restaurants, and restaurant ratings and tips are required.

Houston data containing the neighborhoods and districts, latitudes, and longitudes will be obtained from the data source: https://www.kaggle.com/mrchristolpher/houston-texas-neighborhoods-lat-long-list

All data related to locations and quality of seafood restaurants will be obtained via the Foursquare API utilized via the Request library in Python.

Methodology
• Data will be collected from https://www.kaggle.com/mrchristolpher/houston-texas-neighborhoods-lat-long-list and cleaned and processed into a dataframe.

• Foursquare be used to locate all venues and then filtered by seafood restaurants. Ratings, tips, and likes by users will be counted and added to the dataframe.

• Data will be sorted based on ratings.

• Finally, the data be will be visually assessed using graphing from Python libraries.

Problem Statement
What is / are the best location(s) for seafood cuisine in Houston? In what Neighborhood and/or district should the investor open a seafood restaurant to have the best chance of being successful? Where would I go in Houston to have the best seafood?
