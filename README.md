# credit-risk-classification

ANALYSIS OVERVIEW:

In this study, we utilize machine learning to predict loan health, particularly focusing on identifying high-risk loans in a pool using parameters like loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and ultimate loan status. Our analysis employs a logistic regression model, where the loan pool is divided into training and testing groups to teach and validate the model. We compare two models: one utilizing scaled data and the other incorporating oversampled data.

RESULTS:

Machine Learning Model 1:

Healthy Loan F1-score: 100%
Healthy Loan Precision: 99%
Healthy Loan Recall: 100%
High Risk Loan F1-score: 91%
High Risk Loan Precision: 98%
High Risk Loan Recall: 84%
Balanced Accuracy Score: 98.9%
Machine Learning Model 2:

Healthy Loan F1-score: 100%
Healthy Loan Precision: 99%
Healthy Loan Recall: 100%
High Risk Loan F1-score: 91%
High Risk Loan Precision: 99%
High Risk Loan Recall: 83%
Balanced Accuracy Score: 99.34%

SUMMARY:

 Model 1 and Model 2 exhibit notable accuracy, yielding balanced accuracy scores of 98.9% and 99.34%, respectively. It's important for users to recognize the significance of this finding. Those with a higher risk tolerance in lending would find these models valuable, as they effectively identify all healthy loans. Conversely, those pursuing a more conservative lending strategy might encounter a higher proportion of loans inclined towards "higher risk" than anticipated. In both scenarios, these models should be treated as supplementary tools to enhance informed decision-making processes.
