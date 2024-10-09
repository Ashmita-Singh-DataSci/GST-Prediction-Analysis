# Intelligent Financial Prediction System

## Project Overview
This project aims to develop a robust machine learning model to address various financial functions, such as investment strategies, risk management, and market trend analysis. By leveraging advanced techniques and comprehensive preprocessing, the model provides accurate and interpretable predictions.

## Objectives
- Develop a predictive model for financial data.
- Address data quality issues, handle missing values, and outliers.
- Implement feature selection, feature engineering, and dimensionality reduction.
- Balance class distributions using SMOTE.
- Evaluate model performance using comprehensive metrics.

## Data Preprocessing
- **Categorical and Numerical Differentiation**: Classified columns based on missing values, range, and entropy.
- **Imputation**: Median imputation for numerical columns, mode imputation for categorical columns.
- **Scaling**: Standardized numerical features.
- **Outlier Detection**: Applied Z-Score method.

## Feature Engineering
- **SelectKBest**: Identified significant features.
- **Interaction Terms**: Created using polynomial features for numerical columns.

## Model Training
- **Balancing**: Addressed class imbalance with SMOTE.
- **PCA**: Reduced dimensionality while retaining 98% variance.
- **Stacking Classifier**: Combined XGBoost and SGDClassifier with Logistic Regression as meta-model.

## Evaluation
- **Metrics**: Used classification reports, AUC-ROC, and SHAP values for PCA components.
- **Transparency**: Inversed PCA to understand real feature impacts.

## Future Scope
- Integrate real-time data for dynamic predictions.
- Enhance feature engineering with deep learning techniques.
- Explore hybrid models and explainable AI.
- Ensure scalability with cloud integration and edge computing.
- Improve user interface with interactive dashboards and APIs.

## Instructions
- See `instructions.md` for setup and usage.
- Ensure all dependencies in `requirements.txt` are installed.

## Plagiarism Declaration
"I hereby declare that this project report is my own work and has been written by me in my own words. Any information derived from the published or unpublished work of others has been acknowledged in the text and a list of references is provided. I have not copied in part or in whole or otherwise plagiarized the work of other students and/or persons. The primary sources of assistance were Microsoft Copilot, a referenced research paper, and a PDF report, which provided guidance and insights without copying any proprietary content."

## Citations
**References**
1. Microsoft Copilot, personal communication, 2024.
2. GST 7 Year Report 
https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&ua
ct=8&ved=2ahUKEwirqcWg4oGJAxXdafUHHSqUCbIQFnoECBMQAQ&url=https
%3A%2F%2Fa2z-bucket.s3.ap-south1.amazonaws.com%2FGST7YearsReport.pdf&usg=AOvVaw2rSZgqpyZ0SlBUmgv3
TjHB&opi=89978449

