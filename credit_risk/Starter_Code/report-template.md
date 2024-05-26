# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis is to create and analyze a machine learning model that will be used to predict the creditworthiness of borrowers.

* The financial infomration used includes information about the borrowor,such as income, debt_to income, number of account, total debt; loan information, such as amount of loan, interest rate, status.

* The model is trying to predict 2 classes: healthy loan (0) and high risk loan (1). Value counts aer as follow:
 loan_status
0    75036
1     2500

* The machine learning process started with data cleaning and some EDA to view the data being worked with. Next, I selected the X and y features for testing, split the test and training datasets, fit the model and finally worked with the test sample to evaluate the accuracy and other metrics.

* Since there was a binary component within the data (healthy or not healthy) a LogisticRegression model was used. 

## Results
precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.94      0.89       619

    accuracy                           0.99     19384
   macro avg       0.92      0.97      0.94     19384
weighted avg       0.99      0.99      0.99     19384


* Machine Learning Model 1:
    * Precision: 92%
    * Recall: 97% 
    * Accuracy: 0.99

## Summary

The machine learning model that was produced his a high accuracy and recall/precision rate. It is a good model to predict the creditworthiness of customers.
