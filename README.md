# Financial Performance Dashboard

## Problem Statement
A financial services firm aims to automate financial reporting using Power BI. The objective is to track income, expenses, and profitability across departments and time periods. The dashboard provides insights into budget versus actual performance, cost centers, and key financial KPIs. It enables drill-down analysis to support strategic decision-making by leadership.

## Data Model

### Table: Transactions
- TransactionID
- Date
- Account
- Amount
- Type
- Department

### Table: Accounts
- Account
- AccountName
- Category

### Table: Departments
- Department
- DepartmentName

### Table: Dates
- Date
- Month
- Quarter
- Year

## Relationships
- Transactions.Account → Accounts.Account
- Transactions.Department → Departments.Department
- Transactions.Date → Dates.Date

## Analytical Questions
1. Total income and expenses by department
2. Net profit over time
3. Comparison of actuals vs budgeted values
4. Departments with highest costs
5. Monthly trend in income and expenses
6. Top 5 expense categories
7. Year-over-year profit growth
8. Cost-to-income ratio
9. Profitability by department
10. Variance between planned and actuals

## Tools Used
- Power BI
- Excel

## Files Included
- Power BI report (.pbix)
- Dataset files
- Presentation (PPT)
- DAX calculations document

## Conclusion
This dashboard helps stakeholders monitor financial performance, identify cost drivers, and evaluate profitability trends. It enables data-driven decision-making through interactive and drill-down capabilities.