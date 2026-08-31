## Superstore Sales & Profit Analysis

An end-to-end exploratory data analysis (EDA) of the Sample Superstore dataset — a US retail store's order-level data — built entirely with pandas, NumPy, and Matplotlib (no Plotly/Seaborn). The project uncovers monthly sales & profit trends, category/sub-category performance, customer-segment behavior, and profit efficiency.


<img width="1000" height="500" alt="Monthly Profit analysis" src="https://github.com/user-attachments/assets/9f698ed9-366d-4705-9543-70626a885ba0" />


📌**Project Overview**

The Sample Superstore dataset contains 9,994 order line items from a US-based retail store, spanning 3 product categories (Furniture, Office Supplies, Technology) across 17 sub-categories, sold to 3 customer segments (Consumer, Corporate, Home Office). This case study answers seven core business questions using pure Python data analysis — no BI tool involved.


🎯 **Objectives**
Calculate monthly sales and identify the highest/lowest sales months
Analyze sales by product category — highest and lowest performing category
Break down sales performance by sub-category
Analyze monthly profit and identify the most profitable month
Analyze profit by category and sub-category
Analyze sales and profit by customer segment
Analyze the sales-to-profit ratio (profit efficiency)


🛠️ **Tools & Libraries**

Tool	Purpose
Python	Core language
pandas	Data loading, cleaning, aggregation
NumPy	Numerical operations
Matplotlib	Data visualization
Jupyter Notebook	Analysis environment


🔍 **Analysis Workflow**
Data Cleaning — checked for duplicates and null values (none found), converted Order Date/Ship Date to datetime, derived Order Year, Order Month, and Order Month Name
Monthly Sales & Profit Trends — grouped by month across all years to reveal seasonality
Category / Sub-Category Analysis — aggregated sales and profit to find top and bottom performers
Segment Analysis — compared Consumer, Corporate, and Home Office on sales, profit, and margin
Profit Efficiency — computed a Sales-to-Profit ratio and profit margin % per segment and category


📊** Key Findings**

#	Question	Finding

1	Monthly sales — highest / lowest	Nov ($352,461) highest · Feb ($59,751) lowest

2	Category sales — highest / lowest	Technology ($836,154) highest · Office Supplies ($719,047) lowest

3	Sub-category sales — highest / lowest	Phones ($330,007) highest · Fasteners ($3,024) lowest

4	Monthly profit — highest	Dec ($43,369)

5	Category profit — highest / lowest	Technology ($145,455) highest · Furniture ($18,451) lowest

5	Sub-category profit — highest / lowest	Copiers ($55,618) highest · Tables (-$17,725, a loss) lowest

6	Segment — highest sales & profit	Consumer leads on both sales ($1.16M) and profit ($134K)

7	Most profit-efficient segment	Home Office (lowest sales-to-profit ratio, ~14.0% margin) vs Consumer (least efficient, ~11.5% margin)

Bonus — profit efficiency by category: Technology and Office Supplies convert sales into profit efficiently (~17% margin each), while Furniture is highly inefficient — a Sales-to-Profit ratio of ~40x versus ~5.7–5.9x for the other two categories, driven largely by loss-making Tables and Bookcases.


📈 **Visualizations**

The notebook generates and saves the following charts to images/:

Monthly Sales Analysis (line chart, best/worst month highlighted)

Sales Analysis by Category (bar chart)

Sales Analysis by Sub-Category (horizontal bar chart)

Monthly Profit Analysis (line chart)

Profit Analysis by Category (bar chart, losses in red)

Profit Analysis by Sub-Category (horizontal bar chart, losses in red)

Sales & Profit by Customer Segment (grouped bar chart)

Sales-to-Profit Ratio by Segment (bar chart)

💡 Superstore Sales & Profit Analysis

An end-to-end exploratory data analysis (EDA) of the Sample Superstore dataset — a US retail store's order-level data — built entirely with pandas, NumPy, and Matplotlib (no Plotly/Seaborn). The project uncovers monthly sales & profit trends, category/sub-category performance, customer-segment behavior, and profit efficiency.



📌 Project Overview

The Sample Superstore dataset contains 9,994 order line items from a US-based retail store, spanning 3 product categories (Furniture, Office Supplies, Technology) across 17 sub-categories, sold to 3 customer segments (Consumer, Corporate, Home Office). This case study answers seven core business questions using pure Python data analysis — no BI tool involved.



💡 Business Recommendations
Investigate Furniture profitability — Tables and Bookcases operate at a loss; review discounting and pricing strategy for these sub-categories
Double down on Technology — highest sales and highest profit; a strong candidate for continued investment/promotion
Re-examine Consumer segment discounting — despite leading on total profit, it has the lowest profit margin of the three segments
Plan inventory/staffing around seasonality — sales and profit both peak toward year-end (Nov–Dec), suggesting a strong holiday shopping pattern


👤 **Author**

Kumar Dadarao Wankhade

LinkedIn - www.linkedin.com/in/kumarwankhade
