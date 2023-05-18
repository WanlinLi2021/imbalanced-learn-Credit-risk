# Module 12 Report 

## Overview of the Analysis

In order to predict the credit risk, a dataset with features of loan size, interest rate, borrower income,percentage of debt to income, number of accounts, derogatory marks, and total debt are used for  the machine learning of classification. 

The loan status is what we need to predict. In the dataset 0 represent healthy loan while 1 represent high-risk loan.

A total 77536 rows of data will be used in this study. However, only 2500 of them are high-risk loan. Therefore, this classification dataset is highly imbalanced. Since the limitation of the size of input dataset, RandomOverSampler module from the imbalanced-learn library was used to resample the data.

For binary  supervised classification, Logistic Regression Model was used.

A comparation of performance before and after Random Over Sampling was performed.



## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy: 0.95
  * Precision: 0.99
  * Recall: 0.99



* Machine Learning Model 2:
  * Accuracy:0.99 
  * Precision: 0.99
  * Recall: 0.99

## Summary

* The Logistic Regression Model with Random Over Sampling perform better.

