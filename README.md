# Vendor Performance Analysis Dashboard  

## 1️⃣ PROJECT TITLE / HEADLINE  
### **Vendor Performance Intelligence Dashboard – A Data-Driven Approach to Optimize Procurement, Profitability & Vendor Management**

## 2️⃣ DESCRIPTION / PURPOSE  

The **Vendor Performance Intelligence Dashboard** is an end-to-end enterprise-style analytics solution developed to evaluate **vendor performance**, **profitability**, and **operational efficiency** using a real-world data workflow.

This project bridges the gap between **procurement operations** and **data analytics**, providing business users with actionable insights into vendor contribution, cost structures, and stock efficiency.

**Key Purpose:**
- Measure and compare vendor profitability  
- Track cost distribution (freight, tax, and profit margins)  
- Monitor stock turnover and order values  
- Enable procurement teams to make **data-backed vendor decisions**  

**Data Workflow:**
1. The raw dataset, initially in **Excel format**, was **ingested into a SQL Database** to simulate enterprise data management.  
2. Using **SQLAlchemy**, the data was securely extracted into **Python** for analysis.  
3. Data transformation and analytics were handled using **Pandas** and **NumPy**, with **Matplotlib** providing early visual exploration.  
4. Finally, the cleaned dataset was connected to **Power BI**, where dynamic visuals were created to narrate the vendor performance story visually and interactively.

This multi-technology approach replicates a **realistic, industry-ready pipeline** for performance tracking and procurement optimization.


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

### **Source Information**
- **Source Type:** Excel file (simulating operational vendor data)  
- **Storage:** Imported into a **SQL database** for query-based analytics  
- **Access Layer:** Queried and extracted using **SQLAlchemy** ORM within Python  

### **Dataset Contents:**
- Vendor-wise **sales and cost data**  
- Freight and excise tax distribution  
- **Order value** and **profit** details  
- **Stock turnover** statistics for operational insight  

### **Key Fields:**  
- Vendor Name  
- Total Sales  
- Gross Profit  
- Freight Cost  
- Excise Tax  
- Average Order Value  
- Stock Turnover  

### **Why This Pipeline (Excel → SQL → Python → Power BI)?**
In real-world procurement analytics:
- Data rarely stays in Excel — it is stored in databases for **security and scalability**.  
- SQL ensures **centralized management** and **high-speed querying**.  
- Python offers **flexibility for transformation and analysis**.  
- Power BI delivers **dynamic visualization** for end-users.  

This structure ensures that the project is **enterprise-ready, automated, and scalable**, representing how actual procurement analytics systems are built in large organizations.

## 5️⃣ FEATURES / HIGHLIGHTS  

### **A. Business Problem / Goal**  

Enterprises often engage with multiple vendors but lack clear visibility into which ones drive profitability or inefficiency. This project addresses core questions like:  
- Which vendors contribute most to **revenue and profit**?  
- How do **freight and excise tax costs** affect overall margins?  
- Are **stock turnover rates** healthy or causing operational lags?  
- Which vendors have **the highest average order values**?  
- Who should be **rewarded, re-negotiated, or monitored** closely?  

The goal is to create a **centralized system** where management teams can easily measure vendor performance, track financial impact, and make informed procurement decisions.


### **B. Walkthrough of Key Visuals / Modules**

#### **1. Sales Composition Breakdown (Freight, Profit, Tax)**
A stacked visualization that breaks total sales into freight, tax, and profit components.  
**Purpose:** Quickly highlights cost-heavy vendors and identifies profitability bottlenecks.


#### **2. KPI Indicators (Total Sales, Profit Margin %, Gross Profit)**
Top-level KPI cards summarizing critical metrics across vendors.  
**Purpose:** Provides a quick snapshot of the organization’s overall vendor-related financial performance.

#### **3. Vendor-Level Dynamic Filtering**
Allows real-time filtering across multiple vendors to compare performance metrics interactively.  
**Purpose:** Enables quick comparison of vendors’ sales, profit, and cost profiles.

#### **4. Stock Turnover vs Target Gauge**
Displays actual stock turnover against company-defined targets.  
**Purpose:** Helps procurement managers spot underperforming vendors or slow-moving inventory.

#### **5. Top 5 Vendors by Sales**
A ranked bar chart showing top revenue-generating vendors.  
**Purpose:** Identifies key partners to strengthen relationships or expand contracts with.


#### **6. Total Sales & Average Order Value Chart**
Combines bar (sales) and line (average order value) to reveal vendor behavior patterns.  
**Purpose:** Differentiates high-volume vs. high-value vendors to inform purchasing strategy.

### **C. Business Insights & Impact**

**Strategic Insights Delivered:**
- **Profitability Optimization:** Identify vendors with poor margins due to excessive freight/tax costs  
- **Negotiation Power:** Strengthen talks with data-backed vendor performance metrics  
- **Procurement Efficiency:** Focus on high-turnover, high-margin vendors  
- **Inventory Management:** Detect and mitigate stock inefficiencies early  
- **Cost Control:** Optimize operational expenses through vendor-level analysis  

This solution creates a **360° view of vendor performance**, empowering business teams to drive profitability, improve negotiations, and enhance overall supply chain effectiveness.

## 6️⃣ SCREENSHOTS  

###  **Dashboard Previews**  

#### Vendor Performance Dashboard Overview  
![Vendor Performance Dashboard 1](https://github.com/raksharshetty67/Vendor_Performance_Analysis_Project/blob/main/Screenshot%202025-10-22%20163115.png)

#### Vendor Profitability and Stock Analysis  
![Vendor Performance Dashboard 2](https://github.com/raksharshetty67/Vendor_Performance_Analysis_Project/blob/main/Screenshot%202025-10-22%20163209.png)


## CONCLUSION  

The **Vendor Performance Analysis Dashboard** serves as a complete analytical ecosystem that combines **database engineering**, **data science**, and **business intelligence** to transform procurement decision-making.  

By moving beyond static Excel sheets to a **dynamic, automated analytics pipeline**, the solution empowers organizations to:
- Gain clear, actionable insights on vendor performance  
- Automate reporting and analytics workflows  
- Scale to larger datasets seamlessly  
- Improve vendor management strategies through data-backed intelligence  

This project exemplifies a **data-driven, industry-aligned** approach to vendor and procurement analytics—bridging the gap between raw data and strategic decision-making.

---
