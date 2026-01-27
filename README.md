# 📊 Lending Club Loan Data – Exploratory Data Analysis (EDA)
### 📌 Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on the Lending Club loan dataset to understand borrower behavior, loan characteristics, and factors influencing loan default and risk.

The primary goal of this analysis is to:

Clean and prepare a real-world, highly noisy financial dataset

Identify key variables impacting loan performance

Generate actionable insights useful for credit risk assessment and business decision-making

This repository is designed to be educational for beginners and professionally structured for recruiters and analysts.

### 🧠 Business Context

Lending Club is a peer-to-peer lending platform that connects borrowers with investors.
Incorrect credit risk assessment can lead to:

High default rates

Investor losses

Poor portfolio performance

Through EDA, this project aims to uncover patterns in borrower profiles and loan attributes that can help:

Predict risky loans

Improve approval strategies

Support downstream machine learning models

🗂 Dataset Description

Source: Lending Club historical loan data

Type: Structured financial dataset

Rows: Large-scale real-world data

Challenges:

High percentage of missing values

Redundant and irrelevant features

Mixed data types (numerical & categorical)

🔍 Project Workflow
1️⃣ Data Understanding

Initial inspection of dataset shape and structure

Identification of numerical and categorical features

Understanding business meaning of critical variables

2️⃣ Data Cleaning

This stage focuses on making the data analysis-ready:

Removal of completely empty and near-empty columns

Dropping columns with major missing percentages

Eliminating irrelevant or non-informative features

Ensuring data consistency and usability

💡 Emphasis was placed on why a column was removed — not just removing blindly.

3️⃣ Exploratory Data Analysis (EDA)

Univariate analysis to study individual feature distributions

Bivariate analysis to identify relationships between:

Loan amount

Interest rate

Annual income

Debt-to-income ratio (DTI)

Identification of trends and risk indicators

Visual insights using statistical plots

4️⃣ Key Insights & Observations

Certain financial attributes show strong association with loan risk

Data cleaning significantly improves interpretability

EDA reveals patterns essential for credit risk modeling

5️⃣ Recommendations

Based on the analysis:

Focus on high-impact financial variables for modeling

Remove redundant features early to avoid noise

Use EDA insights to guide feature selection in ML pipelines

🛠 Tools & Technologies Used

Python

Pandas – data manipulation

NumPy – numerical operations

Matplotlib & Seaborn – data visualization

Google Colab / Jupyter Notebook

📁 Repository Structure
├── lending_club_prj2_own.ipynb   # Complete EDA notebook
├── README.md                    # Project documentation

🎯 Who Should Use This Project?

Aspiring Data Analysts learning real-world EDA

Data Science students building portfolios

Recruiters evaluating analytical thinking

Professionals revisiting EDA best practices

🚀 Next Steps (Future Scope)

Feature engineering based on EDA findings

Building predictive models (Logistic Regression, Tree-based models)

Model evaluation using business-centric metrics

Automating data preprocessing pipeline

👤 Author

Vehan Mehul Somaiya
Data Analysis & Machine Learning Enthusiast

⭐ If you find this project useful, consider giving it a star!
