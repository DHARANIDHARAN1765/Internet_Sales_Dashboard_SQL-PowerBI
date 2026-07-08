# 📊 Internet Sales Dashboard Analysis | SQL + Power BI

## 📌 Project Overview
This project transforms static Excel sales reports into interactive Power BI dashboards to help management monitor business performance and make data-driven decisions. SQL was used to clean and prepare the raw data, while Power BI was used to build the data model, create DAX measures, and design interactive dashboards.

---

## 🎯 Project Objectives
- Analyze Internet Sales performance.
- Identify top customers and best-selling products.
- Compare actual sales with the sales budget.
- Provide interactive filters for customer, product, and date.
- Replace manual Excel reports with dynamic Power BI dashboards.

---

## 🛠️ Technologies Used
- SQL
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Microsoft Excel

---

## 📂 Project Workflow

### 1. Business Requirement Analysis
- Understood business requirements from the Sales Manager.
- Identified required KPIs and dashboard features.

### 2. Data Cleaning using SQL
- Removed duplicate records.
- Handled missing values.
- Selected only required columns.
- Prepared clean datasets for reporting.

### 3. Data Modeling in Power BI
Created a Star Schema by connecting:

- Fact Internet Sales
- Dim Customer
- Dim Product
- Dim Date
- Dim Sales Territory

---

## 📈 DAX Measures Created
- Total Sales
- Total Orders
- Total Customers
- Sales vs Budget

---

## 📊 Dashboards

### Sales Dashboard
- Total Sales KPI
- Sales Trend
- Budget vs Sales
- Regional Sales Performance

### Customer Dashboard
- Top Customers
- Customer Purchase Analysis
- Customer-wise Sales

### Product Dashboard
- Best Selling Products
- Category Performance
- Product Sales Analysis

---

## ✨ Key Features
- Interactive dashboards
- Dynamic filters (Customer, Product, Date)
- Star Schema data model
- KPI cards
- Sales trend analysis
- Budget comparison
- Customer insights
- Product performance analysis

---

---

## 📁 Project Structure

```
Internet-Sales-Dashboard/
│
├── Dataset/
│   ├── FactInternetSales.csv
│   ├── DimCustomer.csv
│   ├── DimProduct.csv
│   ├── DimDate.csv
│   └── SalesBudget.csv
│
├── SQL/
│   └── DataCleaning.sql
│
├── PowerBI/
│   └── InternetSalesDashboard.pbix
│
├── Images/
│   ├── SalesDashboard.png
│   ├── CustomerDashboard.png
│   └── ProductDashboard.png
│
└── README.md
```

---

## 💼 Business Impact
This project converts manual Excel reporting into interactive dashboards, enabling faster reporting, better performance monitoring, and informed decision-making.




---

⭐ If you found this project useful, don't forget to give it a Star!
