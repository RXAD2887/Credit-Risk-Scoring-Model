Credit-Risk-Scoring-Model
End-to-end credit scoring engine featuring a rigorous model audit for monotonicity and regulatory compliance.

Project Overview
Developed a high-performance credit scoring engine (AUC: 0.867) using XGBoost and Random Forest. This project bridges the gap between high-predictive machine learning power and the stringent transparency requirements of financial regulations (e.g., OSFI, IFRS 9).

The Core Problem: The ML "Black Box"
The primary challenge in regulated finance is ensuring Model Accountability. While complex models offer superior accuracy, they often lack:

Logical Consistency: Non-linear relationships that may violate economic intuition.

Auditability: Difficulty in providing clear "adverse action reasons" for credit denials.

Monotonicity: The regulatory requirement that increased risk factors (e.g., higher credit utilization) must lead to lower scores.

Key Audit Features
Regulatory Audit Layer: Implemented SHAP to deconstruct black-box predictions into transparent, feature-level contributions.

Monotonicity Validation: Leveraged Spearman Rank Correlation to audit feature logic, ensuring variables like Age and Utilization align with economic reality.

Strategic Risk Calibration: Performed threshold sensitivity analysis to align model outputs with corporate Risk Appetite, balancing opportunity costs against potential capital losses.

Technical Stack
Modeling: SQL, XGBoost, Random Forest, Scikit-learn.

Audit & Interpretation: SHAP, SciPy (Spearman), Matplotlib.
