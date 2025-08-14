🏥 Healthcare Billing Analysis

📌 Project Overview

This project analyzes a healthcare dataset containing 55,500+ patient records to explore billing patterns based on gender, admission type, and other demographic factors.
The goal is to uncover key trends, disparities, and actionable insights that can help improve hospital cost management, operational efficiency, and fairness in billing.

📂 Dataset

Source: Hospital management dataset (synthetic for analysis purposes)

Size: 55,500+ rows × 15 columns

Key Columns:

patient_id – Unique identifier for each patient

gender – Male / Female

admission_type – Urgent / Emergency / Elective

billing_amount – Total charges incurred by the patient

department, diagnosis, length_of_stay, etc.

🎯 Problem Statement

Healthcare organizations often face challenges in understanding and optimizing billing patterns due to varying patient demographics and admission types.
This project addresses:

Are there differences in billing amounts based on gender or admission type?

Which admission categories have higher charges?

Are there outliers that significantly impact hospital revenue?

🛠️ Tools & Technologies

Python (Pandas, NumPy) – Data cleaning & transformation

Matplotlib / Seaborn – Data visualization

Jupyter Notebook – Exploratory Data Analysis (EDA)

📊 Key Visualizations

Box Plot: Billing amount distribution by gender & admission type

Bar Chart: Average billing by department

Histogram: Billing frequency distribution

Scatter Plot: Length of stay vs. billing amount

📌 Insights

Median billing amount is consistent across genders.

Slightly higher variability in billing for Emergency admissions.

No significant gender bias in billing amounts.

Presence of high-value outliers that could influence total revenue.

✅ Business Impact

Helps identify cost drivers in hospital billing.

Ensures fair billing practices across patient demographics.

Supports financial planning by predicting high-cost cases.

📈 Future Scope

Incorporate time-series analysis for seasonal billing patterns.

Integrate predictive modeling to forecast billing amounts.

Analyze the impact of insurance coverage on final bills.
