# hero_fincorp_analysis
# Hero FinCorp: A Comprehensive Data-Driven Analysis 📊

## Project Overview
This project provides a comprehensive data-driven analysis of Hero FinCorp's loan portfolio, customer behavior, and branch performance. The goal of this analysis is to optimize the loan approval process, reduce defaults, and improve branch efficiency through actionable, data-backed recommendations.

## Datasets Used
* *Customer Demographics:* Customer profiles, income, and credit scores.
* *Loan Data:* Active and closed loans, interest rates, and EMI details.
* *Loan Applications:* Application status, processing fees, and rejection reasons.
* *Transactions:* Repayment records and penalty tracking.
* *Default Records:* Details of defaulted loans and recovery amounts.
* *Branch Information:* Geographic and performance metrics for branches.

## Key Objectives
1. *Default Risk Analysis:* Identify customer/loan attributes contributing to defaults.
2. *Branch Efficiency:* Evaluate disbursement volume, processing times, and recovery rates.
3. *Customer Insights:* Segment customers to pinpoint high-value vs. high-risk profiles.
4. *Profitability:* Understand drivers of interest income and financial performance.

## Key Findings & Insights
* *Default Rates:* The portfolio exhibits a 9.49% overall default rate. Traditional linear variables (like credit score alone) show weak standalone correlation, indicating a need for multi-variable non-linear risk modeling.
* *Branch Performance:* The Kara-Bahl branch leads in disbursement volume, while the Sani-Kale branch is the most efficient in processing time.
* *Recovery Effectiveness:* Average recovery sits at ~40.1%. Legal action only marginally improves this to 40.7%, suggesting high litigation costs may not be justified for all cases.
* *Rejection Bottlenecks:* "Low Credit Score" and "Incomplete Documents" are the top reasons for loan rejections.

## Repository Structure
* /data: Contains the raw CSV datasets.
* /images: Visualizations generated during the exploratory data analysis.
* Hero_FinCorp_Analysis.ipynb: The primary Jupyter Notebook containing data cleaning, EDA, statistical analysis, and visual generation.
* Insights_Report.pdf: The finalized business report and actionable recommendations.

## Tools Used
* *Python* (Pandas, NumPy, Matplotlib, Seaborn)
* *Jupyter Notebook*
