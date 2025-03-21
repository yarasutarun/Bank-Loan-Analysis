# Bank-Loan-Analysis
This project provides an in-depth analysis of bank loan data using MySQL. It includes SQL queries to generate key performance indicators (KPIs) such as total loan applications, funded amounts, interest rates, debt-to-income ratios, and loan performance categorization. The dataset can be filtered and analysed based on different parameters like loan status, term, purpose, home ownership, and state.
# Features
## Loan Applications Summary
o	Total loan applications (MTD, PMTD, and overall count)  
o	Funded amounts (MTD, PMTD, and total)  
o	Amount received (MTD, PMTD, and total)  
## Interest Rate & Debt-to-Income Analysis
o	Average interest rates (MTD, PMTD, overall)  
o	Average Debt-to-Income (DTI) ratios (MTD, PMTD, overall)  
## Loan Performance Metrics
o	Good Loan Percentage (Fully Paid & Current Loans)  
o	Bad Loan Percentage (Charged Off Loans)  
o	Loan distribution by state, term, employee length, and purpose  
## Dynamic Filtering for Deeper Insights
o	Queries support filtering by grade, state, term, purpose, etc.
# Project Overview:
The Bank Loan Analysis with MySQL project focuses on analysing banking loan data to derive key insights and performance metrics. It includes SQL queries that help evaluate loan applications, funded amounts, interest rates, debt-to-income ratios, and loan statuses.
Using structured queries, this project enables users to:
### Assess Loan Performance – Identify good and bad loans based on repayment status.
### Monitor Key Metrics – Track total funded amounts, amounts received, and interest rates.
### Analyse Trends – Break down loan applications by month, state, term, employment length, and purpose.
### Enable Data-Driven Decisions – Filter and compare loan data dynamically using SQL queries.
# Key Features:
## Loan Applications Summary
•	Total loan applications (Overall, Month-to-Date (MTD), Previous Month-to-Date (PMTD))  
•	Funded amounts and amounts received (MTD, PMTD, Overall)  
## Loan Performance Metrics
•	Good Loan Percentage → Fully Paid & Current Loans  
•	Bad Loan Percentage → Charged-Off Loans  
•	Loan distribution by state, term, employee length, and purpose  
## Interest Rate & Debt-to-Income (DTI) Analysis
•	Average interest rates (MTD, PMTD, Overall)  
•	Average DTI ratios (MTD, PMTD, Overall)  
## Loan Status Analysis
•	Breakdown of loan count, total amount funded, amount received, interest rates, and DTI per loan status
## Loan Trend Analysis
•	Monthly loan applications and funding trends  
•	Loan insights categorized by state, purpose, and home ownership  
## Dynamic Query Filters for Insights
•	Analyse data using filters such as Grade, State, Term, Purpose, etc.  
•	Modify queries to get custom insights based on specific loan criteria  
# Objective:
The primary objective of this project is to analyse and evaluate banking loan data using MySQL to gain meaningful insights into loan performance, trends, and risk factors. 
This project helps in evaluating lending risks, improving loan approval strategies, and understanding customer borrowing behaviour, making it valuable for financial institutions and data analysts.
## Tools Used:
### MYSQL
For querying and analysing the sales data stored in the database. Power BI (Optional): For visualizing and presenting the insights and trends.
Insights and Analysis:
This MySQL-based analysis uncovers valuable insights into loan performance, borrower trends, and financial risk assessment. Here are the key findings from the dataset:
________________________________________
## 1 Loan Application Trends
Total Loan Applications: Provides a count of all loan applications processed.  
Month-to-Date (MTD) & Previous Month-to-Date (PMTD) Trends: Helps track month-over-month growth or decline in loan applications.  
Loan Distribution by Month: Identifies peak months for loan applications, showing seasonality trends.  
### Insight:
Loan applications tend to spike in certain months, possibly due to seasonal borrowing needs or financial trends.
________________________________________
## 2 Loan Performance Evaluation
Good Loans (Fully Paid & Current): Measures the percentage of loans that are either successfully repaid or currently active.  
Bad Loans (Charged Off): Identifies the proportion of loans that defaulted, highlighting risk areas.  
Loan Status Breakdown: Compares total funded amounts, collected payments, and interest rates for different loan statuses.  
### Insight:
A high percentage of charged-off loans indicates increased lending risk and the need for stricter approval policies.
________________________________________
## 3 Financial Metrics - Funded Amount vs. Received Amount
Total Funded Amount: The total value of loans issued to borrowers.  
Total Amount Received: The total payments collected from borrowers (principal + interest).  
Comparison by Loan Status: Shows repayment efficiency across different categories (Fully Paid, Charged Off, Current).  
### Insight:
Discrepancies between funded vs. received amounts may indicate potential loan recovery challenges or high default rates.
________________________________________
## 4 Interest Rate & Debt-to-Income (DTI) Analysis
Average Interest Rate (Overall, MTD, PMTD): Measures lending rates over time.  
Debt-to-Income Ratio (DTI): Assesses borrowers' financial health and repayment capability.  
### Insight:
Higher DTI ratios and interest rates correlate with increased loan default risk, requiring stricter borrower evaluation.
________________________________________
## 5 Loan Distribution by Key Factors
State-wise Distribution: Identifies high and low loan activity regions.  
Term-wise Distribution: Compares loan performance for different loan durations (e.g., 36 vs. 60 months).  
Purpose-wise Distribution: Reveals the most common reasons for loan applications (e.g., Debt Consolidation, Home Improvement).  
Home Ownership Impact: Examines whether homeownership status influences loan repayment patterns.  
### Insight:
Loans taken for debt consolidation often have higher approval rates, but also a higher risk of default. Borrowers with homeownership status tend to have a lower default rate compared to renters.
________________________________________
## 6 Data-Driven Risk Assessment & Decision-Making
Filtering Capabilities: Enables in-depth analysis using various filters like loan grade, state, term, and purpose.  
Predicting Loan Defaults: Helps financial institutions identify high-risk borrowers and adjust approval criteria accordingly.  
### Insight:
Banks and financial institutions can use these data-driven insights to refine their lending policies, reduce risks, and maximize profits.  
# Final Takeaway:
This analysis helps lenders, financial analysts, and policymakers understand loan dynamics, reduce default risks, and improve lending strategies using data-driven decision-making.

