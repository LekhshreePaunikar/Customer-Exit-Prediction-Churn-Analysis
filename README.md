# 🏦 Customer Exit Prediction (Churn Analysis)
## Kaggle Competition Leaderboard: Top 11% (103rd / 656 teams)

## Introduction

This task was to build an ML model that predicts whether a bank customer will exit or stay. I cleaned data, explored patterns, engineered features, trained several models, tuned them, and finally submitted the best one on Kaggle. The focus was accuracy, business relevance, and reliable predictions.

## Problem Statement

To predict customer churn using demographic, account, financial, and behavioral attributes, allowing financial institutions to identify customers at high risk of leaving.

## Goal

To develop a robust churn classification model that generalizes well on unseen data and maximizes business-relevant performance, especially recall/precision balance for actionable customer retention strategies.

## ML Pipeline

- Cleaned the dataset: handled missing values, outliers, and inconsistencies
- Performed EDA: heatmaps, distribution plots, churn trends
- Encoded categorical variables and scaled numeric features
- Trained multiple ML models (Logistic Regression, RF, XGBoost, CatBoost, LightGBM)
- Hyperparameter tuning with GridSearchCV
- Selected LightGBM as final model and generated Kaggle submission

## Conclusion

After refining the full ML pipeline and benchmarking multiple models, LightGBM delivered the strongest and most stable performance. The final submission achieved an F1 Score of 0.6501, placing me in the Top 11% (103rd out of 656 teams) on Kaggle. This result validates the effectiveness of the pipeline and confirms that the engineered features, model tuning, and selection process successfully captured real churn-driving patterns.
