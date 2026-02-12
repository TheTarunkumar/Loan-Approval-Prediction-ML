# Loan Approval Prediction using Random Forest

## 📌 Project Overview
This project predicts whether a loan application will be Approved or Rejected using Machine Learning.

The model is trained on financial and applicant-related features such as income, loan amount, CIBIL score, assets, and employment status.

---

## 📊 Dataset Information
The dataset contains 4,269 records and 13 features including:

- Number of dependents
- Education
- Self-employed status
- Annual income
- Loan amount
- Loan term
- CIBIL score
- Residential, commercial, luxury & bank asset values
- Loan status (Target Variable)

---

## ⚙️ Machine Learning Workflow

1. Data Cleaning
2. Handling column formatting
3. Encoding categorical variables
4. Train-Test Split (80-20)
5. Model Training using Random Forest Classifier
6. Model Evaluation using:
   - Accuracy Score
   - Confusion Matrix
   - Feature Importance

---

## 🎯 Model Performance

- Accuracy: **97.7%**
- Strong performance on unseen test data
- Very low misclassification

Confusion Matrix Results:
- True Approved: 529
- True Rejected: 306
- False Predictions: Minimal

---

## 🔍 Key Insight

Feature Importance Analysis shows:

- CIBIL Score is the most important factor in loan approval decisions.
- Loan term and loan amount also influence decisions.
- Education and employment status have lower impact compared to financial metrics.

---

## 💡 Business Impact

This model can help financial institutions:

- Automate loan approval decisions
- Reduce manual processing time
- Improve consistency in decision-making
- Minimize risky approvals

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Project Structure

Loan-Approval-Prediction-ML/
│
├── Loan_Approval_Prediction.ipynb
├── loan_approval_dataset.csv
└── README.md

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Model deployment using Streamlit
- Adding feature scaling comparison
