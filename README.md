#BANK LOAN ANALYSIS — INTERNSHIP PROJECT

#SyntecxHub

FOLDER STRUCTURE

Bank_Loan_Analysis_Final/

│

├── README.txt                          ← You are here

│

├── dashboard/

│   └── index.html                      ← MAIN DASHBOARD (open this!)

│

├── dataset/

│   ├── bank_loan_data.csv              ← Raw dataset (38,576 rows, 31 cols)

│   └── bank_loan_data_enriched.csv    ← With extra columns (36 cols)

│

└── excel/

    └── Bank_Loan_Analysis.xlsx         ← Pre-analyzed Excel (8 sheets)

─────────────────────────────────────────
HOW TO USE
─────────────────────────────────────────

▶ DASHBOARD
  Open  dashboard/index.html  in any browser (Chrome, Edge, Firefox)
  - 7 KPI cards (Applications, Funded, Received, Rate, DTI, Good%, Bad%)
  - Monthly trend chart
  - Loan status donut chart
  - Grade-wise good vs bad bar chart
  - Top 10 loan purposes
  - State-wise analysis
  - Full status summary table
  - Filters: Year / Grade / Purpose / Good-Bad

▶ DATASET
  Use bank_loan_data_enriched.csv for any further analysis.
  Extra columns in enriched file:
    good_bad, month_year, year, month, quarter

▶ EXCEL
  8 pre-built sheets:
  1. Loan_Data         — sample records
  2. Summary_KPIs      — all KPI values
  3. Good_vs_Bad_Loans — comparison table
  4. Monthly_Trend     — month-wise data
  5. State_Analysis    — state-wise breakdown
  6. Loan_Purpose      — purpose-wise analysis
  7. Grade_Analysis    — grade A-G analysis
  8. PowerBI_DAX_Guide — DAX formulas reference

─────────────────────────────────────────
DATASET SUMMARY
─────────────────────────────────────────
  Total Records  : 38,576
  Columns        : 31 (raw) / 36 (enriched)
  Date Range     : Jan 2021 – Dec 2024
  Good Loans     : 86% (Fully Paid + Current)
  Bad Loans      : 14% (Charged Off + Default + Late)
  States         : 20 US States
  Loan Purposes  : 10 categories
  Grades         : A through G
─────────────────────────────────────────
