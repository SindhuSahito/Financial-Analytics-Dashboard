# Financial Analytics Dashboard Using Python, SQL, and Power BI

## Project Report

### Prepared By

**Name:** *Sindhu Sahito*
**Role:** Aspiring Data Analyst
**Tools Used:** Python, Pandas, SQL (SQLite), Power BI, Excel

---

# 1. Introduction

Financial analytics helps organizations monitor revenue, expenses, profitability, and operational performance to support informed business decisions. Modern businesses generate large amounts of transactional data, making it essential to transform raw information into meaningful insights.

This project presents a complete Financial Analytics Dashboard developed using Python, SQL, and Power BI. The dashboard analyzes supermarket sales data to evaluate financial performance, identify sales trends, compare expenses, measure profitability, and provide interactive business insights.

The project demonstrates the complete data analytics workflow including data cleaning, exploratory data analysis (EDA), SQL-based analysis, and interactive dashboard development.

---

# 2. Project Objectives

The primary objectives of this project are:

* Clean and preprocess raw financial transaction data.
* Analyze revenue, expenses, and profit.
* Monitor monthly financial performance.
* Identify high-performing product categories.
* Compare profitability across different cities.
* Create an interactive Power BI dashboard for business decision-making.
* Present insights using visualizations and KPI metrics.

---

# 3. Dataset Description

### Dataset Name

Supermarket Sales Dataset

### Source

Kaggle

### Dataset Summary

The dataset contains transaction records from supermarket branches located in Myanmar.

### Dataset Information

* Total Records: 1000
* Total Columns: 17
* Time Period: January 2019 – March 2019

### Main Attributes

* Transaction ID
* Branch
* City
* Customer Type
* Gender
* Product Line
* Unit Price
* Quantity
* Revenue
* Expense
* Profit
* Tax
* Date
* Time
* Payment Method
* Customer Rating

---

# 4. Data Cleaning Process

The dataset was cleaned using Python and the Pandas library.

The following preprocessing steps were performed:

* Loaded the dataset into Pandas.
* Renamed columns for consistency.
* Removed duplicate records.
* Converted numerical columns into proper numeric format.
* Converted the Date column into DateTime format.
* Checked for missing values.
* Verified data types.
* Saved the cleaned dataset for further analysis.

The cleaned dataset was then used throughout SQL analysis, Python visualizations, and Power BI dashboard development.

---

# 5. Exploratory Data Analysis (EDA)

Python libraries including Matplotlib and Seaborn were used to perform exploratory data analysis.

The following visualizations were created:

### Correlation Heatmap

Analyzed relationships between Revenue, Expense, Profit, Quantity, Tax, and Rating.

### Monthly Revenue Trend

Visualized monthly revenue with a rolling average to identify business trends.

### Expense Boxplot

Detected unusual expense values and potential outliers.

### Revenue Distribution

Displayed the distribution of revenue across transactions using histograms.

---

# 6. SQL Analysis

SQLite was used to perform business-oriented SQL queries.

Key analyses included:

* Monthly Revenue
* Expense Analysis
* Profit by City
* Revenue by Product Line
* Payment Method Analysis
* Profit Margin Calculation

SQL queries were used to validate calculations and prepare summarized information for reporting.

---

# 7. Power BI Dashboard

An interactive Financial Analytics Dashboard was developed using Microsoft Power BI.

### Dashboard KPIs

* Total Revenue
* Total Expense
* Total Profit
* Profit Margin

### Dashboard Visualizations

* Monthly Revenue Trend
* Revenue by Product Line
* Expense by Product Line
* Profit by City
* Revenue by Payment Method

### Interactive Features

* City Filter
* Branch Filter
* Product Line Filter
* Payment Method Filter
* Customer Type Filter
* Date Filter

The dashboard enables users to explore financial performance dynamically through slicers and interactive charts.

---

# 8. Technologies Used

| Technology         | Purpose                  |
| ------------------ | ------------------------ |
| Python             | Data Cleaning & Analysis |
| Pandas             | Data Manipulation        |
| Matplotlib         | Data Visualization       |
| Seaborn            | Statistical Analysis     |
| SQL (SQLite)       | Data Querying            |
| Microsoft Power BI | Dashboard Development    |
| Microsoft Excel    | Initial Data Inspection  |
| Jupyter Notebook   | Python Development       |

---

# 9. Key Business Insights

Based on the analysis, the following insights were identified:

* Revenue fluctuated across the three-month period, highlighting seasonal variations in sales performance.
* A limited number of product lines contributed significantly to total revenue, indicating key revenue-driving categories.
* Expenses increased proportionally with revenue, demonstrating a direct relationship between sales volume and operational costs.
* Profitability differed across cities, suggesting opportunities to optimize performance in lower-performing branches.
* Customers used multiple payment methods, emphasizing the importance of maintaining flexible payment options to enhance customer experience.

---

# 10. Project Workflow

The project followed the standard data analytics lifecycle:

Raw Dataset (Kaggle)

↓

Python Data Cleaning (Pandas)

↓

Exploratory Data Analysis

↓

SQL Business Analysis

↓

Power BI Dashboard Development

↓

Business Insights & Reporting

---

# 11. Challenges Faced

Several practical challenges were encountered during the project:

* Inconsistent column names
* Date format conversion
* SQL column mapping after renaming fields
* Designing an effective dashboard layout
* Selecting appropriate visualizations
* Creating DAX measures for KPI calculations

These challenges were resolved through systematic data cleaning and iterative dashboard refinement.

---

# 12. Future Improvements

Future enhancements may include:

* Sales Forecasting using Machine Learning
* Customer Segmentation
* Inventory Analytics
* Profit Prediction Models
* Automated ETL Pipeline
* Real-Time Dashboard Integration
* Streamlit Web Application Deployment

---

# 13. Conclusion

This project demonstrates an end-to-end financial analytics workflow using Python, SQL, and Power BI. Starting from raw transaction data, the project involved data preprocessing, exploratory analysis, SQL querying, and dashboard creation to deliver meaningful business insights.

The resulting dashboard provides decision-makers with an intuitive overview of financial performance, enabling them to monitor revenue, expenses, profitability, and operational trends through interactive visualizations.

This project strengthened practical skills in data cleaning, SQL, exploratory data analysis, data visualization, dashboard design, and business intelligence, making it a valuable addition to a professional data analytics portfolio.

---

# References

* Kaggle Supermarket Sales Dataset
* Microsoft Power BI Documentation
* Pandas Documentation
* Matplotlib Documentation
* Seaborn Documentation
* SQLite Documentation
