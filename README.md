# employee-attrition-prediction
Employee attrition analysis and prediction using machine learning
# Employee Attrition Prediction Using Machine Learning

## Project Overview
This project analyses employee data from the IBM HR Analytics Employee Attrition dataset to explore factors associated with employee turnover and build machine learning classification models.

## Objectives
- Explore employee characteristics and attrition patterns.
- Engineer meaningful features, including Relative Salary Position (RSP).
- Compare classification models and evaluate their performance.
- Investigate how class imbalance and classification thresholds affect the detection of employees who leave.

## Dataset
The dataset contains 1,470 employee records and 35 original attributes. Four uninformative or identifier columns were removed during preprocessing.

Dataset source: [Add the original dataset source link here]

## Tools and Technologies
Python, Pandas, NumPy, Scikit-learn, Imbalanced-learn, Matplotlib and Seaborn.

## Methods
- Exploratory data analysis and statistical testing
- Feature engineering and Principal Component Analysis (PCA)
- Stratified five-fold cross-validation and hyperparameter tuning
- Class imbalance handling using class weighting and SMOTENC
- Comparison of Logistic Regression, Random Forest and boosting models

## Results
The Gradient Boosting model achieved the following results on the held-out test set:

- Recall: 70.21%
- F1-score: 56.41%
- Employees who left correctly identified: 33 out of 47

These results highlight the trade-off between identifying potential leavers and generating false positives.

## Disclaimer
This is an academic machine learning project. Predictions indicate potential attrition risk and should not be treated as definitive judgements about individual employees.
