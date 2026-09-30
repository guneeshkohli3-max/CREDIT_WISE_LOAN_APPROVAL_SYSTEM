# CreditWise — Loan Approval Prediction System

CreditWise is a **machine learning-based loan approval prediction system** that analyzes applicant financial and personal information to predict whether a loan is likely to be approved.

### 🔍 Project Overview

The project focuses on building a complete ML classification pipeline, starting from **data preprocessing and exploratory data analysis (EDA)** to **feature engineering, model training, and evaluation**.

### ⚙️ Key Features

* Performed **data cleaning and missing-value handling**.
* Conducted **Exploratory Data Analysis (EDA)** to understand relationships between applicant attributes and loan approval.
* Analyzed important factors such as **Credit Score, Applicant Income, DTI Ratio, and Savings**.
* Applied **Label Encoding** and **One-Hot Encoding** for categorical features.
* Used **feature scaling** before model training.
* Performed **feature engineering** by creating squared features for `DTI_Ratio` and `Credit_Score`.
* Trained and compared multiple classification models:

  * Logistic Regression
  * K-Nearest Neighbors (KNN)
  * Gaussian Naive Bayes
* Evaluated models using **Accuracy, Precision, Recall, F1-Score, and Confusion Matrix**.
* Selected **Naive Bayes based on Precision** in the model evaluation performed in the notebook.

### 🛠️ Technologies Used

**Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn**

### 📊 Machine Learning Workflow

`Data Collection → Data Cleaning → EDA → Encoding → Feature Engineering → Train/Test Split → Feature Scaling → Model Training → Model Evaluation`

### 🎯 Objective

The primary objective of CreditWise is to demonstrate how machine learning can be applied to **automate and analyze loan approval classification**, while understanding the impact of applicant financial characteristics on the prediction process.
