SELECT Product_Category, SUM(Total_Amount) AS Total_Sales
FROM Retail_Sales_Data
GROUP BY Product_Category
ORDER BY Total_Sales DESC;
