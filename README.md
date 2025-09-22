# S&P 500 Financial Portfolio Analysis (SQL · Python · Tableau)

## Overview
This project analyzes **S&P 500 market performance** to track returns, trends, and risks.  
The workflow starts with **SQL + Python** for data preparation, then moves into **Tableau** for interactive visualization.  

## Tech Stack
- **SQL (SQLite)** – database queries and data extraction  
- **Python (pandas, matplotlib)** – cleaning, transformations, CSV exports  
- **Tableau** – dashboards with KPIs, trends, and portfolio performance analysis
-   
## Methods
**SQL**  
- Queried raw price data from `sap.db`  
- Generated daily and monthly close values  

**Python**  
- Used pandas to clean and reshape data  
- Exported CSVs for Tableau input  

**Tableau**  
- Built three dashboards:  
  1. **Daily Trends** – closing price patterns across the S&P 500  
  2. **Monthly Trends** – end-of-month close analysis for long-term view  
  3. **Portfolio Performance** – returns and risk tracking over time  

## Key Insights
- S&P 500 daily closes show clear volatility clusters, especially around macro events.  
- Monthly aggregation smooths volatility and highlights long-term upward trend.  
- Tableau dashboards enable quick comparison of portfolio growth vs. market baseline.  

## Quick Links
- [Notebook](sap500.ipynb)  
- [Daily/Monthly Exports](exports/)  
- [Tableau Dashboards (TWB Files)](tableau/)
