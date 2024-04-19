Module 12 Report Template

Overview of the Analysis
As part of this Challenge, the analysis was mostly about making a machine learning model that can use financial data to guess the state of a loan. A set of data was looked at, which included loan amounts, interest rates, borrower income, the ratio of debt to income, the number of accounts, bad marks, and overall debt. The goal was to guess whether a loan had a low risk of default (-1) or a high risk of default (1).

It was the loan status marks, which show how risky the loan is, that were being studied. We took several steps to handle the data. First, we imported the dataset. Then, we split it into training and testing sets and features (X) and labels (y). After that, we used sklearn's LogisticRegression method to build and train the machine learning model.

Results
For the Logistic Regression model:

-Accuracy: The model had an accuracy score of 0.99.

-Precision: The precision score was 1.00 for classifying low-risk loans (0) and 0.85 for high-risk loans (1). 

-Recall: The recall score was 0.99 for low-risk loans (0) and 0.91 for high-risk loans (1).

Summary
The logistic regression model was very good at finding low-risk loans, with recall scores close to 1 and accuracy scores very high. It was a little less accurate with high-risk loans, though. This was probably because the sample was not balanced, with more low-risk loans than high-risk loans.

To sum up, this logistic regression model works pretty well for predicting low-risk loans. However, it might need more work or a completely different model to get better at predicting high-risk loans. This is very important because if a lender mistakes a loan for a low-risk one, it could cost them a lot of money. It depends on the lender's risk tolerance and the prediction goal ( reducing false negatives or false positives), more research could be done and other models or resampling methods could be used together to make better high-risk loan predictions.

