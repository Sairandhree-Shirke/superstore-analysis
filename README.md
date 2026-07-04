# superstore-analysis
Exploratory data analysis uncovering $25K profit leaks, discount problems, and seasonal trends in retail sales data — Python, Pandas, Plotly.
Superstore Sales Analysis & Dashboard

Exploratory data analysis on the Superstore Sales dataset, uncovering profit leaks, discount problems, and regional performance using Python.


What This Project Does

Takes raw sales data (9,994 transactions, 21 columns) and answers 5 real business questions:


Which region is most profitable?
Does higher discount always mean lower profit?
Who are the top 5 customers by sales?
Which states are losing the most money?
Is there a seasonal profit pattern hiding in the data?


Ends with an interactive 4-chart business dashboard built in Plotly.


Key Findings


Furniture generates 27% of revenue but only 6% of total profit deep discounting is destroying its margins
Tables lose $17,725 total every table sold at >20% discount generates a loss on average.
Discounts above 20% push average profit negative ,The company is paying customers to take products at 45–50% discount.
Texas alone loses $25,729 more than the next 4 worst states combined.
35% of annual profit comes in Q4 (Oct–Dec) ,January and February are dangerously weak .


Tech Stack
Python 3
Pandas — data loading, groupby, filtering
Matplotlib — static charts
Plotly — interactive dashboard
superstore-analysis/
│
├── README.md
├── superstore_analysis.ipynb   # Main analysis notebook
└── Sample - Superstore.csv     # Dataset (download from Kaggle)
Dashboard Preview

Profit by Sub-Category — Where is the business bleeding?
Dashboard Preview

Business Recommendation

Stop discounting Tables and Bookcases above 20%. Cap discounts company-wide at 20% and re-evaluate the Furniture category entirely. Focus sales resources on Technology — highest revenue and highest profit margin.


Dataset


Source: Kaggle — Superstore Dataset
Rows: 9,994 transactions
Columns: 21 (Sales, Profit, Discount, Category, Region, State, etc.)
