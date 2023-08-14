# Credit Card Fraud Detection

This is a Python script for credit card fraud detection using various machine learning models. The script reads a CSV file containing credit card transaction data, performs exploratory data analysis (EDA), preprocesses the data, trains different models, and evaluates their performance.

## Prerequisites

Before running the script, ensure you have the following libraries installed:

- pandas
- seaborn
- matplotlib
- scikit-learn
- imbalanced-learn (for class balancing)
- xgboost (for XGBoost model)

Description
The script performs the following steps:

Loads the credit card transaction data from 'cc.csv'.

Conducts initial data exploration and visualization using Pandas, Seaborn, and Matplotlib.

Preprocesses the data by removing unnecessary columns and standardizing features using StandardScaler.

Splits the data into training and testing sets using train_test_split.

Trains three different classifiers:

Logistic Regression
Random Forest Classifier
XGBoost Classifier
Evaluates the models' performance using classification reports and F1 scores.

Addresses class imbalance using the Synthetic Minority Over-sampling Technique (SMOTE).

Retrains the models with the balanced dataset and evaluates their performance again.

Results
The script outputs classification reports and F1 scores for each model's performance before and after addressing class imbalance.
