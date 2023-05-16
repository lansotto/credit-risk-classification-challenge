## credit-risk-classification-challenge
U of T's SCS Data Analytics Boot Camp Challenge 20 - Supervised Learning


# Credit Risk Analysis Report

# Overview
The purpose of this challenge assignment is to utilize various techniques to train and evaluate a model based on loan risk.  A dataset of historical lending activity from a peer-to-peer lending services company is utilized to build a model that can identify the creditworthiness of borrowers.  Using a logistic regression model, credit worthiness was assessed.  This involved separating the data into training and testing datasets.  The training dataset was used to train the model to determine the credit worthiness.  The testing data was then fitted and the model's performance in terms of accuracy was calculated.  A classification report was generated to view the precision, recall and F1-score of the model.

# Results
* The logistics regression model did a great job of predicting the 0 (healthy loans) to 1.00 precision, 0.99 recall, and an f1-score of 1.00 
* The model does a poorer job of predicting 0 (high-risk loans) in comparison.  
* For 0 (high-risk loans), the precision score was 0.85, recall score was 0.91 and the f1-score was 0.88.

# Summary
The higher precision, recall and f1-score for healthy loans is likely due to the data is so unbalanced, there are far more healthy loans than high-risk loans.  The precision, recall and f1-score for high-risk loans was lower than for high-risk loans, likely due to the unbalanced data.  I would recommend the model for because it does an excellent job of identifying healthy loans, with precision of 1.00, recall of 0.99 and f1-score of 1.00.  For the loans that the model has identified as high-risk, further investigations can be done to determine if those loans should be approved.

