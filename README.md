# Bank Loan Analysis Project

## Overview
This project involves analyzing bank loan data to assess risk, make informed lending decisions, manage loan portfolios, detect fraud, ensure regulatory compliance, gain customer insights, and analyze profitability. The analysis was performed using SQL for data extraction and transformation, and Power BI for data visualization and reporting.

## Key Performance Indicators (KPIs)
- **Total Loan Applications**
- **Total Funded Amount**
- **Total Amount Received**
- **Average Interest Rate**
- **Average Debt-to-Income Ratio (DTI)**
- **Good Loan vs. Bad Loan KPIs**
  - Good Loan Application Percentage
  - Good Loan Applications
  - Good Loan Funded Amount
  - Good Loan Total Received Amount
  - Bad Loan Application Percentage
  - Bad Loan Applications
  - Bad Loan Funded Amount
  - Bad Loan Total Received Amount
 
## Created Dashboards
 ![Loan summary](Loan summery Dashboard-1.png)

  

## Functionality Performed

### SQL
- **Creating Database and Tables**: Structured storage for loan data.
- **Data Retrieval and Manipulation**: `SELECT`, `DATENAME`, `DATEPART`, `CAST`, `DECIMAL`, `MONTH`, `HOUR`, `QUARTER`, `DAY`, `GROUP BY`, `ORDER BY`, `LIMIT`, `COUNT`, `DISTINCT`, `CTE`, `PARTITION`.

### Power BI
- **Data Connection and Cleaning**: Connecting to SQL Server, cleaning and preparing data.
- **Data Modeling and Processing**: Structuring data, performing transformations, and calculations.
- **Visualizations and KPI Tracking**: Creating charts, card visuals, and formatting them for insights.
- **Advanced Calculations with DAX**: Using DAX functions for complex calculations and time intelligence.

## Charts and Visualizations
- **Monthly Trends by Issue Date (Line Chart)**
- **Regional Analysis by State (Filled Map)**
- **Loan Term Analysis (Donut Chart)**
- **Employee Length Analysis (Bar Chart)**
- **Loan Purpose Breakdown (Bar Chart)**
- **Home Ownership Analysis (Tree Map)**

## Usage
To run this project, you will need:
1. SQL Server to host and manage the loan database.
2. Power BI for connecting to the SQL Server, performing data cleaning, modeling, processing, and creating visualizations.

## Getting Started
1. **SQL Setup**:
   - Create the database and tables using the provided SQL scripts.
   - Insert loan data into the tables.

2. **Power BI Setup**:
   - Connect Power BI to the SQL Server.
   - Load data and perform necessary cleaning and transformations.
   - Create data models and define relationships.
   - Use DAX functions to create calculated columns and measures.
   - Design and format visualizations for KPIs and insights.

## Key Insights
- Comprehensive overview of loan applications and funding trends.
- Detailed analysis of loan performance by various dimensions such as region, loan term, employment length, loan purpose, and home ownership.
- Effective tracking of good vs. bad loans to manage risk and profitability.

## Conclusion
This project provides a robust framework for analyzing bank loan data, offering valuable insights for decision-making, risk management, and strategic planning. The combination of SQL and Power BI enables efficient data processing and intuitive visualizations to support banking operations.
