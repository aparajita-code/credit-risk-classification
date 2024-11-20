# credit-risk-classification

***Credit Risk Analysis Report*** :


***Overview**

The purpose of this analysis is to evaluate the performance of a Logistic Regression model in predicting credit risk. The model aims to classify loans as either healthy (low-risk) or high-risk. By accurately identifying the credit risk associated with loan applications, the company can make informed decisions to mitigate potential losses and ensure the stability of its lending portfolio.

Model Performance Metrics
The following metrics were used to assess the performance of the Logistic Regression model:

Accuracy: 0.99

Precision:

Class 0 (Healthy Loan): 1.00

Class 1 (High-Risk Loan): 0.87

Recall:

Class 0 (Healthy Loan): 1.00

Class 1 (High-Risk Loan): 0.95

F1-Score:

Class 0 (Healthy Loan): 1.00

Class 1 (High-Risk Loan): 0.91

Confusion Matrix
[[18673    86]
 [   32   593]]

***Summary and Recommendations:***

The results from the Logistic Regression model indicate a very high overall accuracy of 99%, showcasing the model's effectiveness in classifying credit risks. Here’s a summary of key findings and recommendations based on the evaluation metrics:

Class 0 (Healthy Loan) Performance:

Precision and Recall: Both precision and recall for healthy loans are perfect at 1.00, indicating that the model has no false positives or false negatives for this class. The model successfully identifies all healthy loans without misclassification.

Class 1 (High-Risk Loan) Performance:

Precision: The precision for high-risk loans is 0.87, suggesting that 87% of the loans predicted as high-risk are indeed high-risk. There are some false positives, but they are relatively few.

Recall: The recall for high-risk loans is 0.95, meaning that 95% of actual high-risk loans are correctly identified, with a small number of high-risk loans being missed (false negatives).

***Justification for Model Recommendation***

Given the exceptional accuracy and high performance metrics, I recommend the implementation of this Logistic Regression model for the company's credit risk assessment. The model's ability to accurately predict both healthy and high-risk loans will allow the company to:

Mitigate Risks: Effectively identify high-risk loans and take proactive measures to mitigate potential defaults.

Improve Decision Making: Support the decision-making process by providing reliable predictions, ensuring that resources are allocated efficiently.

Maintain Portfolio Stability: Ensure the stability of the lending portfolio by minimizing the occurrence of defaults and maintaining a healthy balance of low-risk loans.