# 📦 Supply Chain & Inventory Analysis Dashboard

## 📌 Project Overview

This project focuses on analyzing inventory and supply chain performance for a manufacturing company managing stock across multiple warehouses. The company faces operational challenges such as stock shortages leading to delayed deliveries and overstock situations increasing holding costs.

The solution uses **Power BI**, structured data modelling, and DAX calculations to provide an interactive dashboard that supports inventory decision-making.

https://app.powerbi.com/groups/me/reports/0228d6f1-1bfa-4fb5-9085-c14c0b03b1b2/0560271c53c669b9bbf1?experience=power-bi

---

## 🚨 Business Problem

The organization currently manages inventory manually, leading to:

- Frequent stock-outs causing delivery delays  
- Excess stock increasing storage and holding costs  
- Inefficient reorder planning  
- Limited visibility into inventory turnover  

This project introduces analytical monitoring to improve operational efficiency.

---

## 🎯 Project Objectives

The dashboard was designed to:

- Monitor stock availability  
- Identify low-stock and overstocked products  
- Optimize reorder decisions  
- Detect slow-moving inventory  
- Improve inventory turnover  
- Provide warehouse-level stock risk visibility  
- Support business decision-making through analytics  

---

## 📊 Dataset Description

The project uses four structured datasets designed using dimensional modelling.

### 🛒 Products Dataset
Contains:
- Product ID  
- Category  
- Reorder Point  

---

### 🏭 Warehouses Dataset
Contains:
- Warehouse ID  
- Location  
- Storage Capacity  

---

### 📦 Inventory Dataset
Contains:
- Product Stock Levels  
- Warehouse Distribution  
- Maximum Stock Limits  

---

### 💰 Sales Dataset
Contains:
- Sales Transactions  
- Units Sold  
- Revenue  
- Sales Date  

---

## 🧩 Data Model

The project follows a **Star Schema** model.

### Dimension Tables
- Products  
- Warehouses  
- Date Table  

### Fact Tables
- Inventory  
- Sales  

Relationships were created using:

- Product ID  
- Warehouse ID  
- Date  

---

## 📈 Key Performance Indicators (KPIs)

The dashboard tracks the following metrics:

- Total Stock Availability  
- Inventory Turnover Rate  
- Low Stock Product Count  
- Excess Stock Product Count  
- Slow Moving Inventory Detection  
- Replenishment Requirement Indicator  
- Warehouse Stock Risk Distribution  

---

## 📊 Dashboard Features

### 🟦 Inventory Overview Dashboard
Provides a summary of inventory health including:

- Total Stock  
- Turnover Ratio  
- Stock Status Distribution  
- Stock vs Sales Trends  

---

### 🟥 Risk & Replenishment Dashboard
Highlights:

- Warehouses facing stock shortages  
- Products requiring immediate restocking  
- Slow-moving product identification  

---

### 🟩 Performance Analytics Dashboard
Analyzes:

- Category-level sales demand  
- Monthly inventory movement  
- Inventory efficiency trends  

---

## 🔍 Analytical Insights Generated

The dashboard helps identify:

- Warehouses experiencing frequent shortages  
- Product categories showing overstock risks  
- Slow-moving inventory increasing holding costs  
- Monthly and seasonal demand trends  
- Products requiring urgent replenishment  

---

## 🛠 Tools & Technologies Used

- **Power BI** – Dashboard Development  
- **DAX** – KPI Calculations  
- **Power Query** – Data Transformation  
- **Dimensional Data Modelling** – Performance Optimization  

---

## 💡 Business Impact

This solution enables organizations to:

- Reduce stock-out risks  
- Minimize holding costs  
- Improve demand forecasting  
- Enhance supply chain efficiency  
- Support data-driven decision-making  

---

## 🚀 Future Enhancements

Potential improvements include:

- Integration with ERP or real-time inventory systems  
- Machine learning-based demand forecasting  
- Automated reorder recommendation engine  
- Supplier performance analytics  

---
