# Fathalla Supermarket — Sales Performance Analysis

An end-to-end data analysis project built in Excel, covering data cleaning, 
pivot tables, pivot charts, an interactive dashboard, and a business insights report.

## 📌 Project Overview
This project analyzes sales data from Fathalla Supermarket, a multi-branch 
retail chain operating 52 branches — including regular supermarkets, "Beitna" 
convenience branches, and "Phone Shop" electronics outlets.

The dataset contains 410,516 rows of item-level sales data across all branches, 
with no date or cost fields (branch-level sales snapshot).

## 🎯 Objectives
- Identify top-performing branches by sales value and quantity
- Analyze category and product-level sales contribution
- Compare best-selling products by value vs. by quantity
- Detect pricing pattern differences across branch types
- Build an interactive dashboard for data exploration

## 🗂️ Dataset
- **Rows:** 410,516 (410,495 after cleaning)
- **Columns:** Branch Code, Branch Name, Department Code, Department, Main 
  Group, Subgroup, Item Code, Barcode, Item Name, Net Sales Quantity, Net Sales Value
- **Limitations:** No date/time field, no cost/profit field

 ## 📌 Note on Data
The raw dataset used in this project belongs to Fathalla Supermarket and is 
not publicly shared due to business confidentiality. This repository showcases 
the analysis process, dashboard, and insights derived from the data. 

## 🧹 Data Cleaning
- Removed 21 duplicate rows (based on Branch Code + Item Code + Barcode)
- Validated and corrected data types (Number vs. Currency)
- Checked for blank and zero-value records

## 📊 Analysis & Dashboard
Built using Excel Pivot Tables and Pivot Charts:
- Branch performance (Top 20 by Sales Value & Quantity)
- Category breakdown (Main Group / Subgroup)
- Top 10 products by Value and by Quantity
- Average Value per Item by Branch (pricing pattern analysis)
- Interactive Slicers for Branch and Department filtering

## 💡 Key Insights
- One category ("Canned Goods") drives a disproportionately large share of total revenue
- Top products by value are not always the top products by quantity
- "Beitna" and "Phone Shop" branches show significantly higher average item 
  values than regular supermarket branches, reflecting a different product mix

## 🛠️ Tools Used
- Microsoft Excel (Pivot Tables, Pivot Charts, Slicers, Calculated Fields)
- Canva (PDF Report Design)


## 👤 Author
Mohamed — [www.linkedin.com/in/mohamed-el-sayed-abo-ismail-]
