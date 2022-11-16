# WeatherForecasting
The historical data used in this project is collected from NOAA [1](National Ocean Atmospheric Administration). 
of 9 years for a particular station of Montreal,Canada which is spilt into 2 parts training and testing data set. The data set of the year 2013 to 2020 is used for training the models and one year data of 2021 is used for testing whereas to observe the changing weatherpatterns.The training data consists of 3504 observations and 10 features.For pre-processing, we inspect each feature of the data for the following reasons:
-removal of features with regular missing data or assigning the value zero wherever appropriate
-removal of unimportant, irrelevant or duplicate features. After removal of the null values, we had 3503 observationsand 4 features. We then break the data into train, validation and test sets.
