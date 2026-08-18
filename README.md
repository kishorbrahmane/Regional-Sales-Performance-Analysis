# Regional Sales Performance Analysis

An end-to-end sales analytics project analyzing regional sales performance, profitability, product categories, and sales trends using **Python, SQL, and Power BI**.

## Business Problem

A company operating across multiple regions wants to understand what is driving sales and profitability.

The project focuses on identifying:

* Top-performing regions and product categories
* Revenue and profit contribution
* Impact of discounting on profitability
* Sales trends and seasonality
* Underperforming regions and categories
* KPIs that leadership should monitor

## Dataset

The project uses regional sales transaction data containing:

* Order-level sales transactions
* Regional information
* Product categories and sub-categories
* Sales and profit
* Discount information
* Order dates

The raw Excel dataset is cleaned and exported as a CSV for downstream SQL and Power BI analysis.

## Tools & Technologies

* **Python / Pandas** — Data cleaning and exploratory analysis
* **SQL** — Business analysis and KPI calculation
* **Power BI** — Interactive dashboard and visualization
* **PowerPoint** — Stakeholder presentation

## Project Workflow

### 1. Data Cleaning — Python

The raw sales dataset was analyzed and prepared using Pandas.

Key steps included:

* Loading and inspecting the dataset
* Handling missing values
* Cleaning inconsistent data
* Standardizing fields
* Exporting the cleaned dataset

### 2. Exploratory Data Analysis

EDA was performed to understand:

* Regional sales performance
* Product category performance
* Revenue and profit trends
* Discount patterns
* Monthly sales behavior

### 3. SQL Analysis

SQL was used to calculate important business metrics including:

* Regional revenue
* Regional profit
* Profit margins
* Category-level performance
* Monthly sales growth
* Sales and profitability trends

### 4. Power BI Dashboard

An interactive Power BI dashboard was developed to monitor:

* Revenue
* Profit
* Profit margin
* Regional performance
* Product category performance
* Sales trends

Filters allow users to analyze performance across different time periods, regions, and product categories.

### 5. Business Reporting

The findings were summarized into a stakeholder-focused presentation highlighting major observations and recommendations.

## Key Business Questions

* Which regions generate the highest revenue and profit?
* Which product categories perform best?
* Are high sales volumes translating into higher profitability?
* How does discounting affect profit margins?
* Which regions or categories are underperforming?
* How does sales performance change over time?
* Which KPIs should leadership monitor regularly?

## Key Insights

The analysis is designed to identify:

* High-revenue and high-profit regions
* Categories with strong sales but weak profitability
* Regions affected by excessive discounting
* Monthly and seasonal sales patterns
* Areas requiring performance improvement

*Specific numerical findings should be added after completing the analysis.*

## Recommendations

Potential business recommendations include:

* Review discount strategies where high sales do not translate into proportional profit.
* Focus sales and marketing resources on high-potential regions.
* Investigate underperforming product categories.
* Monitor revenue, profit margin, and discount rate as core KPIs.
* Use monthly sales trends to improve inventory and resource planning.

## Project Structure

```text id="q4y7mx"
Regional-Sales-Performance-Analysis/
│
├── data/
│   ├── Regional Sales Dataset.xlsx
│   └── Sales_data(EDA Exported).csv
│
├── notebooks/
│   └── EDA_Regional_Sales_Analysis.ipynb
│
├── dashboard/
│   └── SALES REPORT.pbix
│
├── presentation/
│   └── PPT - Regional Sales Analysis.pptx
│
└── README.md
```

## How to Explore

1. Open `EDA_Regional_Sales_Analysis.ipynb` to review the Python analysis.
2. Review the cleaned CSV used for downstream analysis.
3. Open `SALES REPORT.pbix` in Power BI Desktop to explore the dashboard.
4. Review the presentation for the stakeholder-focused findings and recommendations.

## Conclusion

This project demonstrates an end-to-end **Data Analyst workflow**, combining Python, SQL, and Power BI to transform raw sales data into business insights that support revenue, profitability, and sales performance decisions.
