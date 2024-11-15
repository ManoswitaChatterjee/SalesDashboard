# USA Sales Analysis - Sales Performence Dashboard

[Interactive Dashboard](https://public.tableau.com/app/profile/manoswita.chatterjee/viz/USASalesPerformanceDashboard_17311638944170/SalesDashboard)


#### Introduction
The USA sales dashboard is an interactive tool that helps in visualizing KPIs, trends, and sales insights with interactive charts for data-driven performance analysis.

#### Goal 
1. The primary goal of the dashboard is to provide insights for USA sales to help make better business decisions.
2. The dashboard also displays important KPIs (Key Performance Indicator(s)) that helps to get a quick overview of the latest sales situation.

#### About the Dataset
1. All the data used in this dashboard is from the Sample Superstore dataset, available in Tableau.
2. It consists of 3 CSV files : Orders, People, and Returns.
3. This dataset contains transaction-level data for a fictional retail store, capturing details on products, categories, customers, sales, and returns across different states in the United States.

#### KPIs 
1. **Total Sales -** This KPI represents the total revenue generated from all sales transactions.
   Formula : Total Sales = SUM(Sales)
   
2. **Profit Margin -** This measures the profitability by comparing profit against sales, indicating how efficiently the business generates profit.
   Formula: Profit Margin = SUM(Profit) / SUM(Sales)
   
3. **Total Orders -** This KPI counts the number of individual orders, providing an overview of transaction volume.
   Formula: Total Orders = COUNT(Order ID)
   
4. **Region with Highest Sales -** This identifies the region that generated the most revenue, highlighting geographical strengths in sales performance.
   Formula: Region with Highest Sales = WINDOW_MAX(SUM(Sales)) = SUM(Sales)
   
5. **Customer Return Rate -** This KPI measures the proportion of orders that were returned, giving insights into product or service satisfaction.
   Formula: Customer Return Rate = COUNT(Order ID (Returns))/COUNT(Order ID)

#### Analysis
The main objective of this report is to nalyze sales performance and profitability trends across the United States.
I specifically choose the above KPIs to help get an overall idea about the ales growth, regional profitability, and customer behavior from the data. This in turn allows to understand the current standing of the sales and which area needs more focus to help with business growth.

#### Overview 

1. Total Sales Count - 2,297,201
2. Profit Margin - 12.47 %
3. Total Orders Count - 9,994
4. Region with Highest Sales - West
5. Customer Return Rate - 2.96 %

![Screenshot_5](https://github.com/user-attachments/assets/ed12f5b0-b574-4910-bfa6-7297ff640528)


####    
