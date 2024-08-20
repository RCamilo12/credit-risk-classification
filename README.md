# credit-risk-classification

In this exercise we look to evaluate a model based on loan risk. This model is supposed to identify the creditworthiness of borrowers and the exercise evaluates its performance by creating a Logistic Regression Model and its respective Classification Report.  

## Results

- Accuracy Score
    The model has an overall accuracy of 0.99 or 99% which means it correctly predicts the loans in almost all the dataset.
- Precision Score
    For the Healthy Loans the model has a 1.00 score which means is extremly accurate in predicting healthy loans. In the HighRisk case we found a 0.87 score which means 87% of the loans were actually highrisk, this opens a bridge on the precision of the model as there might be some false positives where some loans that are healthy were incorrectly classified as high-risk in which the borrower might need some extra steps to get the loan or in worst case scenario just get denied.
- Recall Score
    Once again, a 1.00 score on the Healthy loans, which means it identifies them correctly. On the HighRisk loans we found a 0.89 which opens again a gap for false negatives in which high-risk lonas are flagged as healthy. This could result in a financial issue if the borrower does not pay the loan. 

## Summary

- The model predicts healthy loans extremly well
- It performs well with high-risk loans, but it has precision and recall issues if compared to the healthy loans. This could be due a biased dataset with more information for healthy loans than high risk loans, more data could be collected to make the model's precision and recall get better.