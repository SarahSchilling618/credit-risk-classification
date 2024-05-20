# credit-risk-classification

## Overview of the Analysis

The purpose of this notebook is to develop a Logical Regression Model using machine learning to determine whether a loan is healthy or at high-risk, in order to help lenders decide if they should help give customers the loans that they request.

## Results

After fitting and training the data provided, a confusion matrix was created with the following results:
Confusion Matrix:
[[18679    80]
 [   67   558]]

 This confusion matrix shows a high number of true negative and true positive results, but it also shows a few false negative and false positive results as well. This is normal in a confusion matrix, as it allows us to see potential shortcomings of the model and allows us to potentially fix them. We also ended up with the following classicification report:
           precision    recall  f1-score   support

           0       1.00      1.00      1.00     18759
           1       0.87      0.89      0.88       625

    accuracy                           0.99     19384
   macro avg       0.94      0.94      0.94     19384
weighted avg       0.99      0.99      0.99     19384

With a 99% overall accuracy, we can say that the model achieved its goal of creating an accurate way of determining if someone's loan is healthy or high-risk.

## Summary

Overall, the model has a very high accuracy rate in determining the status of someone's loans.
