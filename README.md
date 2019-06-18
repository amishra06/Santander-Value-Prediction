# Santander Value Prediction (Kaggle, June 18, 2018 - August 20, 2018) 

## Problem Statement
In this competition, Santander Group is asking Kagglers to help them identify the value of transactions for each potential customer.

## Data
An *anonymized* dataset containing numeric feature variables, the numeric target column, and a string ID column is provided.
The task is to predict the value of target column in the test set.

## My Approach

* Since training data was anonymized, I generated new features using aggregation and dimensionality reduction methods.
* Got important features to use in training 
* Trained model using XGBoost and LightGBM
* Final prediction was combination of both.

# Result
Public Leaderboard - 1.54582
Private Leaderboard - 1.51671
(The evaluation metric for this competition is Root Mean Squared Logarithmic Error)
