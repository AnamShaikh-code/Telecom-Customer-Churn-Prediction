# 📊 Telecom Customer Churn Prediction using Machine Learning

An end-to-end Machine Learning project that predicts telecom customer churn using Python and Scikit-learn while providing actionable business insights through an interactive Power BI dashboard.

---

# 🎯 Business Problem

Customer churn is one of the biggest challenges in the telecom industry because acquiring a new customer is significantly more expensive than retaining an existing one. The company needs to identify customers who are likely to leave so that proactive retention strategies can be implemented.

---

# 🎯 Business Objective

The objective of this project is to predict customers who are likely to churn and identify the major factors contributing to customer attrition. The insights generated from this project can help businesses improve customer retention, reduce revenue loss, and make data-driven decisions.

---

# 🎯 Project Objectives

- Predict customers who are likely to churn.
- Identify the major factors influencing churn.
- Compare multiple Machine Learning models.
- Select the best model based on business requirements.
- Build an interactive Power BI dashboard.
- Provide business recommendations to reduce churn.

---

# 📂 Dataset

- **Dataset:** Telco Customer Churn Dataset
- **Source:** IBM Sample Dataset
- **Records:** 7,043 Customers
- **Features:** 21
- **Target Variable:** Churn (Yes / No)

The dataset contains customer demographics, subscribed services, contract details, payment methods, tenure, monthly charges, and churn status.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Power BI
- Jupyter Notebook

---

# ⚙️ Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Preprocessing
6. Model Building
7. Model Evaluation
8. Power BI Dashboard Development
9. Business Insights & Recommendations

---

# 🤖 Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Balanced Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

# 📈 Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- AUC Score

### Selected Model

**Balanced Logistic Regression** was selected because it achieved a higher **Recall**, making it more effective in identifying customers who are likely to churn. In customer retention problems, missing a churning customer is more costly than incorrectly identifying a loyal customer.

---

# 📊 Power BI Dashboard

The dashboard provides interactive visualizations for business stakeholders.

### Executive KPIs

- Total Customers
- Churned Customers
- Active Customers
- Churn Rate

### Business Visualizations

- Churn by Contract Type
- Churn by Internet Service
- Churn by Payment Method
- Churn by Tech Support
- Average Monthly Charges by Churn
- Average Customer Tenure by Churn

---

# 💡 Key Business Insights

- Customers with Month-to-Month contracts have the highest churn.
- Fiber Optic customers show higher churn.
- Electronic Check users are more likely to churn.
- Customers without Tech Support have significantly higher churn.
- Higher Monthly Charges increase churn probability.
- Customers with shorter tenure are more likely to leave.

---

# ✅ Business Recommendations

- Encourage customers to switch to long-term contracts.
- Improve Fiber Optic service quality and pricing.
- Enhance payment convenience for customers.
- Promote Tech Support services.
- Improve onboarding and retention strategies for new customers.
- Provide personalized offers and loyalty rewards to high-risk customers.

---

# 📁 Project Structure

```
Telecom-Customer-Churn-Prediction/
│
├── data/
├── notebook/
├── dashboard/
├── images/
├── README.md
└── requirements.txt
```

---

# 🚀 Future Improvements

- Deploy the model using Streamlit.
- Perform Hyperparameter Tuning.
- Integrate real-time customer data.
- Automate retraining using MLOps.
- Build an AI-powered churn prediction assistant.

---

# 👨‍💻 Author

**Anam Shaikh**

---

# ⭐ If you found this project useful, consider giving it a Star.
