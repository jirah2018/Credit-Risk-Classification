# Credit-Risk-Classification

**Overview 

This module challenge  uses various techniques to train and evaluate a model based on loan risk. Using a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

**Instructions

**Split the Data into Training and Testing Sets

-Read the lending_data.csv data

-Create the labels set (y) from the “loan_status” column, and then 

-Create the features (X) DataFrame from the remaining columns.

-Split the data into training and testing datasets by using 

****Create a Logistic Regression Model with the Original Data

-Fit a logistic regression model by using the training data (X_train and y_train).

-Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model.

-Evaluate the model’s performance by doing the following question:

Question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Answer: The logistic regression model predicts healthy loan(0) at 100% however for high-risk loan(1) at 86%.
