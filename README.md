
# Credit Risk Assessment using Machine Learning

## 📘 Project Overview

This project explores machine learning techniques to assess credit risk using customer financial and demographic data. The primary goal is to build predictive models that help financial institutions determine the likelihood of a borrower defaulting on a loan.

**Author**: Joy Nna Christopher  
**Project Type**: Credit Risk Analysis  
**Tools Used**: Python (Jupyter Notebook)

---

## 🎯 Objective

The aim of this project is to:

- Analyze and preprocess financial data for modeling
- Develop classification models to predict loan default risk
- Evaluate models using industry-standard metrics
- Offer a reproducible and scalable machine learning workflow

---

## 🧠 Technologies Used

- **Python** (Jupyter Notebook)
- Libraries:
  - `pandas`, `numpy` (data handling)
  - `matplotlib`, `seaborn` (data visualization)
  - `scikit-learn` (ML models, preprocessing)
  - `imbalanced-learn` (for resampling)

---

## 📊 Dataset

The dataset includes variables such as:
- Credit history
- Loan amount
- Employment status
- Income level
- Default status (target variable)

---

## 🧪 Methodology

- **Data Preprocessing**:
  - Handling missing values
  - Feature encoding
  - Feature scaling
  - Balancing dataset with SMOTE

- **Machine Learning Models Used**:
  - Logistic Regression
  - Random Forest
  - Decision Tree
  - Gradient Boosting
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)

- **Model Evaluation Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC

---

## ✅ Results Summary

Random Forest and Gradient Boosting models showed superior performance in predicting high-risk customers, especially when class imbalance was addressed using SMOTE.

---

## 🔍 Insights

- High credit score and stable employment correlate with lower default risk
- Loan amount and income ratio play a key role in risk assessment
- Model performance improves significantly with balanced datasets

---

## 📁 Project Structure

```
.
├── credit_risk_assessment.ipynb   # Main analysis notebook
├── README.md                      # Project documentation
└── requirements.txt               # Python dependencies (optional)
```

---

## 📜 License

For educational and research purposes only. Dataset usage is subject to original source terms.

---

## 🙌 Acknowledgements

Thanks to open data contributors and the Python open-source community.
