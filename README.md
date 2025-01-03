# Module 12 Report

## Overview of the Analysis

The purpose of this analysis was to use machine learning to predict the creditworthiness of borrowers based on historical lending data from a peer-to-peer lending services company. Specifically, aiming to classify loans into two categories: healthy loans (0) and high-risk loans (1).

The dataset included financial information such as loan size, interest rate, borrower income, debt-to-income ratio, the number of accounts, derogatory marks, and total debt. The target variable was loan_status, where:

* 0 represents a healthy loan.
* 1 represents a high-risk loan.
Key stages of the machine learning process included:

1. Data Preprocessing: Splitting the data into features (X) and labels (y) and separating it into training and testing datasets.
2. Model Selection: Using a Logistic Regression algorithm to fit the model due to its effectiveness in binary classification problems.
3. Model Evaluation: Assessing the model's performance using metrics such as accuracy, precision, recall, and a confusion matrix.


## Results

* Logistic Regression Model:
   * Accuracy: 99%
* Healthy Loans (0):
   * Precision: 100%
   * Recall: 100%
* High-Risk Loans (1):
   * Precision: 86%
   * Recall: 91%

## Summary

The logistic regression model performed well, with an overall accuracy of 99%. It predicted healthy loans with perfect precision and recall and identified high-risk loans with strong precision (86%) and recall (91%).

Recommendation:
This model is suitable for identifying both healthy and high-risk loans. However, if the goal is to prioritize minimizing missed high-risk loans (false negatives), further optimization may be necessary to improve recall for high-risk loans. Overall, this model is recommended for deployment, with potential future enhancements to improve performance on high-risk loans.
