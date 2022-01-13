# Ride duration prediction 
Wejdan Alzahrani

## Abstract
This project aims to build a ML model to predict the ride duration of bike sharing system's customers. Two models namely, Linear regerssion and gradient boosted trees were used.They were evaluated using mean absolute error matrix and got 6.77 and 6.17 respectively. 

# Design
The data is provided by Ford goBike system, and presents trips taken by the customers for the month of February of 2019. The prediction of the ride duration would  enable the bike sharing service provider to make more precise decision based on their customer's behaviour.

# Dataset 
Our dataset is Bike Sharing Dataset and it can be found [here](https://www.kaggle.com/chirag02/ford-gobike-2019feb-tripdata). The dataset contains around 183k observations with 15 features for each, 5 of which are categorical. Number of the features are relativaly correlated to the duration. There was a need to add more featurs such as sastart_hour and start_day which indicate the hour and day when the customer started the ride.

# Algorithms 
Feature Engineering

Mapping latitude and longitude to 3-dimensional coordinates so nearby continuous values would also be close in reality
Converting categorical features to binary dummy variables
Combining particular dummies and ranges of numeric features to highlight strong signals and illogical values for waterpoint status identified during EDA
Selecting subsets of the total unique values for categorical features that were converted to dummies, according to the number of samples they were associated with and their contribution to certain statuses

Models

-linear regression
-Gradient boosted trees 

Model Evaluation 

The entire training dataset of 171305 records was split into 80/20 train vs.


# Tools
- Pandas for data manipulation
- Seaborn, matplotlib and plotly for visualizing
- Sklearn and xgboost for modeling

# Cummnication
You can refer to the slides and visuals presented.


