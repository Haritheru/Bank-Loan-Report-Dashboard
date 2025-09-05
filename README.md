# Bank-Loan-Report-Dashboard
💰 Bank Loan Report Dashboard 

📌 Project Overview

This project is an SQL + Tableau-powered reporting solution designed to analyze bank loan performance.
It provides insights into loan applications, funded amounts, repayments, borrower demographics, and risk analysis through Good vs. Bad loan categorization.

✨ Dashboard Highlights

Loan Applications (Total, MTD, PMTD)

Funded Amount & Amount Received

Average Interest Rate & Debt-to-Income (DTI)

Loan Status Overview (Fully Paid, Current, Charged Off)

Good Loan vs. Bad Loan Analysis

Borrower Segmentation (State, Term, Purpose, Employment, Home Ownership)

📈 Key KPIs Tracked

Total Loan Applications

Funded & Collected Amounts

Avg Interest Rate & Avg DTI

Good Loan % vs. Bad Loan %

Borrower Demographics

🧮 SQL Calculations

Applications: COUNT(id) (Total, MTD, PMTD)

Funding & Repayments: SUM(loan_amount) and SUM(total_payment)

Rates: AVG(int_rate) * 100, AVG(dti) * 100

Loan Quality: Good vs. Bad loan % based on loan_status

Segmentation: Grouped by Month, State, Term, Purpose, Employment, Home Ownership

🔎 Key Insights

Good loans dominate funding and repayments.

Bad loans highlight higher-risk categories.

Loan activity shows monthly trends with clear MTD vs. PMTD differences.

Borrower segmentation reveals state- and purpose-based variations.

📷 Sample Dashboard Screenshots

📊 Dashboard 1 — Summary

High-level KPIs such as total loan applications, funded amount, amount received, average interest rate, average DTI, and Good vs. Bad loan percentage.

screenshot : <img width="1909" height="988" alt="Screenshot 2025-09-04 105038" src="https://github.com/user-attachments/assets/c77e099b-81bd-409d-9d02-1a58e80055c7" />


📊 Dashboard 2 — Overview

Aggregated portfolio performance across months, including loan status breakdown (Fully Paid, Current, Charged Off), repayment trends, and overall funding analysis.

Screenshot : <img width="1919" height="1014" alt="Screenshot 2025-09-04 105122" src="https://github.com/user-attachments/assets/bb2e795a-6e3c-49d4-a7a0-388f5b433659" />


📊 Dashboard 3 — Details

Tabular loan-level view showing borrower segmentation by state, purpose, loan term, employment length, and home ownership.

Screenshot : <img width="1919" height="1014" alt="Screenshot 2025-09-04 105152" src="https://github.com/user-attachments/assets/88e2a444-1d49-45c2-a633-4fdd1837c623" />


🚀 How to Use

Import the bank_loan_data into SQL.

Run queries from BANK LOAN REPORT QUERY DOCUMENT.docx.

Open the Tableau file Bank Loan Project.twb.

Explore dashboards (Summary, Overview, Details) using filters (Grade, State, Term, Purpose, etc.).
