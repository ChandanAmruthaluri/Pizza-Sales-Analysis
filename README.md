# 🍕 Pizza Sales Data Analysis Project

## 📊 Project Overview
This project analyzes sales data for a pizza chain to identify key business indicators such as bestselling categories, peak sales times, and revenue drivers. The analysis combines **SQL** for data verification and **Power BI** for interactive visualization, enabling data-driven decisions for inventory management and marketing strategies.

**View the Interactive Dashboard:** [https://drive.google.com/file/d/13w5DV_vO8wcnFFTBYNJxiYPVf3YC14GN/view?usp=sharing]

## 🛠️ Tech Stack
* **Database:** MySQL (Data storage & querying)
* **Visualization:** Microsoft Power BI (Dashboarding & Reporting)
* **Data Transformation:** Power Query (ETL)
* **Analysis Language:** DAX (Data Analysis Expressions) & SQL

---

## 🔍 Key Performance Indicators (KPIs)
The dashboard tracks the following core metrics:
* **Total Revenue:** Sum of the final price of all pizza orders.
* **Average Order Value:** The average amount spent per order.
* **Total Pizzas Sold:** The total quantity of pizzas delivered.
* **Total Orders:** The distinct count of order IDs.
* **Average Pizzas Per Order:** Calculation of the average number of pizzas in a single basket.

---

## 📈 Dashboard Insights & Features

### 1. Daily & Monthly Trends
* Visualized daily trends to identify the busiest days of the week (e.g., Friday/Saturday spikes).
* Analyzed monthly sales data to track seasonality and growth periods.

### 2. Category & Size Analysis
* **Sales by Category:** Breakdown of sales across Classic, Supreme, Veggie, and Chicken categories.
* **Sales by Size:** Analysis of customer preference for Large, Medium, or Regular pizzas.

### 3. Best & Worst Sellers
* Identified the **Top 5 Pizzas** by Revenue, Quantity, and Total Orders.
* Identified the **Bottom 5 Pizzas** to highlight underperforming menu items.

---

## 💻 Technical Implementation

### SQL Data Validation
SQL was used to verify the accuracy of the Power BI figures. Below are sample queries used in the analysis:

**1. Calculate Total Revenue:**
```sql
SELECT SUM(total_price) AS Total_Revenue FROM pizza_sales;
