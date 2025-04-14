# 📊 Healthcare Insurance Fraud Analysis Dashboard
## 🧾 Overview
This project focuses on identifying and analyzing patterns related to healthcare insurance fraud using Medicare claims data. Through interactive dashboards built in Power BI, it uncovers provider behaviors, beneficiary trends, and possible fraudulent activities based on reimbursement and hospitalization data.

## 📁 Dataset Description
The dataset used in this project includes:

Beneficiary data (gender, race, chronic conditions, etc.)

InPatient and OutPatient claims (claim amount, duration, diagnosis codes)

Provider data with fraud flags

Physician identifiers

Reimbursement and hospitalization information

## 🧰 Tools & Technologies Used
Power BI – for building all dashboards and visualizations

Power Query Editor – for data transformation, cleaning, and shaping

DAX (Data Analysis Expressions) – for creating calculated columns, measures, KPIs, and logic-based insights

## 🔧 Data Processing Steps
Cleaned and merged InPatient, OutPatient, Beneficiary, and Provider datasets

Handled nulls and outliers using Power Query

Created calculated columns and KPIs using DAX (e.g., total reimbursement, count of claims, fraud ratios)

Generated relationships between tables for accurate cross-filtering

Built visual components based on insights (e.g., bar charts, pie charts, scatter plots)

## 📈 Dashboard Sections (Power BI)
### 📍 Page 1: Demographics & Reimbursements
Count of beneficiaries by race and gender

Total InPatient vs. OutPatient reimbursements

State-wise distribution of beneficiaries

Gender-based beneficiary distribution

Number of inpatient and outpatient beneficiaries

Beneficiaries by race

### 📍 Page 2: Chronic Conditions & Age Patterns
% of beneficiaries with heart/renal failure

Age groups that hospitalize most frequently

Most common hospitalization durations

Insurance claims reimbursed based on duration

Age group that benefits most from Medicare

### 📍 Page 3: Fraudulent Providers & Retirement Patterns
Spike in hospitalization around retirement age (65)

% of providers marked as potentially fraudulent

Most common admit diagnosis codes

Reimbursements claimed by fraudulent providers (IP and OP)

### 📍 Page 4: Physician Analysis
Highest reimbursements claimed by fraud/non-fraud physicians

Number of physicians involved per claim

Patterns involving same attending and operating physicians

Duration vs. fraud status by age

Reimbursement by attending physician

### 📍 Page 5: Reimbursement Outliers
Highest IP/OP reimbursement claims

Provider-wise attending physician reimbursement

Alive vs. dead beneficiary percentages (inpatient)

### 📍 Page 6: Provider-level Breakdown
Highest IP/OP reimbursement claimed by each provider

% of providers that are flagged as fraud

% of claims involving same sets of physicians

## 💡 Key Insights
Most beneficiaries fall under race 1 and are slightly more male.

Older beneficiaries (65–80) drive the majority of hospitalizations and reimbursements.

Short hospital stays (1 day) are most common, but longer durations appear more in fraud cases.

Only ~9.35% providers are marked as potential fraud, yet they receive disproportionately higher reimbursements.

Claims involving multiple physicians are less likely to be fraudulent.

Certain providers and physicians stand out with unusually high reimbursement amounts.

## 🧠 Conclusion
The dashboard effectively highlights fraud-prone patterns, helping stakeholders identify suspicious claims and prioritize investigations. It serves as a visual decision-support tool for healthcare fraud analysts and policy makers.

## 🚀 Future Enhancements
Integration of AI/ML fraud prediction models

Drill-through reports for deep dives into specific providers or states

Real-time fraud detection using streaming data and alerts




