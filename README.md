# 📊 Retail Sales Performance Dashboard

## 📌 Project Overview
Retail businesses generate huge amounts of sales data, but without proper analysis, it remains underutilized. This project analyzes **retail sales performance** using **SQL** for data extraction and transformation, and **Power BI** for visualization.

📊 **Key Features:**
- **Interactive Power BI Dashboard** 📈 for visual storytelling.
- **SQL queries** 🛠️ to extract and analyze sales trends.
- **Data preprocessing** 🔄 for accurate insights.
- **Sales performance evaluation** across different time periods, product categories, and regions.

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Dataset](#-dataset)
- [Power BI Dashboard](#-power-bi-dashboard)
- [SQL Queries](#-sql-queries)
- [Insights & Results](#-insights--results)
- [How to Use](#-how-to-use)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

## 📊 Dataset
- **Source**: [Kaggle Retail Dataset](https://www.kaggle.com/) (or proprietary dataset)
- **Size**: 10,000+ records
- **Columns**:
  - `Order_ID` - Unique transaction ID
  - `Product_Name` - Name of the sold product
  - `Category` - Product category
  - `Sales` - Revenue generated
  - `Quantity` - Number of units sold
  - `Discount` - Discount applied
  - `Profit` - Net profit earned
  - `Order_Date` - Date of purchase
  - `Region` - Geographic sales region

---

## 📊 Power BI Dashboard
Here is a preview of the Power BI dashboard:

![Dashboard Screenshot](images/dashboard.png)

---

## 🛠 SQL Queries
Here’s an example of a SQL query used to calculate total sales per category:

```sql
SELECT Category, SUM(Sales) AS Total_Sales
FROM Sales_Data
GROUP BY Category
ORDER BY Total_Sales DESC;
