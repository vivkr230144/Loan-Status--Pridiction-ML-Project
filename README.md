# Loan-Status--Pridiction-ML-Project
ML Project with the use of Python

Objective:
To build a predictive model that classifies whether a loan application will be approved or rejected based on applicant details like income, credit history, employment, loan amount, etc.

📊 Dataset Features:
Typical features include:

ApplicantIncome, CoapplicantIncome

LoanAmount, Loan_Amount_Term

Credit_History

Gender, Marital_Status, Education

Property_Area

Loan_Status (Target)

🔍 Approach:
Data Cleaning: Handled missing values and inconsistent entries.

Feature Engineering: Created new features such as income-to-loan ratio.

Encoding: Label encoded categorical variables.

Modeling: Trained classifiers like Logistic Regression, Random Forest, and XGBoost.

Evaluation: Used accuracy, confusion matrix, and AUC score to assess performance.

Explainability: Applied SHAP to understand key factors influencing loan approvals.

✅ Outcome:
Achieved ~85% accuracy with high recall for approved loans. Identified key approval drivers: credit history, loan amount, and applicant income.

💡 Business Value:
Helps banks and NBFCs make faster and data-driven loan decisions, reducing manual underwriting effort and default risk.
