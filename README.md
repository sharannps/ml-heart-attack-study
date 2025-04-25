# Heart Attack Prediction with Machine Learning

A comprehensive machine learning project to predict the likelihood of heart attacks using clinical data. This study covers all key phases including data preprocessing, exploratory data analysis (EDA), model training, and evaluation. Multiple classifiers were compared, with the Random Forest model delivering the best performance.

## Project Overview

This project focuses on building predictive models to identify patients at risk of heart attacks. The dataset includes health indicators such as age, cholesterol, blood pressure, and more. Employed several machine learning algorithms and evaluated them to determine the most effective one.

## Features & Workflow

- **Data Preprocessing**: Handling missing values, scaling, handling outliers, encoding categorical variables, normalization.
- **Exploratory Data Analysis (EDA)**: Insightful visualizations to understand data distribution and relationships.
- **Modeling**:
  - Logistic Regression
  - Decision Tree
  - Support Vector Machine (SVM)
  - Random Forest
  - XGBoost
  - CatBoost
  - LightGBM
- **Model Evaluation**: Accuracy, AUC-ROC Curve, CV Score, Precision, Recall, F1-Score

## Best Model Performance

- **Model**: Random Forest Classifier  
- **Accuracy**: 90.32%  
- **AUC Score**: 93%

## Tools & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Comparison of Machine Learning Models' Performance Across Metrics

| Model             | Accuracy | CV Score | Precision | Recall  | F1-Score | AUC  |
|-------------------|----------|----------|-----------|---------|----------|------|
| Logistic Regression | 87.10%   | 76.67%   | 87.50%    | 95.45%  | 91.30%   | 88%  |
| Decision Tree      | 74.19%   | 83.33%   | 93.75%    | 68.18%  | 78.95%   | 79%  |
| Random Forest      | 90.32%   | 90.00%   | 95.24%    | 90.91%  | 93.02%   | 93%  |
| SVM                | 87.10%   | 83.33%   | 90.91%    | 90.91%  | 90.91%   | 89%  |
| XGBoost           | 77.42%   | 76.67%   | 85.71%    | 81.82%  | 83.72%   | 87%  |
| CatBoost           | 87.10%   | 90.00%   | 95.00%    | 86.36%  | 90.48%   | 91%  |
| LightGBM           | 77.42%   | 70.83%   | 89.47%    | 77.27%  | 82.93%   | 84%  |
