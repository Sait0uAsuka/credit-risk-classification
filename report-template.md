# Module 12 Report Template

# Credit Risk Analysis Report
## Overview of the Analysis
The purpose of this analysis was to develop and evaluate machine learning models to predict the risk level of loans based on various financial features. The goal was to classify loans into two categories: 0 for healthy loans (low-risk) and 1 for high-risk loans. This prediction allows a financial institution to better manage and assess the risk of loans they are issuing.

The dataset used contains multiple financial variables such as loan amount, interest rate, and borrower information. The objective was to train a model to predict whether a loan would be high-risk or healthy based on these features.

The stages of the machine learning process involved:
 
1. Data Preprocessing: Addressing missing values, normalizing the data, and encoding categorical variables.
2. Model Selection: Logistic Regression was chosen for this binary classification task.
3. Model Training and Evaluation: The model was trained and evaluated using key metrics: accuracy, precision, and recall.

# Results
The results from the Logistic Regression model were as follows:

- Logistic Regression:
    - Accuracy: 99%
    - Precision (Healthy loan - Class 0): 1.00
    - Recall (Healthy loan - Class 0): 0.99
    - Precision (High-risk loan - Class 1): 0.85
    - Recall (High-risk loan - Class 1): 0.95
    - F1-Score (Healthy loan - Class 0): 1.00
    - F1-Score (High-risk loan - Class 1): 0.89

# Summary
The Logistic Regression model performed well overall, with a high accuracy of 99%. The model demonstrated excellent performance in identifying healthy loans (Class 0), with perfect precision and high recall. For high-risk loans (Class 1), while the recall was high at 95%, the precision was lower (85%), meaning some healthy loans were misclassified as high-risk.

Considering the overall accuracy and the high recall for high-risk loans, the model is suitable for predicting loan risk. However, if it’s critical to minimize false positives for high-risk loans, further tuning or exploring other algorithms might be beneficial.

**Recommendation**: The company is recommended to use the Logistic Regression model because it balances accuracy and recall well. However, to improve precision in predicting high-risk loans, further adjustments or improvements to the model could be considered.
