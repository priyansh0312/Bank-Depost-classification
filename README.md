# Bank-Depost-classification

Bank Marketing Data Set from UCI Machine Learning Repository

## Problem Statement
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. 

## Results
- Trained 3 ML models with and without hyperparameter tuning
- `Logistic Regression` with Hyperparameter tuning outperformed all the models in terms of the `Recall` and `F1-score` - `0.88` and `0.54` respectively
- `Random Forest` with hyperparameter tuning outperformed all the models in terms of accuracy - `91.02%`

The aim of the model was to reduce the `False Negatives`  by peaking the `Recall` in order to reduce the loss of potential clients for taking a deposit 
