# Netflix-Financial-Analysis
Portfolio project analyzing Netflix financial statements and stock performance (2022–2025) with key ratios, cashflow metrics, and visualizations.

This project demonstrates a comprehensive financial and stock analysis of Netflix (NFLX) using Python and pandas in Google Colab. The analysis includes:

-Cleaning and transforming income statement, balance sheet, and cashflow CSVs
-Calculating key financial ratios for profitability, leverage, liquidity, and cash flow
-Creating visualizations for insights into financial trends
-Performing data checks and validation to ensure data integrity

Data Sources

All data is publicly sourced and includes:

Income Statement: Total revenue, net income, EBITDA, and other key metrics

Balance Sheet: Total assets, total liabilities, equity, and current assets/liabilities

Cash Flow Statement: Operating cash flow, capital expenditures, free cash flow

Stock Price History: Open, high, low, close, volume

Note: Years with incomplete data (2021) were excluded from the analysis.


Key Financial Metrics Calculated


Profitability Ratios

Net Profit Margin = Net Income / Total Revenue

EBITDA Margin = EBITDA / Total Revenue

Return on Assets (ROA) = Net Income / Total Assets

Return on Equity (ROE) = Net Income / Shareholder Equity


Leverage & Liquidity

Current Ratio = Current Assets / Current Liabilities

Debt-to-Equity Ratio = Total Liabilities / Shareholder Equity

Debt Ratio = Total Liabilities / Total Assets


Cash Flow Metrics

Free Cash Flow (FCF) = Operating Cash Flow – Capital Expenditure


Insights from Analysis

Profitability Trends -

Netflix’s net profit margin and EBITDA margin have been increasing (2022–2025), indicating improved operational efficiency.
ROA and ROE trends show the company is generating more profit per unit of assets and equity.


Leverage and Liquidity - 

Debt-to-equity and debt ratio are gradually declining, signaling reduced leverage.
Current ratio remains stable above 1, showing adequate liquidity to cover short-term obligations.


Cash Flow Analysis -

Free cash flow has increased significantly, consistent with growing profitability.
CFO-to-net-income ratio indicates strong operational cash conversion.


Stock Performance -

Daily and annual stock returns were analyzed and compared to financial trends.
Visualizations show the correlation between financial performance and stock growth.


Technical Highlights

Data cleaning, transposing, and sorting of multiple CSVs

Handling missing values (NaNs) and aligning financial statements with stock data

Calculation of financial ratios and cash flow metrics

Generating colorful, professional plots using matplotlib and pandas

Performing data sanity checks to ensure internal consistency


Visualizations

Profitability ratios over time (Net Profit Margin, EBITDA Margin, ROA, ROE)

Leverage ratios over time (Debt-to-Equity, Debt Ratio)

Cash flow metrics over time (Free Cash Flow, CFO to Net Income)

Stock daily and annual returns (bar charts and line plots)


Skills Demonstrated

Python & pandas for data cleaning, transformation, and analysis

Financial analysis concepts and ratio calculations

Data visualization and storytelling using matplotlib

How to Run

Open this notebook in Google Colab.
Upload the CSV files for Netflix financials:
NFLX_income.csv
NFLX_balance.csv
NFLX_cashflow.csv
NFLX_stock_history.csv
Run all cells sequentially to reproduce the analysis and visualizations.
