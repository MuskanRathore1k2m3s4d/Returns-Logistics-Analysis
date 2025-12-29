# Returns Logistics & Revenue Leakage Analysis

##  Project Overview
To identify the root causes of declining net profit despite stable sales volumes.

##  Tools Used
SQL Modeling: Created a master_analytics table by joining sales and returns data to calculate true profit (Sales - Unit Cost - Shipping).
Exploratory Data Analysis (Python): Used Pandas to group data and calculate a 15.50% Return Rate, identifying key loss drivers.
Business Intelligence (Power BI): Designed a dashboard to track $64.59K Net Profit against $259.31K Revenue, highlighting that "NULL" and "Damaged" reasons are the primary leakage points.

##  Key Insights
* The "NULL" Factor:** A large portion of returns had no recorded reason, suggesting a gap in data collection at the warehouse.
* Category Loss:** The 'Beauty' category has the highest return rate (15.5%), significantly eating into margins.
* Profitability:** Identified that shipping costs for returned items are the primary "hidden" cost.

##  Dashboard Preview
![Dashboard](dashboard_preview.png)
