# S&P 500 Portfolio Analysis (SQL · Python · Tableau)

## Overview
This project analyzes **S&P 500 market performance** to track returns, trends, and risks.  
The workflow starts with **SQL + Python** for data preparation, then moves into **Tableau** for interactive visualization.  
Exported visuals make the dashboards accessible without requiring Tableau Desktop.  

## Tech Stack
- **SQL (SQLite)** – queries and data extraction  
- **Python (pandas, matplotlib)** – cleaning, transformations, CSV exports  
- **Tableau** – dashboards with KPIs, trends, and portfolio performance analysis  

## Methods
**SQL**  
- Queried raw price data from `sap.db`  
- Generated daily and monthly close values  

**Python**  
- Used pandas to clean and reshape data  
- Exported CSVs (`daily_close_sp500.csv`, `month_end_close_sp500.csv`) for Tableau  

**Tableau**  
- Built dashboards to visualize growth and returns:  
  - **Growth of $1 (S&P 500)** – long-term compounding growth  
  - **Monthly Returns** – volatility and cyclical patterns  
  - **Portfolio Performance (additional views)**  

## Key Insights
- S&P 500 shows strong long-term compounding growth (“Growth of $1” chart).  
- Monthly return distribution highlights sharp downturns (e.g., 2020, 2022) alongside recovery cycles.  
- Tableau dashboards enable flexible analysis for both short-term volatility and long-term portfolio growth.  

## Visuals
- [Growth of $1 — S&P 500 (PDF)](visual/growth_value.pdf)  
- [Monthly Returns — S&P 500 (PDF)](visual/monthly_returns.pdf)  

## Quick Links
- [Notebook](sap500.ipynb)  
- [Daily/Monthly Exports](exports/)  
- [Tableau Dashboards (TWB Files)](tableau/)  
- [Visual Outputs](visual/)  
