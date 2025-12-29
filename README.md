# mysql-data-warehouse-baraaproject
Building a modern data warehouse with MySQL Workbench, including ETL processes, data cleaning, data standardiation, data analytics and advance data analysis.


# 🚀 Data Warehouse and Analytics Project
---

## 📌 **Welcome to the Data Warehouse and Analytics Project!**
This project is inspired by **Data with Baraa** and demonstrates a **comprehensive data warehousing, cleaning, standardization, and advanced analytics** solution. It follows **industry best practices** and is designed to provide **actionable business intelligence** for a bicycle business.

The project consolidates **6 tables from CRM (3) and ERP (3) sources**, applies **data manipulation and standardization**, and creates **3 consolidated tables** for:
- **Customer Info**
- **Product Info**
- **Sales Info**- 

![Table Connections](https://github.com/ojem1/mysql-data-warehouse-baraaproject/blob/main/docs/Table%20Connections.drawio.png?raw=true)


Additionally, the project includes **data visualization** using **Tableau/Power BI** to provide insights for data-driven decision-making.

---

## 🎯 **Project Overview**

### **Objective**
To build a **scalable data warehouse** and **analytics pipeline** that:
- Consolidates and cleans raw data from multiple sources.
- Standardizes data for consistency and accuracy.
- Provides **business intelligence insights** through visualizations and reports.

### **Specifications**
| **Aspect**               | **Details**                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| **Data Sources**         | 6 tables (3 CRM, 3 ERP)                                                     |
| **Data Cleaning**        | Deduplication, standardization, and transformation                          |
| **Data Warehouse**       | Consolidated tables for customer, product, and sales data                  |
| **Visualization Tools**  | Tableau/Power BI                                                            |
| **Database**             | MySQL                                                                       |
| **Language**             | SQL                                                                         |

---

## 🛠 **Methodology**

### **1. Building the Data Warehouse**
- **Data Extraction**: Pull raw data from CRM and ERP sources.
- **Data Cleaning**:
  - Remove duplicates using `ROW_NUMBER()` or self-joins.
  - Standardize formats (e.g., dates, country names, gender).
  - Handle missing or invalid values.
- **Data Transformation**:
  - Convert and standardize fields (e.g., `cst_marital_status`, `prd_line`).
  - Swap incorrect date ranges (e.g., `prd_start_dt` and `prd_end_dt`).
- **Data Loading**: Insert cleaned data into consolidated tables.

### **2. Business Intelligence: Analytics and Reporting**
- **Objective**: Provide insights into customer behavior, product performance, and sales trends.
- **Methodology**:
  - Use **Tableau/Power BI** to create dashboards.
  - Analyze trends (e.g., sales by region, customer demographics).
  - Generate reports for **data-driven decision-making**.
- **Benefits**:
  - Identify **top-selling products** and **customer segments**.
  - Track **sales trends** over time.
  - Optimize **inventory and marketing strategies**.

---

## 📊 **Data Visualization**
Here are some examples of the **insights** you can generate with this project:

### **Customer Demographics**
- Age distribution
- Gender breakdown
- Marital status trends

### **Sales Performance**
- Revenue by product category
- Sales trends over time
- Regional sales performance

### **Product Analysis**
- Top-selling products
- Product profitability
- Inventory turnover

---

## 💡 **Why This Project?**
As an **Electrical and Electronics Engineer** with a passion for **data analytics and data science**, I designed this project to:
- Showcase **end-to-end data warehousing** skills.
- Demonstrate **data cleaning, standardization, and analytics** best practices.
- Provide **actionable insights** for businesses (e.g., bicycle retailers).

This project is a **portfolio piece** but follows **real-world industry standards** to ensure scalability and reliability.

---

## 📜 **License**
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 🤝 **Connect With Me**
Hey, I am [Oje Ebhota](https://sites.google.com/view/oje-ebhota-data-portfolio/home)  and I love working with big data Let’s connect and discuss data, analytics, or anything tech-related!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/oje-ebhota-65592246/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/ojem1)
[![Email](https://img.shields.io/badge/Email-Contact-red)](mailto:ojem1@yahoo.com)

---

## 🙌 **Acknowledgments**
- **Data with Baraa** for the inspiration and tutorials.
- **Alex the Analayst** Also for his insightful tutorials
---

## 🚀 **Get Started**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/data-warehouse-analytics.git
