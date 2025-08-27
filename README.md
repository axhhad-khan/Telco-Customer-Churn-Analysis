# 📊 Telco Customer Churn Prediction

Predicting customer churn using **Machine Learning** to help telecom companies proactively retain high-value customers.

## 🚀 Project Overview

This project builds a **predictive model** to identify customers who are likely to leave (churn).
By leveraging **data preprocessing, feature engineering, and classification algorithms**, the pipeline generates actionable insights for telecom businesses.

Key Highlights:

* Data cleaning & preprocessing of Telco Customer Churn dataset.
* Feature encoding, scaling, and class imbalance handling.
* Training multiple ML models (Logistic Regression, Random Forest, XGBoost, etc.).
* Model evaluation with accuracy, precision, recall, F1-score, and ROC-AUC.
* Final churn prediction pipeline ready for deployment.


## ⚙️ Tech Stack

* **Python 3.x**
* **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost
* **Environment**: Jupyter Notebook / VS Code

## 📊 Dataset

Dataset: **Telco Customer Churn**

* Contains customer demographics, account information, and service usage.
* Target column: `Churn` (Yes/No).

👉 [Download Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)

## 🧑‍💻 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/telco_customer_churn.git
   cd telco_customer_churn
   ```

2. Create virtual environment & install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the script:

   ```bash
   python telco_customer_churn.py
   ```

4. Or open Jupyter Notebook:

   ```bash
   jupyter notebook telco_customer_churn.ipynb
   ```

---

## 📈 Results

• **Best Model Achieved**: XGBoost with highest ROC-AUC.
• Feature importance analysis highlights contract type, tenure, and monthly charges as key churn drivers.

🚀 Future Improvements

• Deploy model using **Flask / FastAPI**.
• Build interactive dashboards with **Streamlit / Power BI**.
• Integrate with real-time customer data pipelines.
