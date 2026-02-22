# Credit-Risk-Scoring-Model
End-to-end credit scoring engine using XGBoost/Random Forest, featuring a rigorous model audit for monotonicity and regulatory compliance
# Credit Risk Scoring & Regulatory Model Audit

## Project Overview
This project develops a high-performance credit scoring engine (AUC: 0.862) using XGBoost and Random Forest, with a specific focus on **Model Interpretability** and **Regulatory Compliance**.

## Key Features
* **Advanced Feature Engineering**: Handled skewed financial distributions and missingness indicators for "no-income" profiles.
* **Model Audit**: Implemented **SHAP (SHapley Additive exPlanations)** to deconstruct the "black-box" model.
* **Logical Consistency**: Validated variable monotonicity using **Spearman Rank Correlation** to ensure Age and Utilization align with economic intuition.

