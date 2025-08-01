# Customer-Churn-Prediction-using-machine-learning
## 🛠️ Project Overview

The telecommunications industry faces significant losses due to customer churn. By leveraging data science, companies can proactively address churn, increase retention, and boost profitability.
This project delivers an end-to-end customer churn prediction pipeline, using real-world customer records to build, evaluate, and interpret predictive models—all in Python using a Jupyter/Colab notebook.

---

## 📦 Dataset Overview

Size: 7,043 customer records

Fields: 21 columns, including demographic, services, account, and billing information

Key Columns:

gender, SeniorCitizen, Partner, Dependents (Demographics)

tenure, Contract, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges (Account/Billing)

PhoneService, MultipleLines, InternetService, OnlineSecurity, ..., StreamingMovies (Subscribed Services)

Target: Churn (Yes/No)

---

## 🚦 Problem Statement

Goal:
To accurately predict whether a customer will churn (i.e., discontinue service) using their demographic, account, and service usage data—and provide business insights into why churn occurs.

---

## 🧑💻 Solution Pipeline

1. Data Exploration & Preprocessing
Data import, initial inspection, and summary statistics

Missing value treatment & conversion of data types

Encoding categorical variables (Label Encoding)

Scaling continuous features (for logistic regression)

2. Feature Engineering & Analysis
Exploratory Data Analysis with Seaborn and Matplotlib

Visualizations: churn rates, tenure, charges, and service affinity

Correlation analysis and feature importance evaluation

3. Model Development
Logistic Regression: Strong baseline, interpretable model

Decision Tree Classifier: Captures nonlinear patterns, offers interpretable rules

Full training-validation-test split to ensure realistic evaluation

4. Model Tuning & Evaluation
Hyperparameter optimization using GridSearchCV (Decision Tree)

Model assessment using:

Confusion Matrix

Classification Report (precision, recall, F1 score)

AUC/ROC Curve and Score

5. Interpretation & Business Insights
Visualization of top drivers of churn

Recommendations for business action based on feature importance

---

## 📊 Key Results

Well-calibrated, explainable models that predict customer churn with strong recall and ROC performance

Business-driven insights into the factors most influencing churn

Models ready for deployment in retention analytics, dashboards, or automated interventions

---

## 🛠️ Tech Stack

Tool	Purpose
Python	Primary programming language
Pandas	Data manipulation
NumPy	Numerical computing
Seaborn	Exploratory data visualization
Matplotlib	Statistical plotting
Scikit-learn	ML modeling, tuning, validation
Google Colab	Cloud-based notebook environment


