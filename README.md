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

## Project 2: Sales Performance Analysis 

## Problem Statement

A multinational retail company wants to analyze its sales performance across different regions, product categories, and time periods.

The objective is to identify top-performing products, understand seasonal trends, detect underperforming regions, and track key performance indicators. The dashboard is designed to help sales managers make data-driven decisions and improve inventory and marketing strategies.

---

## Key Objectives

* Analyze revenue across regions and product categories
* Track monthly, quarterly, and yearly trends
* Identify top and low-performing products
* Understand customer purchasing behavior
* Evaluate profitability and growth metrics

---

## Dataset Description

### Sales Table

* SaleID
* ProductID
* CustomerID
* Date
* Quantity
* Revenue

### Products Table

* ProductID
* ProductName
* Category
* Price

### Customers Table

* CustomerID
* Name
* Region

### Dates Table

* Date
* Month
* Quarter
* Year

---

## Data Model Relationships

* Sales.ProductID → Products.ProductID
* Sales.CustomerID → Customers.CustomerID
* Sales.Date → Dates.Date

These relationships support effective data modeling in Power BI.

---

## Key Performance Indicators

* Total Revenue
* Profit Margin
* Sales Growth
* Average Revenue per Customer

---

## Business Questions Answered

1. What is the total revenue by region and category?
2. Which products have the highest and lowest sales?
3. What are the monthly and quarterly sales trends?
4. What is the average revenue per customer?
5. Which regions have the highest profit margins?
6. How does sales performance vary by product category?
7. What is the year-over-year sales growth?
8. Which customers are the top buyers?
9. What is the sales distribution across months?
10. How do discounts affect revenue?

---

## Tools and Technologies Used

* Power BI
* DAX (Data Analysis Expressions)
* Data Modeling
* Excel / CSV datasets

---

## Dashboard Features

* Interactive filters (Region, Category, Time)
* Drill-down capabilities
* KPI indicators for quick insights
* Trend analysis charts
* Customer segmentation visuals

---

## Insights and Outcomes

* Identified high-performing regions and products
* Observed seasonal sales trends
* Detected underperforming categories
* Enabled better decision-making for sales strategy

---

## Conclusion

This project demonstrates how Power BI can be used to convert raw sales data into meaningful insights, helping businesses improve performance and make informed decisions.




