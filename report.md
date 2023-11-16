# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of the anaylsis was to determine creditworthiness given specific information.
* Information included loan size, interest rate, borrower income, debt to income ratio number of accounts,
  derogatory marks and total debt.
* We did our analysis using the loan_status column as the target column that we were trying to predict.
* We used Logistic Regression as well as Random Over Sampling for this analysis.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  *   precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384



* Machine Learning Model 2:
  *     precision    recall  f1-score   support

           0       0.99      0.99      0.99     75036
           1       0.99      0.99      0.99     75036

    accuracy                           0.99    150072
   macro avg       0.99      0.99      0.99    150072
weighted avg       0.99      0.99      0.99    150072

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* It seems like the second model performed slightly better on the high risk loans and about the same for healthy loans. Given this information I would recommend the second model over the first one. I would however like to see a more balanced data set for testing.



