# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis was to create a data model that predicts the credit worthiness of borrowers. We were given historical data about different borrowers and thier loan status. There were 77,535 records in the database. The database also contained data on the loan size, the interest rate of the loan, the borrowers income level, the number of accounts the borrower had, how many marks it had against its credit score, and the total debt. We then took the data and split it into a training and testing datasets. We then created a Logistic Regression model and trained it on the training data. We then ran the model on test data to see how good the model was at predicting data it hadn't seen before.   

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  - Balanced accuracy score: 94%
  - Precision score: macro average 93% / weighted average 99%
  - recall score: macro average 94% / weighted average 99%

* Machine Learning Model 2:
  - Balanced accuracy score: 99%
  - precision score: macro average 94% / weighted average 100%
  - recall score: macro average 99% / weighted average 99%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

I would recommend using this model to predict the creditworthiness of borrowers, because it has over ~94% accuracy in predicting the outcome of the repayment  of the initial loan. Given the more accurate understanding of creditworthiness of borrowers, the lender would be able to make an adequate profit of this loan book. 
