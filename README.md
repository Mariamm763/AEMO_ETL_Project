# AEMO_ETL_Project

The aim of this project is to automate the extraction of electricity price and demand data from the Australian Energy Market Operator (AEMO) into Python.
To enable more accurate analysis and forecasting, the project focuses on compiling complete yearly datasets across all five NEM regions (NSW, VIC, QLD, SA, TAS).
___
#  Data Coverage

The script automatically downloads **all five NEM regions (NSW, VIC, QLD, SA, TAS)** across multiple years.  
This is particularly useful for statistical models like **ARIMA**, which require multiple years of continuous data for accurate forecasting.

###  Time Granularity

The database stores **5-minute interval data** — the finest resolution available — allowing users to:

- Aggregate up to **hourly** or **daily** summaries
- Perform precise short-term load forecasting
- Avoid early assumptions about temporal resolution

This structure gives you full control over how much to aggregate, depending on your modeling needs.

###  Usability & Integration

The SQL structure is optimized for **usability in tools like Power BI and Python (pandas)**:

- Create SQL **views** to simplify queries and aggregations
- Easily export to CSV for analysis in Python notebooks
- Fast loading into Power BI for visualization dashboards

Database stucture
___

<img width="605" height="372" alt="Screenshot 2025-07-10 122830" src="https://github.com/user-attachments/assets/c9d7aba7-23a2-4fea-929d-9f383c8585df" />

The picture shows the current structure of the database after it has been created. More tables will be added over time.
