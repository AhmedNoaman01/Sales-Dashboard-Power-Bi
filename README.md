# 📊 Sales Dashboard – Power BI

## 📌 Overview  
This project showcases an **interactive Sales Dashboard** built using **Microsoft Power BI**.  
It provides insights into total sales, costs, profitability, and performance across different regions and products.  

The dashboard was designed to enable business decision-makers to:  
- Track key sales KPIs in real time  
- Identify top-performing products and regions  
- Monitor profitability trends year over year  

---

## 🔹 Key Features  
- **Interactive Filters** – Filter by employee, customer, buying group, country, or state province  
- **KPIs Overview** – Total Sales, Total Cost, Total Profit, Profitability %  
- **Yearly Sales Trends** – Line chart showing sales progression  
- **Regional Performance** – State-wise sales, profit, and performance rating  
- **Product Insights** – Top-selling stock items ranked by revenue  
- **Data Visualization Best Practices** – Clear color coding and intuitive charts  

---

## 🛠 Data Preparation Process  

### 1. **Data Cleaning**  
Performed in **Power Query** to ensure high data quality:  
- Removed duplicates  
- Handled missing values  
- Standardized text formatting  
- Corrected inconsistent entries  

### 2. **Data Modeling**  
Designed a **star schema** for optimal performance:  
- **Fact Table** – Sales transactions with measures for revenue, cost, and profit  
- **Dimension Tables** – Date, Product, Customer, Employee, and Region  
- Relationships established with proper cardinality and filters  

### 3. **DAX Measures**  
Created custom measures for:  
- Total Sales  
- Total Cost  
- Total Profit  
- Profitability %  
- Sales Performance Rating
--------
![Product SCD Flow](https://github.com/AhmedNoaman01/Sales-Dashboard/blob/main/Image/Capture.PNG)

![Product SCD Flow](https://github.com/AhmedNoaman01/Sales-Dashboard/blob/main/Image/Capture2.PNG)

![Product SCD Flow](https://github.com/AhmedNoaman01/Sales-Dashboard/blob/main/Image/Capture3.PNG)
