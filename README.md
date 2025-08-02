# Power BI Sales Performance Dashboard

This project presents a comprehensive **Sales Performance Dashboard** built using Power BI. It analyzes sales, profit, and customer performance across different categories and regions. The goal is to help stakeholders quickly gain insights and make data-driven decisions.

---

## Key Metrics Displayed

-  **Total Sales:** 179.57K  
-  **Total Profit:** 34.61K  
-  **Profit Margin:** 19.27%

---

##  Business Questions Answered

This dashboard was built to solve the following business problems:

1.  **What is the total sales, total profit, and profit margin?**  
   → Answered using KPI cards.

2.  **Which product categories generate the most sales?**  
   → Answered using horizontal bar charts.

3.  **Which regions contribute the most in quantity sold and profit?**  
   → Answered using donut charts for region-wise breakdown.

4.  **What is the monthly trend of sales?**  
   → Answered using a line chart (sales over months).

5.  **Who are the top customers based on sales and profit?**  
   → Answered using a tabular report showing total sales, profit, and order count.

6.  **How is sales distributed across geographic regions?**  
   → Answered using a map visualization.

---

##  DAX Measures Used

Here are the custom DAX formulas used to calculate KPIs in the dashboard:

```DAX
-- Total Sales
Total Sales = SUM(Sales[Sales Amount])

-- Total Profit
Total Profit = SUM(Sales[Profit])

-- Profit Margin
Profit Margin = 
    DIVIDE(
        [Total Profit],
        [Total Sales],
        0
    )

🛠️ Tools Used
      Power BI Desktop
      Microsoft Excel (for data processing)
      DAX (Data Analysis Expressions)

## How to Use
Download or clone the repository.

Open the .pbix file with Power BI Desktop.

Explore the interactive dashboard.

Optionally, connect your own dataset to reuse the visuals and structure.

👤 Author
Rakibul Islam
rir.rakibulislam@gmail.com
