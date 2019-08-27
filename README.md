# Credit-Card-Fraud-Analytics

The dataset was sourced from Kaggle: https://www.kaggle.com/mlg-ulb/creditcardfraud

It contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

In the JupyterNotebook, I first conducted EDA to compare the distribution of different variables such as amount, No_of_transactions etc. between normal and fraud class and select those that perform obvious difference as input for modeling. Then I built Logistic Regression model with L1 regularization after GridSearchCV optimization and also use SMOTE oversampling method ( as it is an unbalanced dataset) to fit random forest model with recall 0.81 after optimization
