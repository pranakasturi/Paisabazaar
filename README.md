# 💳 Credit Risk Analysis - Paisabazaar

This project involves analyzing a **Credit Score Dataset** from Paisabazaar to evaluate customer creditworthiness using Machine Learning techniques. The dataset contains detailed demographic, financial, and credit history information of customers to help build predictive models for credit risk assessment.

---

## 📁 Dataset Overview

- **Dataset Name:** Credit Score Dataset  
- **Source:** Paisabazaar  
- **Rows:** 96,696  
- **Columns:** 28  
- **Content Includes:**
  - Customer Demographics
  - Financial Details
  - Credit History
  - Payment Patterns

---

## 🎯 Project Goal

To clean, analyze, and model customer credit data to identify key features that help predict credit risk. The final model will assist in credit scoring and financial decision-making.

---

## 🛠️ Tech Stack

- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost  
- **Modeling Techniques:** Logistic Regression, Random Forest, XGBoost  
- **Feature Selection:** Mutual Information (MI) Score  
- **Dimensionality Reduction:** Principal Component Analysis (PCA)  
- **Serialization:** Pickle

---

## 🧼 Data Preprocessing

- Removed null and duplicate values  
- Cleaned inconsistent formats  
- Handled outliers using **IQR method** and **capping**
- Encoded categorical features  
- Standardized data using `StandardScaler`

---

## 📊 Exploratory Data Analysis (EDA)

- **Univariate Analysis:** Distribution of credit scores, income, age, etc.  
- **Bivariate Analysis:** Credit Score vs Income, Age vs Loan History, etc.  
- **Visualizations:** Countplots, Boxplots, Correlation Heatmaps

---

## 🧠 Feature Engineering

- Created age groups  
- Derived debt-to-income ratio  
- Applied **MI Score** for feature selection  
- Used **PCA** to reduce dimensionality  

---

## 🤖 Model Building and Evaluation

| Model                | Description            | Accuracy |
|---------------------|------------------------|----------|
| Logistic Regression | Baseline Model         | ✅       |
| Random Forest       | Best Performing Model  | ✅✅✅    |
| XGBoost             | Tuned Ensemble Model   | ✅✅     |

- Hyperparameter tuning with `GridSearchCV` and `RandomizedSearchCV`
- **Random Forest** gave the best accuracy and was selected for production

---

## 🏁 Final Model Deployment

- Final model serialized using **Pickle**
- Can be integrated into APIs or dashboard applications

---
