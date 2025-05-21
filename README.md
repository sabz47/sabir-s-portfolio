# sabir-s-portfolio
Analytics Portfolio

# 🧃 Beverage Company Data Analysis (Excel | Power Query | Power Pivot)

## 📊 Project Overview

This project involves analyzing structured data for a beverage company using **Microsoft Excel**. The goal was to extract meaningful insights from the company's operations using **Power Query**, **Power Pivot**, and **data modeling** — all within Excel.

Although there was **no direct sales amount available**, we focused on **transaction trends**, **return patterns**, and **product-customer relationships** to derive performance metrics and business insights.

---

## 🧱 Dataset & Structure

The dataset consists of the following tables:

- `Customers`: Customer demographics and segmentation
- `Products`: Product details (categories, sizes, variants)
- `Transactions`: Records of purchases (no amount, only units/occurrence)
- `Returns`: Product returns data
- `Store` & `Region` Lookup (if applicable)
- `Calendar`: Date table for time-based analysis

---

## 🛠 Key Activities

### 1. **Data Cleaning with Power Query**
- Loaded raw data into Excel via **Power Query**.
- Cleaned and prepared each table:
  - Removed nulls and blanks
  - Ensured proper data types
  - Normalized columns and merged related fields
- Applied basic transformation logic (e.g., conditional columns, filtering)

### 2. **Data Modeling in Power Pivot**
- Created a **star schema** in Power Pivot.
- Defined relationships between:
  - Transactions ↔ Customers
  - Transactions ↔ Products
  - Returns ↔ Products
  - Calendar ↔ Transactions / Returns
- Handled **indirect relationships**, e.g., Region via Store (if applicable).

### 3. **DAX Measures and Analysis**
- Created calculated columns and measures to track:
  - Number of transactions per product/category
  - Return rate = Returns / Transactions
  - Product popularity trends
  - Customer activity (repeat transactions, most active segments)
  - Time-based trends (monthly, quarterly)

---

## 📈 Insights Generated

- Identified top-selling products by **number of transactions**.
- Highlighted products with **highest return rates**.
- Analyzed customer behavior — frequent buyers, inactive users.
- Time-series analysis to detect seasonality in purchases and returns.
- Detected potential product quality issues via return frequency.

---

## 💻 Tools Used

- Microsoft Excel
  - **Power Query** for data extraction and cleaning
  - **Power Pivot** for building relationships and writing DAX
  - **PivotTables and Charts** for reporting

---

## 📁 Folder Structure

