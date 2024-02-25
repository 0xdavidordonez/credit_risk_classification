# Module 12 Report 

## Overview of the Analysis

In this credit risk analysis, the purpose is to evaluate and compare the performance of two machine learning models in predicting credit risk. The analysis focuses on financial information related to creditworthiness, aiming to predict whether a credit applicant is likely to be a high risk (`1`) or low risk (`0`) based on certain features.

### Data Overview
The dataset contains information on credit applicants, and the goal is to predict credit risk. The target variable is binary, with `0` representing low risk and `1` representing high risk. The dataset was imbalanced, with significantly fewer high-risk cases.

### Machine Learning Process
The analysis involved the following steps:
* Data preprocessing, including separating data into labels and features and splitting the data into training and testing datasets.
* Utilization of Logistic Regression model for credit risk prediction.
* Addressing class imbalance using Random Oversampling method.

## Results


* **Machine Learning Model 1:**
  * Balanced Accuracy Score: 0.967989851522121
  * Precision and Recall Scores:
    - Class 0: Precision - 1.00, Recall - 0.99
    - Class 1: Precision - 0.84, Recall - 0.94

* **Machine Learning Model 2:**
  * Balanced Accuracy Score: 0.9946686570347071
  * Precision and Recall Scores:
    - Class 0: Precision - 0.99, Recall - 0.99
    - Class 1: Precision - 0.99, Recall - 0.99

## Summary

Summary of the results from the machine learning models:

* The second model, trained on oversampled data, outperformed the first model in terms of balanced accuracy and precision/recall for both classes.
* The balanced accuracy score for the oversampled model is higher (0.9947) compared to the original model (0.9680).
* Precision and recall for high-risk cases (Class 1) significantly improved with oversampling.

### Recommendation

Based on the analysis, it is recommended to use the model trained on the oversampled data for credit risk prediction. This model demonstrates superior performance in accurately identifying high-risk credit applicants, which is crucial for mitigating potential financial risks.

Consideration for stakeholders:
* The nature of credit risk problems often emphasizes the need to accurately predict high-risk cases. The oversampled model excels in this aspect.
* The improved precision and recall for high-risk cases indicate a more reliable identification of applicants with potential credit issues.

## Conclusion

In conclusion, the oversampled Logistic Regression model is recommended for credit risk prediction due to its higher performance in accurately identifying high-risk cases. The analysis provides valuable insights for stakeholders involved in credit risk assessment.

