# ☕ Coffee Sales Analysis Dashboard

## 📌 Project Overview
This project focuses on analyzing coffee sales data to extract meaningful insights related to customer behavior, product performance, and regional trends. The goal is to transform raw Excel data into an interactive dashboard for better business decision-making.

---

## 📁 Dataset Description

The dataset consists of three main tables:

### 🧾 Orders
- Contains transactional data (1000+ records)
- Fields: Order ID, Order Date, Customer ID, Product ID, Quantity, Sales

### 👥 Customers
- Customer demographic and geographic details
- Fields: Customer Name, Country, City, Loyalty Card Status

### 📦 Products
- Product-level information
- Fields:
  - Coffee Type (Arabica, Robusta, Liberica, Excelsa)
  - Roast Type (Light, Medium, Dark)
  - Size, Unit Price, Profit

---

## 🔧 Data Processing

- Cleaned and structured raw data
- Handled missing and inconsistent values
- Created relationships between datasets:
  - Orders → Customers
  - Orders → Products
- Performed feature engineering:
  - Total Sales calculation
  - Profit estimation
  - Category mapping (Coffee Type, Roast Type)

---

## 📊 Dashboard Features

- 📅 **Sales Trend Analysis**
  - Monthly and yearly trends (2019–2022)

- ☕ **Product Performance**
  - Sales by coffee type
  - Roast type comparison

- 🌍 **Geographical Insights**
  - Country-wise sales distribution

- 👥 **Customer Analysis**
  - Top 5 customers by sales
  - Loyalty card impact on purchasing behavior

---

## 📈 Key Insights

- Majority of revenue comes from the United States
- Arabica and Excelsa are among the top-performing coffee types
- Noticeable seasonal trends in sales data
- A small group of customers contributes significantly to total revenue

---

## 🛠 Tools & Technologies

- Microsoft Excel
  - Pivot Tables
  - Data Visualization (Charts)
  - Slicers & Interactive Dashboard
- Data Cleaning & Transformation

---

## 🚀 How to Use

1. Download the Excel file from this repository
2. Open the file in Microsoft Excel
3. Navigate to the **Dashboard** sheet
4. Use slicers and filters to explore insights interactively

---

## 📌 Conclusion

This project demonstrates the ability to:
- Work with structured datasets
- Perform data cleaning and transformation
- Build interactive dashboards
- Generate actionable business insights

---

## 🔗 Future Improvements

- Build the same dashboard in Power BI
- Integrate SQL for data extraction
- Add predictive analysis using Python
