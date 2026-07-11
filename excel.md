# 📊 Excel Sales Data Analysis Portfolio Project

## 🌟 Project Overview

Throughout these two projects, I used **Microsoft Excel** to clean, analyse, and visualise retail and bike sales data. The aim was to transform sales data into insights by analysing customer behaviour, product performance, and revenue trends.

---

# 📂 Datasets

## 🛒 Retail Sales Dataset

## 🚲 Bike Sales Dataset

**Source:** Provided via bootcamp

The retail dataset contains **1,001 rows** of customer, product, and sales information.

The bike sales dataset contains **113,037 transactions**, including customer demographics, product information, sales, costs, and revenue.

---

# 🧹 Data Preparation

The following steps were completed to prepare the datasets for analysis:

✅ Removing duplicates.  
✅ Standardising dates and currency formats.  
✅ Cleaning and organising the datasets.  
✅ Applying Excel formulas to calculate business metrics.  
✅ Creating PivotTables to summarise sales performance.  
✅ Building PivotCharts to visualise trends.  
✅ Using conditional formatting to highlight key patterns and performance.  

---

# 🔄 Data Formatting and Transformation

The original Date column displayed Excel serial numbers instead of a date, so I changed the format of the Date column to **“Date”** to allow the dates values to be displayed correctly.

I also used the **YEAR()**, **MONTH()**, and **DAY()** functions to extract the year, month, and day from the original Date column.

Creating separate date fields made it easier to analyse sales trends over time using PivotTables and PivotCharts.

---

# 🔍 Analysis

The analysis included:

- Data cleaning and formatting.
- SUMIFS and AVERAGEIF functions.
- Calculated columns for revenue, cost, and profit.
- PivotTables to summarise data.
- PivotCharts to visualise and analyse trends.
- Conditional formatting to highlight performance.

---

# 🛒 Retail Dataset

## 📦 Product Performance Analysis

I created a product performance summary table to analyse sales performance and customer purchasing behaviour.

The table included total sales, customer purchases by gender, and average sales per product.

I used **SUMIF()**, **SUMIFS()**, and **AVERAGEIF()** to calculate sales metrics based on different criteria and applied conditional formatting to highlight higher and lower performing products.

This helped identify differences in product performance and purchasing patterns.

---

## 👥 Creating Age Categories

The original dataset had a numerical age column, I created an age category column using the **IFS()** function to group customers into Young Adults, Adults, and Seniors.

This made it easier to compare sales across different age groups in PivotTables and charts.

---

## 💰 Creating Calculated Columns

The original dataset did not contain a commission value, so I created a new Commission column to calculate the commission earned on each sale.

I calculated this by multiplying the Total Sales value by the commission rate of **1.5%**.

---

# 🚲 Bike Sales Dataset

## 📈 Revenue and Profit Trend Analysis

I created a PivotTable to summarise annual revenue and profit from 2017 to 2021.

The data was grouped by year and displayed in a PivotChart to show revenue and profit trends over time, making it easier to identify overall business growth.

---

# 📊 Visualisation

## Images

(Add project dashboard images here)

---

# 💡 Key Findings

## 1️⃣ Customer Purchasing Behaviour

The retail analysis showed that clothing was the most frequently purchased product category by both male and female customers.

However, despite having the highest purchase volume, clothing generated the lowest total sales, indicating a lower average selling price compared with other product categories.

**Business relevance:**  
Understanding purchasing behaviour helps organisations evaluate pricing strategies, product performance, and opportunities to improve profitability.

---

## 2️⃣ Revenue Trends and Market Performance

The bike sales analysis revealed strong revenue growth over five years, reaching a peak of **$29.7 million in 2021**.

The United States generated the highest overall revenue, while adult customers accounted for half of all purchases, making them the largest customer group.

**Business relevance:**  

These insights can help organisations identify high-performing markets, understand their core customer base, and make informed decisions about future sales and marketing strategies.

---

# ✅ Conclusion

This project demonstrates my ability to clean and analyse data using Excel, apply formulas and PivotTables, and create visualisations and identify insights.
