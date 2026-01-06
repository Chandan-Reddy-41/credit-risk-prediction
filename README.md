# 🏦 Credit Risk Prediction Pipeline

## 📊 Project Overview
This project develops a machine learning solution to predict the risk of loan default. By leveraging a synthetic financial dataset, I built an end-to-end pipeline that processes raw data, handles outliers, engineers high-impact features, and evaluates multiple classification algorithms.

## 🏆 Key Results
* **Champion Model:** XGBoost
* **Accuracy:** 95.8%
* **AUC-ROC Score:** 0.98
* **Feature Engineering:** Significantly improved predictive power by creating domain-specific ratios like `loan_to_income` and `credit_per_loan`.

## 🛠️ Tech Stack & Methods
* **Python:** Pandas, NumPy, Scikit-Learn, XGBoost.
* **Preprocessing:** Outlier handling (IQR), Median Imputation, and One-Hot Encoding.
* **Feature Selection:** Recursive Feature Elimination (RFE) to identify the top 18 most impactful predictors.
* **Model Comparison:** Benchmarked Logistic Regression, Decision Trees, SVM, Random Forest, and XGBoost using Stratified K-Fold Cross-Validation.



## 📈 Key Insights
* **Credit Score & Income:** These remained the strongest predictors of default across all models.
* **Non-Linearity:** Ensemble methods (Random Forest and XGBoost) outperformed linear models, suggesting complex relationships between borrower variables.
* **Efficiency:** Using RFE allowed for a 15% reduction in features while maintaining over 95% accuracy.

## 📂 Repository Structure
* `credit-risk-prediction.ipynb`: Main Jupyter Notebook with full analysis and modeling.
* `Dataset_CDS/`: Directory containing the synthetic training and testing data.
* `.gitignore`: Configuration to keep the repository clean from temporary files.
