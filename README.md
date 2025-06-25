#Credit Risk Analysis - Paisabazaar 🏦📊

This project involves analyzing a Credit Score Dataset from Paisabazaar to evaluate customer creditworthiness using machine learning and deep learning techniques. The dataset offers detailed demographic, financial, and credit history information of customers to help build predictive models for credit risk assessment.

📁 Dataset Overview
Dataset Name: Credit Score Dataset

Source: Paisabazaar

Rows: 96,696

Columns: 28

Content:

Customer Demographics

Financial Details

Credit History

Payment Patterns

🎯 Project Goal
To clean, analyze, and model customer credit data to identify key features that help predict credit risk. The final model will assist in credit scoring for financial decision-making.

🧪 Tech Stack
Languages: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

Modeling Techniques: Logistic Regression, Random Forest, XGBoost

Feature Selection: Mutual Information Score

Dimensionality Reduction: Principal Component Analysis (PCA)

Serialization: Pickle

🔍 Data Preprocessing
Removed null and duplicate values

Cleaned inconsistent formats

Used IQR method and capping to handle outliers

Converted categorical variables using encoding techniques

Standardized data using StandardScaler

📊 Exploratory Data Analysis (EDA)
Univariate Analysis: Distribution of credit scores, income, age, etc.

Bivariate Analysis: Credit Score vs Income, Age vs Loan History, etc.

Visualized trends using Countplots, Boxplots, Heatmaps

🧠 Feature Engineering
Created Age Groups

Derived Debt-to-Income ratios

Encoded categorical features

Applied Mutual Information Score for feature selection

Used PCA to reduce dimensionality for model training

🤖 Model Building
Model	Accuracy	Notes
Logistic Regression	✅	Baseline model
Random Forest	✅✅✅	Best performing model
XGBoost	✅✅	Competitive performance

Hyperparameter tuning done using GridSearchCV and RandomizedSearchCV

Random Forest achieved the highest score and was chosen for production

🛠️ Production
Final model serialized using Pickle

Ready for deployment as a credit risk assessment API or service

🚀 Future Enhancements
Deep learning-based credit scoring using neural networks

Real-time model inference using Flask or FastAPI

Integration with business intelligence dashboards (Power BI/Tableau)
