# 📉 Customer Churn Prediction System

This project is part of my internship with **Future Interns**. The goal was to build a **Customer Churn Prediction System** using real-world data to identify which customers are most likely to stop using a service. Churn prediction is crucial in industries like telecom, SaaS, and banking where customer retention is more cost-effective than acquisition.

---

## 📊 Objective

To develop a machine learning model that predicts customer churn and provide actionable business insights based on the results.

---

## 🔧 Tools & Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- SMOTE (from imbalanced-learn)
- Google Colab

---

## 🧠 Key Steps

### 1. **Data Exploration & Cleaning**
- Loaded and explored the dataset (`Churn_Model.csv`)
- Checked for missing values and handled categorical variables
- Dropped irrelevant features (`Surname`, `CustomerID`) for better performance

### 2. **Feature Engineering**
- One-hot encoded categorical columns
- Identified and selected key features:
  - `Contract`, `PaymentMethod`, `InternetService`, `Tenure`, etc.

### 3. **Handling Imbalanced Data**
- Used **SMOTE** to oversample the minority class (churned customers)

### 4. **Model Training**
Tested and compared the following classification models:
- Logistic Regression
- Random Forest
- XGBoost (with hyperparameter tuning)

### 5. **Evaluation Metrics**
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## ✅ Results

- **Best Model**: XGBoost (fine-tuned with SMOTE)
- **Accuracy**: ~87%
- Business-ready PDF report generated with key churn drivers and recommendations

---
---
## 🧠 Lessons Learned

- How to analyze customer behavior using machine learning
- Handling imbalanced data using SMOTE
- Importance of feature selection in predictive modeling
- How to present results in a business-friendly format
---
## 📎 Resources

- 🔗 [Kaggle Dataset - Bank Customer Churn Modeling](https://www.kaggle.com/datasets/barelydedicated/bank-customer-churn-modeling)

---


## 📁 Repository Structure

📄 Churn_Modelling.csv
📄 dt_final.csv
├── 📓 ML_Task2.ipynb
├── 📄 README.md
├── 📄 Churn Prediction Report.pdf
└── 📁 visualizations
📫 [LinkedIn – Sinam Ametewee](https://www.linkedin.com/in/sinam-ametewee-267a6b265/)  
