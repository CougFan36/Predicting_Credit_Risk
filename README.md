# Predicting Credit Risk
The purpose of this project was to create a predictive model for assigning credit risk to loans based on a variety of factors.  The data was pulled from LendingClub's API, and we used a full year's worth of data from 2019 to predict the credit-risk for loans issued in Q1 of 2020.

## Model Types
Because we were attempting to predict on a binary value, we used two classification modeling types: logistic regression and kNN (k Nearest Neighbors) clustering.  We train these models on unscaled data and then train them on the scaled data to identify any improvement.  

Finally, we present our conclusion on which model performed better based on the accuracy scores of each model.