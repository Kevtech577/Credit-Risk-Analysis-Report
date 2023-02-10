# Credit-Risk-Analysis-Report
Credit Risk Analysis Report


Overview

The purpose of this analysis is to determine the creditworthiness of borrowers using historical lending data from a peer-to-peer lending services company. The data is imbalanced, with a larger number of healthy loans compared to risky loans. To address this, two versions of the data will be used for model building: the original data and a resampled data using the RandomOverSampler module from the imbalanced-learn library. A logistic regression model will be used to make predictions on both datasets.

Results

Logistic Regression Model with Original Data
Balanced Accuracy Score:
Precision and Recall Scores:
Logistic Regression Model with Resampled Data
Balanced Accuracy Score:
Precision and Recall Scores:
Summary

The performance of both the logistic regression model fit with the original data and the logistic regression model fit with the resampled data will be compared. Based on the balanced accuracy scores, precision, and recall scores, a recommendation will be made for which model is more suitable for the task of determining the creditworthiness of borrowers. If neither model is recommended, reasoning for the recommendation will be provided.
