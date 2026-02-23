# Credit Risk Scoring & Regulatory Audit
> **End-to-end scoring engine focusing on ML interpretability and OSFI/IFRS 9 compliance.**

---

## 🎯 Project Impact
Developed a robust credit engine reaching **AUC: 0.867**. This project solves the **"ML Black Box"** problem by bridging high-performance modeling with strict financial regulatory transparency.

## ⚖️ The Core Problem
In regulated banking, accuracy isn't enough. We must ensure:
* **Logical Consistency**: No counter-intuitive relationships in the model.
* **Auditability**: Providing clear "adverse action reasons" for credit denials.
* **Monotonicity**: Ensuring risk factors (e.g., Utilization) align with economic reality.

## 🛠️ Key Audit Solutions
* **Regulatory Transparency**: Implemented **SHAP** to deconstruct black-box predictions.
* **Logic Validation**: Leveraged **Spearman Rank Correlation** to audit feature monotonicity.
* **Risk Calibration**: Performed threshold sensitivity analysis to balance **Opportunity Cost** vs. **Capital Risk**.

## 💻 Tech Stack
* **Modeling**: `SQL`, `XGBoost`, `Random Forest`, `Scikit-learn`
* **Audit**: `SHAP`, `SciPy (Spearman)`, `Matplotlib`
