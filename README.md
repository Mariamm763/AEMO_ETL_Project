# AEMO_ETL_Project

This project automates the extraction and structuring of electricity price and demand data from the Australian Energy Market Operator (AEMO) into Python and SQL databases. The goal is to support time series forecasting and market analysis across all five National Electricity Market (NEM) regions.
___
#  Data Coverage
- Automatically downloads and compiles data for:
 NSW, VIC, QLD, SA, TAS

- Supports multi-year extraction for long-term trend analysis

- Ideal for statistical models such as ARIMA and machine learning pipelines

###  Time Granularity

-Data is stored at 5-minute resolution — the most granular available

- Easily aggregate to:

- Hourly, daily, or custom time intervals

- Supports: 

  - Short-term load forecasting

  - Peak demand analysis

- Price signal modeling

###  Usability & Integration
- Designed for seamless use in:

- Python (Pandas)

- Power BI

- SQL-based querying

- Features:

  - SQL views for simplified analysis

  - CSV export options

  - Fast loading into dashboards

Database stucture
___

- 5-minute interval data stored by year and region

- Easily extendable with:

  - Renewable generation

  - Interconnector flow

  - Emissions

  - Market bidding data


<img width="605" height="372" alt="Screenshot 2025-07-10 122830" src="https://github.com/user-attachments/assets/c9d7aba7-23a2-4fea-929d-9f383c8585df" />

The picture shows the current structure of the database after it has been created. More tables will be added over time.
