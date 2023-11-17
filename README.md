# -credit_risk_classification
Challenge 20

The analysis is to predict credit risk for peer-to-peer lending through the use of machine learning.  Build a model that id's the creditworthiness of borrowers. The lending data provided included loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, total debt and loan status.
The goal was to predict if a loan is healthy or high-risk.  Models created are Logistic Regression Model using original data and resampled data.

Both models perform very strongly when predicting healthy loans. With the second model, using the resampled data, accuracy and recall greatly improved to nearly perfect scores. Precision remains an issue with both models, staying at 87%.
The recommendation is to use Model 2.
Since both models correctly predict healthy loans, more important to have a model that correctly classifies more high-risk loans. The risk associated with mis-classifying a healthy loan as high-risk is lower than the risk of not classifying a high-risk loan as such.

This project was a bit easier than Tableau but with exercises reusing the same code with slight modifications it was easier to catch on.  There was a lot of info in this section so it was difficult to keep up.  Yes, machine learning is way worse.  So, for a while, I will enjoy coding.
