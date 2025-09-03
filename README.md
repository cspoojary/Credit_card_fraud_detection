# Credit_card_fraud_detection
### >Python >Machine Learning >Basic >Finance
A comprehensive credit-card transaction analysis project using machine learning to detect fraudulent activity, uncover patterns, and deliver actionable insights.

## Project Overview
This project analyzes anonymized credit card transaction data to detect unusual or outright fraudulent behavior. By leveraging statistical exploration and machine learning algorithms, it aims to accurately identify potential fraud while minimizing false alarms—crucial for financial institutions and fraud-prevention systems.

## The Dataset used
- <a href = "https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data/">Dataset</a>

## Tools & Technologies Used
 * Data Processing & Modeling: Python, Pandas, NumPy, Scikit-Learn, XGBoost, Imbalanced-learn
 * Visualization: Matplotlib, Seaborn, Plotly
 * Environment: Jupyter Notebook, GitHub

## Insights & Key Findings
 * Imbalanced Data: Fraudulent transactions constitute only a tiny fraction (≈ 0.17%) of the dataset, highlighting the need for specialized modeling techniques.
 * Amount & Time Patterns: Fraudulent behavior often occurs in specific ranges or time windows—visualizations reveal clustering patterns.
 *  Model Performance:
    * Random Forest achieved a ROC-AUC of ~0.97, with strong recall for fraud detection.
    * XGBoost matched or exceeded performance, with clearer feature importance ranking.
 * Important Predictors: Features like V14, V17, and V12 emerged as consistent top contributors.
 * Effectiveness of Imbalance Techniques: SMOTE and class-weight adjustments notably improved recall without sacrificing precision excessively.
 * Threshold Trade-offs: Precision-Recall curves helped identify an optimal balance point—prioritizing recall (catching fraud) while managing false positives.

## Project Files
- <a href = "https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data/">Full EDA, modeling pipeline, evaluation, and visualizations.</a>
