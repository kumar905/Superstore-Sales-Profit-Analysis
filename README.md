## Superstore Sales & Profit Analysis

An end-to-end exploratory data analysis (EDA) of the Sample Superstore dataset — a US retail store's order-level data — built entirely with pandas, NumPy, and Matplotlib (no Plotly/Seaborn). The project uncovers monthly sales & profit trends, category/sub-category performance, customer-segment behavior, and profit efficiency.


📌**Project Overview**

The Sample Superstore dataset contains 9,994 order line items from a US-based retail store, spanning 3 product categories (Furniture, Office Supplies, Technology) across 17 sub-categories, sold to 3 customer segments (Consumer, Corporate, Home Office). This case study answers seven core business questions using pure Python data analysis — no BI tool involved.


🎯 **Objectives**

1. Calculate monthly sales and identify the highest/lowest sales months
2. Analyze sales by product category — highest and lowest performing category
3. Break down sales performance by sub-category
4. Analyze monthly profit and identify the most profitable month
5. Analyze profit by category and sub-category
5. Analyze sales and profit by customer segment
6. Analyze the sales-to-profit ratio (profit efficiency)


🛠️ **Tools & Libraries**


1. Python	Core language

2. pandas	Data loading, cleaning, aggregation

3. NumPy	Numerical operations

4. Matplotlib	Data visualization

5. Jupyter Notebook	Analysis environment


🔍 **Analysis Workflow**

Data Cleaning — checked for duplicates and null values (none found), converted Order Date/Ship Date to datetime, derived Order Year, Order Month, and Order Month Name

Monthly Sales & Profit Trends — grouped by month across all years to reveal seasonality

Category / Sub-Category Analysis — aggregated sales and profit to find top and bottom performers

Segment Analysis — compared Consumer, Corporate, and Home Office on sales, profit, and margin

Profit Efficiency — computed a Sales-to-Profit ratio and profit margin % per segment and category


📊 ##Key Findings


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

Monthly Sales Analysis (line chart, best/worst month highlighted)

<img width="1000" height="500" alt="Monthly sales analysis" src="https://github.com/user-attachments/assets/53f6ddc1-eaa7-4ff7-a6e9-c96aa3614348" />



Sales Analysis by Category (bar chart)

<img width="1000" height="500" alt="Sales Analysis by Category" src="https://github.com/user-attachments/assets/34b1395b-7faf-4384-8f41-55969577ee3d" />


Sales Analysis by Sub-Category (horizontal bar chart)

<img width="1100" height="600" alt="Sales analysis by Sub-Category" src="https://github.com/user-attachments/assets/a2072ff2-1942-473e-8e94-40ee2b61fb3b" />


Monthly Profit Analysis (line chart)

<img width="1000" height="500" alt="Monthly Profit analysis" src="https://github.com/user-attachments/assets/9f698ed9-366d-4705-9543-70626a885ba0" />


Profit Analysis by Category (bar chart, losses in red)

<img width="1000" height="500" alt="Profit Analysis by Category" src="https://github.com/user-attachments/assets/54daae29-9b58-42fd-b51b-4b75e4c3bbe8" />


Profit Analysis by Sub-Category (horizontal bar chart, losses in red)

<img width="1100" height="600" alt="Profit Analysis by Sub-Catagory" src="https://github.com/user-attachments/assets/cb0981ab-3ffe-4214-9e79-a1be1f759c7c" />


Sales & Profit by Customer Segment (grouped bar chart)

<img width="1000" height="500" alt="Sales and Profit by Customer Segment" src="https://github.com/user-attachments/assets/6b7ecf50-4d0e-4bd0-918e-dc861b7f7c20" />


Sales-to-Profit Ratio by Segment (bar chart)

<img width="1000" height="500" alt="Sales to Profit Ratio by Segment" src="https://github.com/user-attachments/assets/b9b8209e-f3e4-46cd-bd5a-541c177430d4" />



💡 Superstore Sales & Profit Analysis

An end-to-end exploratory data analysis (EDA) of the Sample Superstore dataset a US retail store's order-level data built entirely with pandas, NumPy, and Matplotlib (no Plotly/Seaborn). The project uncovers monthly sales & profit trends, category/sub-category performance, customer-segment behavior, and profit efficiency.



💡 Business Recommendations

Investigate Furniture profitability — Tables and Bookcases operate at a loss; review discounting and pricing strategy for these sub-categories

Double down on Technology — highest sales and highest profit; a strong candidate for continued investment/promotion

Re-examine Consumer segment discounting — despite leading on total profit, it has the lowest profit margin of the three segments

Plan inventory/staffing around seasonality — sales and profit both peak toward year-end (Nov–Dec), suggesting a strong holiday shopping pattern


👤 **Author**

Kumar Dadarao Wankhade

LinkedIn - www.linkedin.com/in/kumarwankhade
