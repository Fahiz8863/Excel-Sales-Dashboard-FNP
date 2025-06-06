# Excel-Sales-Dashboard-FNP
An interactive Excel dashboard for analyzing sales performance of FNP products by occasion, product, location, and time. Includes pivot tables, slicers, and visual KPIs for actionable insights.

# Excel Sales Dashboard – FNP

This project presents an interactive Excel dashboard designed for analyzing sales data of FNP (Flowers N Petals) across multiple dimensions such as occasions, products, cities, and time periods. It combines visual analytics with pivot tables and slicers to enable efficient and dynamic data exploration.

---

## 🧩 Data Model & Relationships

A relational data model was created in **Excel’s Power Pivot** to efficiently manage multiple tables and support dynamic analysis.

**Entities:**
- `Customers`
- `Orders`
- `Products`
- `Metadata` (File data)

**Relationships:**
- `Customers[Customer_ID]` → `Orders[Customer_ID]`
- `Products[Product_ID]` → `Orders[Product_ID]`

## 📊 Dashboard Highlights

- **Total Revenue**: ₹35,20,984  
- **Total Orders**: 1000  
- **Average Delivery Time**: 5.53 days  
- **Average Customer Spend**: ₹3,520.98  

### Key Visuals:
- Revenue by Occasions, Months, and Product Category  
- Top 5 Products and Top 10 Cities by Revenue  
- Orders by Day of the Week  
- Interactive filters for Occasion, Order Date, and Delivery Date  

---

## 🧮 Pivot Tables & Data Analysis

Included pivot tables to provide:
- Revenue breakdown by product category, city, and occasion
- Order volume by day of the week
- Correlation analysis (order quantity vs. delivery time)
- Dynamic slicers for filtering views

---

## 🛠 Tools Used

- **Microsoft Excel**
  - Pivot Tables
  - Slicers
  - Line and Bar Charts
  - Conditional Formatting
  - Dashboard Design

---

## 💡 Use Cases

- Sales trend monitoring  
- Regional and product-wise performance tracking  
- Festival-based revenue analysis  
- Customer behavior understanding

---

## 📌 Author

Fahiz Mohammed PP
Aspiring Data Analyst | Excel & BI Tools | Data-Driven Storytelling  
LinkedIn Profile: https://www.linkedin.com/in/fahiz-mohammed-68130421b

---

