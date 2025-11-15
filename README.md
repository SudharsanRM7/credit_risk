# Interpretable Machine Learning for Credit Risk

## Project Overview
This project builds a binary classification model to predict loan default using XGBoost. It emphasizes model interpretability using SHAP values to meet regulatory standards.

## Approach
- Feature engineering: handled missing values, encoded categorical variables
- Model: XGBoost with tuned hyperparameters
- Evaluation: optimized for AUC and Recall
- Interpretability: SHAP summary and force plots

## Findings
- Top 5 features: loan_amount, credit_score, income, debt_to_income_ratio, employment_length
- SHAP revealed strong nonlinear interactions
- Local explanations showed why some defaults were misclassified

## Deliverables
- 📊 ROC curve and SHAP plots
- 🔍 Force plots for two case studies
- 📝 Strategic summary for credit policy

## Submission
All code and outputs are in this repo. See `submission_summary.md` for key metrics and insights.
