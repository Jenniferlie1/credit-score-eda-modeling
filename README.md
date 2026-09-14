# Credit Score EDA & Modeling — Random Forest vs XGBoost
Exploratory data analysis and predictive modeling on a 50,000-row credit score dataset, comparing tuned Random Forest and XGBoost models.
## Overview
- Dataset: 50,000 rows × 28 columns
- Dropped identifier/sensitive columns (ID, Customer_ID, Name, SSN)
- Fixed inconsistent data types, handled invalid values, outliers, and missing values
- Encoding and scaling applied before modeling
## Workflow
1. EDA — insights and irregularities in the raw dataset, addressed appropriately
2. Data Cleaning — inconsistent/invalid value handling, outlier treatment, missing value imputation, encoding, scaling
3. Modeling — Random Forest and XGBoost, each tuned across 3+ hyperparameters over a search space of 3+ values, evaluated on a held-out test set
4. Evaluation — model comparison across 3+ metrics with conclusions
5. Feature Importance — key drivers of credit score from the best-performing model (Outstanding_Debt and Interest_Rate as top predictors)
## Tech Stack
Python Pandas NumPy scikit-learn XGBoost Matplotlib
## Data
Credis_Score_Dataset_B.csv
