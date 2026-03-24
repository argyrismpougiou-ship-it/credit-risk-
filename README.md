# credit-risk-
Power BI Capstone Project focusing on Credit Risk Analysis &amp; Default Prediction. Features an interactive EDA dashboard and a dynamic DAX-powered Loan Approval Simulator based on a Logistic Regression model (R). Any advice or feedback is more than welcomed!
# 🏦 Credit Risk Analytics & Default Prediction Dashboard

## 📌 Project Overview
This repository contains my final capstone project for a Data Analytics seminar. The main objective of this project is to analyze credit risk, identify key drivers of loan defaults, and build a data-driven tool for loan approval processes. 

The analysis is based on the **"Credit Risk" dataset by Lao Tse**, thoroughly cleaned and transformed to extract actionable business insights.

## 🛠️ Tech Stack & Tools Used
* **Power BI:** Data visualization, interactive dashboards, and storytelling.
* **Power Query:** Data cleaning, transformation, and feature engineering.
* **DAX:** Advanced measures, What-If parameters, and custom mathematical calculations.
* **R (Programming Language):** Statistical modeling and Machine Learning (Logistic Regression).

## 🚀 Key Features of the Dashboard

### 1. Executive Overview & EDA
* **Portfolio Distribution:** Visualizes the total loan amount distributed by loan intent and credit grade.
* **Risk vs. Reward Analysis:** A dual-axis chart comparing estimated profitability against average interest rates across different loan grades, highlighting the "high-yield, high-risk" trap.

### 2. Risk Analysis & Key Influencers
* Deep dive into the demographic and financial factors driving default rates.
* Identifies **Debt-to-Income (DTI)** ratio and **Prior Default History** as the ultimate risk indicators.

### 3. The "Crown Jewel": Interactive Loan Approval Simulator
Unlike static dashboards, this project integrates a Machine Learning model directly into the BI environment. 
* A **Logistic Regression model** was trained in R (achieving a solid **AUC score of 0.78**).
* The model's coefficients were translated into a dynamic **DAX-powered Simulator**.
* **How it works:** Users can adjust What-If slicers (Requested Loan Amount, Annual Income, Interest Rate, and Age) to see the **Real-Time Probability of Default (PD)** for a hypothetical applicant.

## 💡 Top Business Insights
1. **DTI is King:** Applicants with a Debt-to-Income ratio exceeding 35-40% show a disproportionately high probability of default. Approvals should be strictly capped at this threshold.
2. **Age is Statistically Insignificant:** The predictive model mathematically proved (p-value: 0.991) that an applicant's age does not influence their likelihood to default, emphasizing the need to eliminate human bias in underwriting.
3. **The High-Interest Trap:** Lower-grade loans carry significantly higher interest rates but trigger an exponential increase in default rates. Stronger collateral policies are required for these segments.

## 🤝 Feedback & Contributions
As this is my Capstone Project for my Data Analyst journey, **any advice, code reviews, or suggestions for improvement would be more than welcomed!** Feel free to explore the `.pbix` file, open an issue, or connect with me to discuss data analytics.
