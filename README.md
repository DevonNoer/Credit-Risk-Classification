# Credit-Risk-Classification
In this challenge the goal was to create a machine-learning model the can evaluate borrowers and identify their creditworthiness. 
## Overview of the Analysis
1. Using the lending_data.csv I created a dataframe with the columns, loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt, and loan_status. Loan_status is 0 (healthy loan) and 1 (high risk loan).
2. Next I stored values of loan_status into y and all the features except loan_status into X.
3. Then I used the tain_test_split module from sklearn to split the data into the variables with a random state of 1.
4.  Next I created a logicistic regression model with X_train and y_train and a random state of 1, and then predicted it with X_test.
5.  Using the prediction I created a confusion matrix and a classification report.
## Results
Machine Learning Model 0 (healthy loan):
- Accuracy: 1.00
- Precision: 1.00
- Recall: 0.99
Machine learning Model 1 (high risk loan):
- Accuracy: 0.88
- Precision: 0.85
- Recall: 0.91
## Summary
For the healthy loan (0) the f1 score is 1.00 so it predicts it extremely well, for the high-risk loan (1) the f1 score is a .88 which means it still predicts it at a good percentage. The overall f1 score for accuracy is .99 which means this model predicts this very well. The goal of the model was to determine the high risk loans and because of this the model performs well and could be used to help determine if someone is high risk or not.
## Overview of files
Inside the main folder there is a folder for Code and Resources
- Code: In here is the code for the project
- Resources: In here is the csv of the data for the project
