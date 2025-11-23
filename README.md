# 📊 Vendor Performance Analysis Dashboard  


## 1️⃣ PROJECT TITLE / HEADLINE  
**Vendor Performance Intelligence Dashboard – A Data-Driven Approach to Optimize Procurement, Profitability & Vendor Management**

## 2️⃣ DESCRIPTION / PURPOSE  
- The **Vendor Performance Intelligence Dashboard** is a complete end-to-end data analytics solution designed to evaluate vendor performance using real-world, enterprise-style workflows. The project focuses on analyzing sales metrics, profit distribution, operational costs, and stock turnover efficiency to support data-driven procurement and vendor strategy.
- The dataset was initially available in **Excel format**, similar to how many organizations receive raw operational files. To make the project **industry-ready**, the Excel data was **ingested into a SQL Database**, which aligns with how real companies store and manage vendor and procurement information. Using **SQLAlchemy**, the data was extracted securely into Python for processing.
- Data cleaning, transformation, and analytical computations were performed using **Pandas** and **NumPy**, while **Matplotlib** was used for exploratory data visualization. After processing, the refined dataset was imported into **Power BI**, where an interactive dashboard was built to present insights clearly and visually.

**This solution enables organizations to:**
- Identify profitable vs low-performing vendors  
- Understand cost distributions (freight, taxes, margins)  
- Track stock turnover efficiency  
- Monitor order value patterns  
- Strengthen procurement decisions using data-backed evidence  

By combining database-driven data ingestion, Python-based analytics, and Power BI dashboards, this project delivers a realistic, scalable, and actionable vendor performance analysis platform suitable for modern supply chain and procurement environments.


## 3️⃣ TECH STACK  
![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?logo=plotly&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-ORM-FB0606?logo=databricks&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-Editor-007ACC?logo=visual-studio-code&logoColor=white)


## 4️⃣ DATA SOURCE  
- **Source Type:** Excel dataset (ingested into SQL Database)  
- **Ingestion Method:** The original Excel data was loaded into a SQL database to simulate a real-world production environment  
- **Access Method:** Queried using **SQLAlchemy** in Python  

### **Content Included in the Dataset:**  
- Vendor-wise sales information  
- Freight charges  
- Excise tax amounts  
- Order values  
- Profit-related metrics  
- Stock turnover data  

### **Key Fields:**  
- Vendor Name  
- Total Sales  
- Gross Profit  
- Freight Cost  
- Excise Tax  
- Average Order Value  
- Stock Turnover  

### **Why This Workflow? (Excel → SQL Database → Python → Power BI)**  
In most real business environments, operational data is **not processed directly from Excel**.  
Instead, organizations store procurement and vendor data in relational databases for:

- Faster querying  
- Better scalability  
- Centralized data management  
- Automation & reliability  

To follow this real-world standard, the Excel file was **ingested into a SQL database**, and the analysis pipeline was created using **SQLAlchemy + Pandas** for secure and efficient data extraction.

This approach makes the project:

- **Industry-aligned**  
- **Scalable for large datasets**  
- **Suitable for automation**  
- **More realistic for enterprise analytics**



## 5️⃣ FEATURES / HIGHLIGHTS  

### 💡 **A. Business Problem / Goal**  
Organizations often work with multiple vendors and need clarity on their contribution to revenue, profit, and operational efficiency. This project aims to solve key business questions such as:

- Which vendors generate the highest sales and profit?  
- How much do freight charges and excise taxes impact margins?  
- Are stock turnover rates meeting the expected operational targets?  
- How do average order values vary across different vendors?  
- Which vendors should be prioritized, monitored, or renegotiated with?  

The goal is to provide a **single source of truth** for vendor insights, enabling procurement and management teams to make faster and smarter decisions.

### 🧭 **B. Walkthrough of Key Visuals / Modules**  

#### **1. Sales Composition Breakdown (Freight, Profit, Tax)**  
A visual breakdown showing how total sales are distributed across freight charges, excise taxes, and gross profit.  
This helps identify cost-heavy areas and understand how much value each vendor truly contributes.

#### **2. KPI Indicators: Total Sales, Profit Margin %, Gross Profit**  
High-level KPIs summarizing financial performance.  
These indicators offer an instant snapshot of revenue flow, profitability strength, and overall business health.

#### **3. Vendor-Level Dynamic Filtering**  
Interactive filtering across vendors allows decision-makers to drill down and compare performance.  
Helps identify best-performing vendors, underperformers, and hidden patterns.

#### **4. Stock Turnover vs Target Gauge**  
A performance gauge showing whether stock turnover meets organizational targets.  
Useful for detecting slow-moving stock, inefficient vendors, or procurement delays.

#### **5. Top 5 Vendors by Sales**  
A ranking view that highlights the top revenue-generating vendors.  
Helps procurement teams focus on strategic vendors for partnership, negotiation, and planning.

#### **6. Total Sales & Average Order Value Chart**  
A combined bar (sales volume) and line (order value) chart that highlights vendor behavior:  
- High-volume vs low-volume vendors  
- Vendors delivering high-value orders  
- Patterns that influence ordering and negotiation strategies  

### 🚀 **C. Business Insights & Impact**  
From the analysis and Power BI dashboard, organizations can derive powerful insights:

- **Improved vendor negotiation** backed by profit and cost data  
- **Cost optimization** by identifying high freight/tax-heavy vendors  
- **Better inventory planning** using stock turnover analytics  
- **Enhanced procurement decisions** via vendor comparison and ranking  
- **Higher profitability** through data-driven vendor selection  
- **Clear visibility** of operational and financial performance  

Overall, this project delivers a **complete vendor intelligence system** that transforms scattered raw data into structured, scalable, and actionable insights—supporting stronger decision-making across procurement, finance, and supply chain teams.


## 6️⃣ SCREENSHOTS  

### 📌 Dashboard Previews  

![Vendor Performance Dashboard 1](https://github.com/raksharshetty67/Vendor_Performance_Analysis_Project/blob/main/Screenshot%202025-10-22%20163209.png)
  
![Vendor Performance Dashboard 2](https://github.com/raksharshetty67/Vendor_Performance_Analysis_Project/blob/main/Screenshot%202025-10-22%20163115.png)

---
