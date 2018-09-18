# Predicting-bike-rental-demand
Jupyter notebook for forecasting the bike rental demand in Washington,D.C

# Requirements
Install conda for python, which has all the necessary packages for data manipulation and machine learning.

# Description
Bike sharing systems therefore function as a sensor network, which can be used for studying mobility in a city.This is a kaggle competition in which we need to historical usage patterns with weather data in order to forecast bike rental demand in the Capital Bikeshare program in Washington, D.C.

# Libraries Used
1.Pandas
2.Numpy
3.Matplotlib
4.Seaborn

# Regressor Used for Prediction
1.AdaBoost Regressor

# Evaluation Metric Used
1.R2 Score
2.Mean Squared Error

# Procedure
# Step 1: 
Data cleaning - Check for any missing values in the dataset and try to get rid off it either by deleting it or replacing it with values appropriate to the feature. Also get to know the types of each feature in the dataset and make the data ready for EDA.
# Step 2:
EDA - Exploratory Data Analysis, this is nothing but visualizing the important features in the dataset, so that we could find some outliers, also we can find correlation between the different features in the dataset.
# Step 3:
Now Split the dataset into train and test to predict the bike rental demand
# Step 4:
Use Adaboost Regressor to train your model
# Step 5:
Using the trained model for forecasting the demand using the test dataset. 
