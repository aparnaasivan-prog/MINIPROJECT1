# 🌍 MNC Global Analysis – Power BI

## 📊 Mini Project 1 | Global Business Intelligence Dashboard

A Power BI business intelligence project designed to analyze multinational corporation (MNC) performance across **sales, profitability, employees, companies, products, countries, and industries**.

The project demonstrates the complete data analytics workflow, including **data cleaning, transformation, data modeling, DAX calculations, and interactive dashboard development**.

---

## 🎯 Project Objective

The objective of this project is to analyze global MNC operations and identify meaningful business trends and performance indicators.

The dataset provides a comprehensive foundation for:

- Analyzing sales and profitability
- Evaluating company performance
- Understanding employee distribution and salary trends
- Comparing regional and country-level performance
- Analyzing product and industry performance
- Identifying business opportunities and areas requiring improvement
- Supporting data-driven business decisions

---

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| **Microsoft Excel** | Data preparation and initial cleaning |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Analytical calculations and measures |
| **Microsoft Power BI** | Data modeling, visualization and dashboard development |
| **GitHub** | Project documentation and portfolio |

---

## 🧹 Data Cleaning & Transformation

The raw dataset contained various data quality issues. The following data preparation steps were performed:

- Removed duplicate records
- Handled missing and blank values
- Standardized inconsistent categorical values
- Handled `N/A`, `NULL`, `UNKNOWN` and invalid entries
- Validated employee and transaction IDs
- Corrected date formats and invalid dates
- Standardized numerical data types
- Prepared the data for analytical modeling
- Created a structured data model by establishing relationships between tables

These steps improved **data consistency, accuracy, and reliability** for dashboard analysis.

---

## 🧩 Data Modeling

A structured relational data model was developed in Power BI to connect the major business entities.

The model supports analysis across:

- Employees
- Companies
- Sales / Transactions
- Products
- Countries
- Departments
- Industries

Relationships between tables were established to enable efficient cross-filtering and interactive dashboard analysis.

---

## 📐 Key DAX Measures

The project includes analytical measures such as:

- **Total Sales**
- **Total Profit**
- **Average Profit**
- **Profit Margin**
- **YTD Sales**
- **YTD Profit**
- **Transaction Count**
- **Employee Count**
- **Average Salary**
- **Sales Target Achievement**

These measures were used to create meaningful KPIs and visualizations.

---

# 📈 Dashboard Overview

The MNC Global Analysis dashboard provides a consolidated view of global business performance.

### 1. 🌐 MNC Global Analysis

This section provides an executive-level overview of:

- Total Employees
- Total Companies
- Total Sales
- Total Profit
- Top-performing Companies
- Revenue by Country
- Revenue by Industry
- Global business performance

### 2. 👥 Employee & Company Analysis

This section focuses on workforce and organizational analysis:

- Employee distribution
- Employee gender analysis
- Department-wise employee distribution
- Job role analysis
- Average salary by department
- Country-wise employee distribution
- Company performance
- Global payroll analysis

### 3. 💰 Sales & Profitability Analysis

This section analyzes financial and transactional performance:

- Total Sales
- Total Profit
- Quantity Sold
- Profit Margin
- Loss Transactions
- Sales by Company
- Profit by Company
- Payment Method Analysis
- Monthly sales and profit trends
- Country-level profitability

---

# 🔍 Key Insights

### 🌎 Global Reach
The MNC operations cover major global regions, including **North America, Europe, Asia, and Australia**, demonstrating broad international business operations.

### 🏆 Top Performing Companies
**Samsung, Wipro, and Sony** are among the leading companies based on sales and profitability.

### 💵 Financial Performance
The analysis reports approximately:

- **Total Sales:** 2.48B
- **Total Profit:** 119.77M

The monthly analysis indicates an overall positive growth pattern.

### 👨‍💼 Workforce Strength
The dataset contains approximately **10K employees**, with an average salary of approximately **136K**.

The workforce is distributed across multiple departments, job roles, companies, and countries.

### ☁️ Product Performance
**Cloud Services and Analytics Platforms** represent important revenue-generating product categories and provide opportunities for further business expansion.

---

# 💡 Business Recommendations

Based on the dashboard analysis, the following recommendations were identified:

### 1. 🌏 Improve Underperforming Regions
Develop targeted strategies for lower-performing regions such as **Australia and Canada** to improve sales and profitability.

### 2. 📉 Reduce Loss Transactions
Analyze the causes of loss transactions and improve:

- Product quality
- Customer engagement
- Pricing strategies
- Transaction monitoring

### 3. 👥 Invest in Employees
Strengthen employee training, development, and retention programs to improve workforce productivity and long-term performance.

### 4. ☁️ Expand High-Profit Products
Increase investment in high-performing product categories such as:

- Analytics
- Cloud Services

This can help improve overall profitability and market growth.

---

# 📊 Business Value

The dashboard helps stakeholders:

- Monitor overall business performance
- Identify high-performing companies
- Compare regional performance
- Track sales and profitability trends
- Understand workforce distribution
- Identify loss-making transactions
- Evaluate product performance
- Make data-driven strategic decisions

---

# 📁 Project Structure

```text
MNC-Global-Analysis/
│
├── README.md
│
├── Dataset/
│   └── MNC_Global_Dataset.xlsx
│
├── PowerBI/
│   └── MNC_Global_Analysis.pbix
│
├── Dashboard/
│   ├── Executive_Overview.png
│   ├── Sales_Analysis.png
│   └── Employee_Analysis.png
│
└── Documentation/
    └── Project_Summary.pdf
