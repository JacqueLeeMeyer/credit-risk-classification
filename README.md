# credit-risk-classification
Module 20 Challenge

# Model Report

## Overview of Analysis

The purpose of this model is to identify the probable creditworthiness of borrowers. The model used the following data:


* Loan Size
* Interest Rate
* Income
* Debt to Income Ration
* \# of Accounts
* Derogatory Marks
* Total Debt
* Loan Status


The model predicts creditworthiness in two categories, “Healthy Loan” (0) and “High-Risk Loan” (1).
The first steps in this machine-learning process were to separate the ‘Loan Status’ information from the rest of the data, then split the data into testing and training sets. Next, a Logistic Regression Model was created using the training data set and predictions were made on the testing data set. Lastly, the model was evaluated using a confusion matrix and a classification report.


## Results

Logistic Regression Model:
 * Accuracy: This model is 99% accurate overall.
* Precision: 
     * Healthy Loans- approximately 100% labeled as healthy are classified correctly
     * High-Risk Loans - approximately 87% labeled high-risk are classified correctly.
 * Recall
     * Healthy Loans- approximately 100% of actual healthy loans are classified correctly
     * High-Risk Loans - approximately 89% of actual high-risk loans are classified correctly

## Summary

Using this model to predict Healthy vs High-Risk borrowers is recommended based on its total performance. The overall accuracy of this logistic regression model is 99%, making it a good model to use for predicting creditworthiness of the borrowers. It is particularly good at predicting healthy loans, while still performing quite well on the high-risk. More data on high-risk loan characteristics would likely improve these predictions even further. 

___

Sources: No outside sources were used to write the code for this challenge.