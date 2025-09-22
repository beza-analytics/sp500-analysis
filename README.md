# S&P 500 Portfolio Analysis (SQL · Python · Excel · Tableau)

## Overview
This project analyzes **S&P 500 market performance** to track returns, growth, and volatility.  
The workflow starts with **SQL + Python** for data preparation, moves into **Excel** for applied financial analysis, and ends with **Tableau dashboards** for interactive visualization.  
Exported visuals and Excel workbooks make the insights accessible without specialized software.

## Tech Stack
- **SQL (SQLite)** – queries and data extraction  
- **Python (pandas, matplotlib)** – cleaning, transformations, CSV exports  
- **Excel** – growth of $1 analysis, monthly return calculations, CAGR/volatility metrics  
- **Tableau** – dashboards with KPIs, trends, and portfolio performance  

## Methods
**SQL**  
- Queried raw price data from `sap.db`  
- Generated daily and monthly close values  

**Python**  
- Used pandas to clean and reshape data  
- Exported CSVs (`daily_close_sp500.csv`, `month_end_close_sp500.csv`) for Excel & Tableau  

**Excel**  
- **sap_daily.xlsx** – shows growth of $1 invested, daily returns, and risk/return metrics (CAGR, annualized return, volatility)  
- **sap_monthly.xlsx** – summarizes monthly % returns with pivot charts and volatility trends  

**Tableau**  
- Built dashboards to visualize growth and returns:  
  - **Growth of $1 (S&P 500)** – long-term compounding growth  
  - **Monthly Returns** – volatility and cyclical patterns  
  - **Additional Tableau Views** – exploratory visualizations included in `/tableau/`  

## Key Insights
- S&P 500 shows strong long-term compounding growth (“Growth of $1” view).  
- Monthly return distribution highlights sharp downturns (e.g., 2020, 2022) alongside recovery cycles.  
- Risk metrics (volatility, CAGR) help compare daily vs. monthly horizons.  
- Tableau dashboards enable flexible analysis for both short-term volatility and long-term portfolio growth.  

## Visuals
- [Growth of $1 — S&P 500 (PDF)](visual/growth_value.pdf)  
- [Monthly Returns — S&P 500 (PDF)](visual/monthly_returns.pdf)  

## Quick Links
- [Notebook](sap500.ipynb)  
- [Daily/Monthly Exports (CSV)](exports/)  
- [Daily Returns (Excel: Growth of $1 + Risk Metrics)](excel/sap_daily.xlsx)  
- [Monthly Returns (Excel: Chart + Monthly Change)](excel/sap_monthly.xlsx)  
- [Tableau Dashboards (TWB Files)](tableau/)  
- [Visual Outputs (PDFs)](visual/)  
