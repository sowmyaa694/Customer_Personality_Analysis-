# Customer_Personality_Analysis-
Customer Personality Analysis
A machine learning project that analyzes customer personality traits to predict marketing campaign responses, helping businesses target the right customers.
📌 Project Overview
This project uses the Marketing Campaign dataset to:

Understand customer buying behavior through EDA
Engineer meaningful features (Age, TotalSpent, TotalChildren)
Handle class imbalance using SMOTE
Predict whether a customer will respond to a campaign using XGBoost

🛠️ Tech Stack

Python, Pandas, NumPy
Matplotlib, Seaborn (EDA & Visualization)
Scikit-learn (Preprocessing, Models, Evaluation)
XGBoost
Imbalanced-learn (SMOTE)

📊 ML Pipeline

Data Cleaning — Handle missing values, fix data types, remove outliers (IQR method)
Feature Engineering — Age, TotalSpent, TotalChildren
EDA — Distributions, correlation heatmap, class imbalance check
Preprocessing — Label Encoding, Standard Scaling, SMOTE
Modeling — Logistic Regression, Decision Tree, XGBoost
Tuning — RandomizedSearchCV on XGBoost

🎯 Models Compared
ModelDescriptionLogistic RegressionBaseline modelDecision TreeInterpretable modelXGBoost (Tuned)Best performing model
📁 Dataset

marketing_campaign.csv — IBM marketing campaign dataset (tab-separated)
Features include: Income, Spending on products, Number of purchases, Campaign responses

🏫 Project Info

College: Sridevi Women's Engineering College (Autonomous)
Department: CSE (Data Science)
Year: III B.Tech, Semester II, A.Y 2025-26
Guide: Mrs. Smitha Panigrahy
