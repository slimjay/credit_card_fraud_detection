# credit_card_fraud_detection

## Project Overview

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

## Data Source

This dataset was obtained from [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'.

## Data Used

- Data : Credit Card data with over 284807 rows and 13 columns from September 2013 by European cardholders.
- Data Cleaning and Analysis: Python, Jupyter Notebook
- Dependencies: Pandas, Numpy, sklearn.model_selection(train_test_split), sklearn.linear_model(LogisticRegression), sklearn.metrics(accuracy_score)

## Summary of Findings
1. No null value in the dataset
2. The dataset is highly unbalanced. Normal transaction was more than Fraudulent
3. I took a sample of Fraudulent transactions (492) and concatenated with Legit transactions to balance it
4. Prepared the data
5. Split the data into Training and Test data
6. Trained the model using Logistic Regression(Ideal for binary classification problem)
7. Trained data had accuracy score of 0.9326556543837357, while Test had accuracy of 0.9187817258883249
