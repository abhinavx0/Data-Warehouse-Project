# Data Warehouse and Analytics
Welcome to the **Data Warehouse and Analytics Project** repository!
This project guides you through the end-to-end process of building a modern data warehouse and turning raw data into meaningful insights. It's designed as a hands-on portfolio project based on real-world data engineering and analytics practices.

---
## Data Architechture.
The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:

<img width="856" height="600" alt="Image" src="https://github.com/user-attachments/assets/ece01402-0f90-4f58-bbdd-ce732672fb39" />

1. **Bronze Layer**: Stores raw data exactly as received from source CSV files. Data is ingested into the **MySQL database** without transformation.
2. **Silver Layer**: Performs data cleansing, standardization, and normalization to prepare the data for reliable analysis and downstream use.
3. **Gold Layer**: Contains business-ready data organized in a **star schema**, optimized for reporting, dashboards, and advanced analytics.

---
## Data Integration Model.

<img width="792" height="617" alt="Image" src="https://github.com/user-attachments/assets/11a9b7a6-2f79-44a1-b678-56600c061c44" />

---
## Data Flow Diagram.

<img width="741" height="369" alt="Image" src="https://github.com/user-attachments/assets/a827c33a-468d-45b3-a524-71007e92281d" />

---
## Data Marts(Star Schema).

<img width="792" height="472" alt="Image" src="https://github.com/user-attachments/assets/364b3d79-e49c-4f2a-83c7-b7211a50b3e8" />

---
## 📖 Project Overview

This project covers the full lifecycle of building a data warehouse and delivering business insights:

1. **Data Architecture**: Designing a modern warehouse using the Medallion Architecture with **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from CSV sources into a structured warehouse.
3. **Data Modeling**: Creating optimized fact and dimension tables for fast and flexible analysis.
4. **Analytics & Reporting**: Writing SQL queries and building dashboards to uncover key business insights.

🎯 This repository is aiming to demonstrate skills in:

* SQL Development
* Data Architecture
* Data Engineering
* ETL Pipeline Design
* Data Modeling
* Data Analytics

---

## 🚀 Project Requirements

### 🏗️ Data Warehouse Development (Data Engineering)

#### 🎯 Objective

Design and implement a modern data warehouse using **MySQL** to consolidate and organize sales data for analytical reporting and better decision-making.

#### 📋 Key Specifications

* **Data Sources**: Ingest data from two primary sources — **ERP** and **CRM**, both provided as CSV files.
* **Data Cleansing**: Address and fix data quality issues before loading to ensure accuracy and consistency.
* **Data Integration**: Merge ERP and CRM data into a unified, analysis-friendly schema.
* **Project Scope**: Work with the most recent snapshot of data; historical tracking is not required.
* **Documentation**: Provide clear and comprehensive documentation of the data model to support analysts and business users.

---

### 📊 BI & Analytics (Data Analysis)

#### 🎯 Objective

Develop SQL-based insights to support strategic decision-making by analyzing:

* **Customer Patterns & Segmentation**
* **Product-Level Performance**
* **Sales Trends & Seasonal Insights**

The resulting metrics will provide actionable intelligence for stakeholders, supporting both operational and strategic goals.

## 🔍 Exploratory Data Analysis (EDA)

All SQL queries used for exploration and KPI generation:  
👉 :contentReference[oaicite:0]{index=0}  

---

## 📈 Key Business Questions Answered

### 🛍️ Product Analysis
- Which products generate the highest revenue?
- Which products are underperforming?
- How does product performance change over time?

### 👤 Customer Analysis
- Who are the top customers by revenue?
- What is the customer distribution by country and gender?
- How many customers are actively purchasing?

### 📊 Sales Analysis
- What are total sales, orders, and quantities?
- What are sales trends over time?
- Which regions contribute most to revenue?

---

## 📌 KPIs (Key Performance Indicators)

### 💰 Core Metrics
- Total Sales  
- Total Orders  
- Total Quantity Sold  
- Average Selling Price  
- Total Customers  
- Active Customers  

### 📦 Product KPIs
- Revenue by Category  
- Top 5 & Bottom 5 Products  
- Average Cost per Category  
- Product Sales Distribution  

### 👥 Customer KPIs
- Revenue per Customer  
- Customer Segmentation (VIP / Regular / New)  
- Demographics (Age, Country, Gender)  

### ⏱️ Time-Based KPIs
- Monthly & Yearly Sales Trends  
- Order Lifecycle Analysis  
- Recency (Last Purchase Behavior)  

---

## 🧠 Advanced EDA & Insights

Detailed EDA with segmentation and trends:  
👉 :contentReference[oaicite:1]{index=1}  

### 🔹 Product Insights
- Identified high vs low performing products  
- Tracked revenue trends and growth patterns  
- Used moving averages for trend clarity  

### 🔹 Customer Insights
- Identified VIP customers driving major revenue  
- Segmented users based on behavior  
- Analyzed purchase frequency and spending  

### 🔹 Sales Trends
- Detected seasonality  
- Compared year-over-year performance  
- Built cumulative and trend metrics  

---
## 🚀 What Makes This Project Strong

- End-to-end pipeline (Data → Insights)  
- Strong business KPI understanding  
- Real-world analytics use cases  
- Structured problem-solving  

---

## 🔮 Future Improvements

- Build Power BI / Tableau dashboards  
- Add Customer Lifetime Value (CLV)  
- Add churn prediction  
- Include profit & margin analysis  

---
## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi there! I'm Abhinav Om, currently a 3rd-year undergraduate student at the Indian Institute of Information Technology (IIIT) Ranchi.
I'm passionate about turning raw data into meaningful insights and am actively working toward a career as a Data Analyst or Business Analyst.

I enjoy solving real-world problems through data, exploring trends, and drawing actionable conclusions that drive decision-making.
I'm constantly improving my skills in SQL, Excel, Python, and data visualization tools like Power BI and Tableau.
With hands-on project experience in data warehousing and analytics, I'm building a strong foundation for a future in analytics and consulting.
