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

## 📌 Insights & Results

This project helped uncover key insights from the retail sales dataset, such as:

- 📊 **Top-selling products** and **least-performing items**
- 📈 **Revenue trends** over different time periods
- 📍 **Geographical sales distribution**
- 📦 **Inventory analysis** to optimize stock management

The insights were visualized using Power BI dashboards to provide an intuitive understanding of sales performance.

---

## 📷 Power BI Dashboard Screenshots

Here are some snapshots of the Power BI dashboards created:

![Dashboard Screenshot 1](screenshots/dashboard1.png)
![Dashboard Screenshot 2](screenshots/dashboard2.png)

---

## 📂 Repository Structure


---

## 🚀 How to Use This Project

1. Clone this repository using:
   ```sh
   git clone https://github.com/YourGitHubUsername/Retail-Sales-Performance-Dashboard.git


---

### **Step 3: Add Screenshots of Power BI Dashboard**
1. **Create a folder named `screenshots` in your GitHub repository.**  
   - Click on **"Add File"** > **"Create new file"**  
   - In the "file name" box, type `screenshots/placeholder.txt` (GitHub needs at least one file to save an empty folder).  
   - Click **Commit changes**.

2. **Upload your Power BI Dashboard screenshots.**  
   - Open the `screenshots` folder in GitHub.  
   - Click on **"Add File"** > **"Upload Files"**.  
   - Select your Power BI images and upload them.  
   - Click **Commit changes**.

---

### **Step 4: Save & Commit README Changes**
1. Once you've pasted the above content in `README.md`, click **Commit changes**.
2. Your README file is now complete!

---

**Final Step: Check Your Repository**  
Go back to your repository homepage and check if:
- The **README file** is properly formatted.
- The **screenshots folder** contains your images.

That's it! Let me know if you need any clarification. 🚀

