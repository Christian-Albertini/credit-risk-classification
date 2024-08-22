# credit-risk-classification
UNC Module 20 Challenge

## Overview of the Analysis
The purpose of this analysis is to predict credit risk for peer-to-peer lending using machine learning.  The data provided included information on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt and loan status.  I used this data to predict if a loan was healthy or high risk.  The dataset contained the information from 75,036 healthy loans and 2,500 high risk loans.  In order to perform the analysis, the dataset had to be split into training and testing sets by splitting the labels from the original dataset.  I then created a logistic regression model and fit the training data to that model.  I then ran predictions using the testing data on the model.  I then created a confusion matrix and classification report for my findings.

## Results
* Machine Learning Model 1:
  * Accuracy: 99%
  * Precision:
    * Healthy Loans: 1.00
    * High-Risk Loans: 0.85
  * Recall:
    * Healthy Loans: 0.99
    * High-Risk Loans: 0.91

## Summary
The model was able to strongly predict healthy loans, but there was a significant margin of error for high-risk loans.  This model is good for use to predict healthy loans, but a new model should be designed that is better at predicting high-risk loans, as those are more dangerous to mistake as healthy loans than predicting healthy loans to be high-risk.
