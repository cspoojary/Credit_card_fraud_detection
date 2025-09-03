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
- <a href = "https://github.com/cspoojary/Credit_card_fraud_detection/blob/main/creditcard.ipynb">Full EDA, evaluation, and visualizations.</a>

## Project Workflow Checklist
* Importing Libraries & Loading Data
   * Imported Pandas, NumPy, Matplotlib/Seaborn, Scikit-Learn
   * Loaded creditcard.csv
* Data Exploration (EDA)
   * Checked dataset shape, columns, data types
   * Checked for missing values / duplicates
   * Descriptive statistics (mean, median, std, etc.)
* Class Imbalance Check
  * Count of fraud vs non-fraud transactions
  * Percentage of fraud cases
* Feature Exploration
  * Distribution of Amount and Time
  * Histograms / KDE plots of features
  * Correlation heatmap
* Data Preprocessing
  * Normalization/Scaling (Amount, Time)
  * Train-test split
* Modeling
  * Logistic Regression
  * Random Forest
* Handling Imbalance
  * applied class_weight=balanced
* Model Evaluation
  * Accuracy, Precision, Recall, F1-score
  * Confusion Matrix
  * ROC Curve & AUC
  * Precision-Recall curve
* Visualization & Insights
  * Fraud vs Non-fraud distribution plots
  * Feature importance bar chart
  * ROC & PR curves
