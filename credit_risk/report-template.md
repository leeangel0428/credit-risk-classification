# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to utilize machine learning techniques to forecast credit risk. The challenge was to categorize the loan data from the lending_data.csv into a "healthy loan" or a "high-risk loan" and build a predictive model that would be able to do that on its own based on the data provided.

Variables considered:
- "loan_size", the size of the loan
- "interest_rate", the interest rate
- "borrower_income", annual income of the person borrowing from the loan
- "debt_to_income", the debt to income ratio of person
- "num_of_accounts", number of accounts the person has open 
- "derogatory_marks", the negative marks
- "total_debt", total debt of person
- "loan status", whether the person was marked as "healthy" or "high risk"

Stages of Analysis: 
1) Split the Data into Training and Testing Sets

- Load data into a dataframe
- Separate the labels from the features
- Split the data using train_test_split

2) Create a Logistic Regression Model with the Original Data

- Fit a logistic regression model using the training data
- Save the predictions on the testing data labels by using the testing feature data and the fitted model
- Evaluate the model's performance by generating a confusion matric and printing the classification report

## Results

* Machine Learning Model 1:
  * ***Precision:*** "healthy"score was 1.00 which is excellent and "high risk" score was .85 which is good
  * ***Recall:*** "healthy" score was .99 and "high risk" was .91, both which are good
  * ***F1-score:*** "healthy" score was 1.00 which is excellent and "high risk" score was .88 which is good
  * ***Accuracy:*** The accuracy of the model was 99% which is nearly perfect.

## Summary
In conclusion, the model is good and definitely worth using but I don't know if I would recommend it without knowing the specifics of the business objectives. 