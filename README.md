BUSINESS OBJECTIVE
To optimize retail performance across 45 stores by leveraging data-driven insights for strategic decision-making. The goal is to enhance revenue generation, improve operational efficiency, and develop accurate forecasting capabilities to support business growth.



DATASET DESCRIPTION
1.	STORES  DATASET (stores.csv)
●	Contains information about 45 retail outlets


●	Columns:

○	Outlet_ID: Unique identifier for each retail location (1001-1045)

○	Category: Store classification (Premium, Standard, Express)

○	Square_Meters: Physical size of store in square meters

2.	FEATURES  DATASET (features.csv)

●	Contains weekly environmental and promotional data for each store

●	Total records: 8,190

●	Columns:

○	Outlet_ID: Store identifier

○	Week_Period: Date of data collection

○	Avg_Temp: Average temperature for the week

○	Gas_Cost_per_Liter: Fuel price

○	Promo1_Percent to Promo5_Percent: Different promotional discounts

○	Price_Index: Consumer Price Index

○	Jobless_Rate: Unemployment rate

3.	SALES  DATASET (sales.csv)

●	Contains weekly sales data per department for each store

●	Total records: 421,570

●	Columns:

○	Outlet_ID: Store identifier

○	Section_ID: Department identifier

○	Week_Period: Sales week date
○	Period_Revenue_K: Weekly sales in thousands
○	Special_Week: Holiday week indicator (True/False)
