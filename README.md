# Credit Risk Analysis

## Overview of the Analysis

The aim of this research is to develop a prediction model for assessing loan applicants' credit risk. Being a much more prevalent classification difficulty than high-risk loans, credit risk is inherently uneven. In order to address this issue, we used machine learning techniques, specifically logistic regression, to forecast the probability that a loan will fail. We trained our model using both original and oversampled data, using a dataset of past lending activity in an effort to increase the algorithm's accuracy in identifying high-risk loans.

## Results

The performance of the logistic regression model trained on the original and resampled datasets is summarized as follows:

- **Original Data:**
  - Accuracy Score: 0.95
  - Precision Score for Healthy Loans (0): 1.00
  - Precision Score for High-Risk Loans (1): 0.85
  - Recall Score for Healthy Loans (0): 0.99
  - Recall Score for High-Risk Loans (1): 0.91
  
- **Resampled Data:**
  - Accuracy Score: 0.994
  - Precision Score for Healthy Loans (0): 1.00
  - Precision Score for High-Risk Loans (1): 0.84
  - Recall Score for Healthy Loans (0): 0.99
  - Recall Score for High-Risk Loans (1): 0.99

## Summary

When trained on the original dataset, the logistic regression model showed remarkable predictive powers, especially in detecting healthy loans. However, after training on the oversampled dataset, its capacity to recognize high-risk loans significantly increased. The higher recall score for high-risk loans, which indicates that the model is very successful in identifying loans that may default, is proof of this.

The capacity to identify high-risk loans is critical due to the significant risks associated with credit risk assessment. In addition to maintaining high precision for healthy loans, the model trained on the oversampled data exhibits a notable improvement in recognizing high-risk loans, which may aid the business in reducing financial risk.

For the purpose of determining credit risk, I therefore advise using the logistic regression model that was trained on the oversampled data. Because of its excellent performance in identifying high-risk loans, the company may be able to save a substantial amount of money by issuing fewer poor loans and being better equipped to control its exposure to risk.
