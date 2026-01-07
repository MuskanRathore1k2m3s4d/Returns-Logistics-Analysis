# E-Commerce Return & Profit Analysis

An end-to-end Data Analytics project designed to identify revenue leakage and profit erosion caused by high return rates and hidden logistics costs using SQL, Python, and Power BI.

##  Project Overview
The company experienced a decrease in net profit despite stable sales. This project analyzes 1,000+ transactions to pinpoint which product categories are losing money and evaluates the financial impact of various return reasons.

##  Project Objectives
* Analyze overall net profit after accounting for Unit Cost and Shipping.
* Identify high-risk product categories with the highest return rates.
* Quantify the financial loss caused by specific return reasons (e.g., "Not as Described").
* Differentiate between "Hidden" shipping costs and actual product costs.
* Build an interactive dashboard for real-time profit tracking.

#  Tools & Technologies Used
* SQL:Data modeling, joining Sales and Returns tables, and calculating Net Profit.
* Python (Pandas, Seaborn): Exploratory Data Analysis (EDA) and visualizing return reason impacts.
* Power BI:KPI creation, DAX measures, and interactive financial visualizations.
* Excel: Initial data exploration and CSV management.

## Dashboard Preview
![Dashboard Preview]("C:\Users\Muskan Rathore\OneDrive\图片\Screenshots\ZARA Dashboard Preview.png.png")

##  Project Structure
Returns-Logistics-Analysis/
│
├── data/
│   ├── sales_data.csv
│   └── returns_data.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── sql_scripts/
│   └── cleaning_queries.sql
│
├── outputs/
│   └── master_cleaned.csv
│
├── dashboard/
│   └── Return_Logistics_Dashboard.pbix
│
└── README.md
