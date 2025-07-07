# Bank loan Data Analysis (Interactive Dashboard creation using Power BI)
## Project Objective
The primary objective of the Details Dashboard is to provide a comprehensive and user-friendly interface for accessing vital loan data. It will serve as a one-stop solution for users seeking detailed insights into our loan portfolio, borrower profiles, and loan performance.

## Dataset 
- <a href="https://github.com/Richa-goyal06/Bank-loan-Analysis/blob/main/financial_loan.csv">Dataset</a>

## Dashboard 1: Summary
Banks and financial institutions handle thousands of loan applications every month. However, without a structured analytics system, it becomes challenging to monitor lending performance, track repayments, and evaluate borrower health.
This project addresses that challenge by building a Power BI dashboard that tracks key KPIs like total loan applications, funded amounts, repayments, interest rates, and DTI ratios. It also includes a loan status grid view to differentiate good and bad loans, enabling faster, data-driven decisions in lending operations.

## Process :
- Data Extraction & Analysis (MySQL):
Raw loan data was queried directly from a structured MySQL database using SQL. This step involved filtering relevant fields, joining multiple tables, and deriving calculated metrics required for business analysis.

- Data Preprocessing & Cleaning (Power Pivot):
The extracted data was loaded into Power Pivot for transformation. Key operations included handling missing values, standardizing formats, creating calculated columns (e.g., DTI ratio), and preparing the data model for reporting.

- Dashboard Development (Power BI):
Cleaned data was visualized using Power BI. Interactive dashboards were built with filters, slicers, KPIs, and grid views, offering insights into loan performance, borrower risk, and month-over-month trends in lending operations.

## Project insight
- Most loans were approved for applicants with strong credit history and lower DTI ratios.

- Urban customers had higher average loan amounts but also slightly higher default rates.

- The majority of defaults occurred in loans with longer terms and lower co-applicant income.

- Month-over-month loan approvals increased, but funded amounts remained steady — indicating tighter screening.

- Average interest rates remained stable, but high-risk borrowers were charged slightly more.

## Final conclusion
The Bank Loan Analysis project successfully delivered a comprehensive Power BI dashboard that enables real-time monitoring of key loan performance indicators. By integrating SQL-based data extraction, Power Pivot for transformation, and dynamic visualizations in Power BI, the project provides valuable insights into loan approvals, repayments, borrower profiles, and risk factors. This solution empowers financial stakeholders to make data-driven decisions, optimize lending strategies, and improve portfolio health with greater clarity and precision
