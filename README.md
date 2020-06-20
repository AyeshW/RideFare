# RideFare Classification
Ride fare classification problem is to build a machine learning solution for predicting the calculated fare of a ride is correct or incorrect

## TaxiFare - Best Solution Notebook
- This notebook contains the best model which scored highest score in the Kaggle private leaderboard
- All the essential pre-processing anf feature engineering steps are included in this file

## Trip Fare - Approaches Notebook
- This notebook contains the all pre-processing, feature engineering, resamapling and model selection steps
- Mainly this file contains XGBoost Classifier model evaluation and predictions

## Trip Fare - Catboost Notebook
- CatBoost is the model used for the best solution
- This notebook contains all the pre-processing, feature engineering, resampling steps done with catboost model

## Trip Fare - Regression Notebook
- This is a completely different approach to address the above taxi fare classification problem
- In this approach, I predicted the fare value using other features of data labelled as correct and calculated the error between actual and predicted fare values. Later I calculated upper and lower percentile values of the error for correct data and data points beyond the boundaries classified as incorrect fares.
