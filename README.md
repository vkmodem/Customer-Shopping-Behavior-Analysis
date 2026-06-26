# Customer-Shopping-Behavior-Analysis
This end-to-end analytics project investigates 3,900 retail transactions using Python, MySQL, and Power BI. It establishes a $59.76 average spend baseline dominated by Clothing. Crucially, deep-dive SQL uncovers a major bottleneck: 73% of shoppers sit outside the loyalty subscription ecosystem. 

# Retail Customer Shopping Behavior Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge&logo=mysql)
![Power%20BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter)

---

# 🛍️ Retail Customer Shopping Behavior Analysis

An end-to-end data analytics project designed to transform raw retail transaction data into actionable business intelligence through **Python**, **MySQL**, and **Power BI**.

This repository demonstrates a complete analytics workflow—from data ingestion and feature engineering to SQL-based business analysis and executive-level reporting—providing insights into customer demographics, purchasing behavior, loyalty segmentation, pricing dynamics, and merchandising opportunities.

---

# 📌 Executive Summary

Retail organizations generate massive volumes of transactional data, yet many struggle to convert that information into strategic decisions. This project analyzes **3,900 customer transactions** to uncover patterns in customer spending, product demand, promotional effectiveness, subscription adoption, and lifecycle behavior.

The analysis revealed an **average customer spend of \$59.76 per transaction** and an **average review rating of 3.75/5**, indicating generally positive customer sentiment. One of the most significant findings was that approximately **73% of customers are non-subscribers**, highlighting a substantial opportunity for customer retention and recurring revenue programs. Additional insights identified opportunities in merchandising optimization, discount-driven premium spending behavior, customer loyalty development, and inventory alignment for dominant product categories.

---

# 🎯 Business Objectives

The project was designed to answer key commercial questions:

- Which customer segments generate the highest revenue?
- How does discounting influence premium spending behavior?
- What purchasing patterns exist across demographic groups?
- Which product categories drive the largest share of sales?
- How effective are current subscription and loyalty initiatives?
- What customer lifecycle segments require targeted CRM strategies?
- How can inventory planning be aligned with customer demand?

---

# 🗂️ Repository Structure

```text
Retail-Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.csv
│   └── Raw transactional dataset containing customer purchase records.
│
├── Customer Shopping behaviour.ipynb
│   └── Python analytics notebook performing:
│       • Exploratory Data Analysis (EDA)
│       • Missing value treatment
│       • Median imputation of review ratings
│       • Feature engineering
│       • Data transformation
│       • MySQL database loading via SQLAlchemy
│
├── updated_data.csv
│   └── Cleaned and transformed dataset generated from the notebook.
│
├── Customer_shopping_behaviour sql.sql
│   └── Collection of SQL business queries answering:
│       • Revenue analysis
│       • Premium customer behavior
│       • Shipping logistics
│       • Loyalty segmentation
│       • Customer lifecycle analytics
│
├── Customer behaviour Dashboard.pbix
│   └── Interactive Power BI dashboard containing:
│       • Category performance
│       • Subscription penetration
│       • Customer insights
│       • Executive KPIs
│
├── Customer_Behavior_Analysis_Report.pdf
│   └── Formal executive report summarizing methodology,
│       findings, recommendations, and business impact.
│
└── README.md
    └── Project documentation.
```

---

# 🔄 Analytics Pipeline Architecture

The project follows a modern analytics engineering workflow:

```text
┌───────────────────────────┐
│ 1. Data Ingestion         │
│ & Feature Engineering     │
│        (Python)           │
└─────────────┬─────────────┘
              │
              ▼
┌───────────────────────────┐
│ 2. Relational Analytics   │
│        (MySQL)            │
└─────────────┬─────────────┘
              │
              ▼
┌───────────────────────────┐
│ 3. Executive Dashboarding │
│       (Power BI)          │
└─────────────┬─────────────┘
              │
              ▼
┌───────────────────────────┐
│ 4. Strategic Reporting    │
│      & Recommendations    │
└───────────────────────────┘
```

## Phase 1 — Ingestion & Feature Engineering (Python)

The Jupyter Notebook performs:

- Raw CSV ingestion using Pandas
- Data quality assessment
- Missing review rating treatment using median imputation
- Creation of customer age-group quartiles
- Purchase frequency standardization into days
- Removal of redundant promotional attributes
- Export of cleaned dataset
- Loading transformed data into MySQL using SQLAlchemy

### Technologies

- Python
- Pandas
- NumPy
- SQLAlchemy
- PyMySQL
- Jupyter Notebook

---

## Phase 2 — Relational Querying (MySQL)

The transformed dataset is loaded into MySQL for analytical querying.

Key SQL analyses include:

- Revenue contribution by gender
- Premium customer spending identification
- Discount threshold impact analysis
- Shipping performance insights
- Customer lifecycle classification
- New vs Returning vs Loyal customer segmentation

---

## Phase 3 — Macro Visualization (Power BI)

Power BI provides executive-level visibility into:

- Revenue distribution
- Product category performance
- Customer demographics
- Subscription penetration
- Purchase behavior patterns
- KPI monitoring

---

## Phase 4 — Executive Synthesis

Insights from Python, SQL, and Power BI are consolidated into a publication-ready executive report containing:

- Findings
- Strategic recommendations
- Business implications
- Growth opportunities
- CRM optimization opportunities

---

# 💡 Key Strategic Insights

## 📉 Loyalty Conversion Bottleneck

- Approximately **73% of customers are non-subscribers**
- Only **27% participate in subscription-based engagement**
- Indicates substantial opportunity for retention programs and recurring revenue models

### Recommendation

Introduce:

- Tiered loyalty programs
- Personalized offers
- Subscription incentives
- CRM-driven retention campaigns

---

## 🛒 Dynamic Cart Threshold Opportunities

Analysis suggests opportunities to increase Average Order Value (AOV) through:

- Free-shipping thresholds
- Bundle discounts
- Cross-sell recommendations
- Dynamic promotional triggers

### Expected Outcome

- Higher basket sizes
- Improved customer retention
- Increased revenue per transaction

---

## 👕 Inventory Alignment for Dominant Categories

The **Clothing** category emerged as the strongest demand driver.

### Recommendation

- Prioritize inventory replenishment
- Improve demand forecasting
- Optimize assortment planning
- Align promotional spend with top-performing categories

### Business Impact

- Reduced stock-outs
- Improved inventory turnover
- Higher sales conversion

---

## 👥 Customer Lifecycle Segmentation

Customers were classified into:

| Segment | Description |
|----------|-------------|
| New | Single-purchase customers |
| Returning | Repeat purchasers |
| Loyal | High-frequency repeat customers |

This segmentation enables targeted CRM and retention strategies.

---

## ⭐ Customer Satisfaction Signals

- Average Review Rating: **3.75 / 5**
- Indicates generally positive customer experiences
- Opportunities remain for service quality optimization and review score improvement

---

# 📊 Dashboard Demo

Add a screenshot of your Power BI dashboard to the repository and update the image path below.

```markdown
![Dashboard Preview](path/to/image.png)
```

Example:

```markdown
![Dashboard Preview](assets/dashboard-preview.png)
```

### Preview Placeholder

![Dashboard Preview](path/to/image.png)

---

# 🛠️ Technology Stack

| Layer | Tools |
|---------|---------|
| Data Processing | Python, Pandas, NumPy |
| Notebook Environment | Jupyter |
| Database | MySQL |
| Data Loading | SQLAlchemy, PyMySQL |
| Visualization | Power BI |
| Reporting | PDF Executive Report |

---

# 🚀 Step-by-Step Local Setup

## 1. Clone Repository

```bash
git clone https://github.com/your-username/retail-customer-shopping-behavior-analysis.git

cd retail-customer-shopping-behavior-analysis
```

---

## 2. Create Virtual Environment (Optional)

### Windows

```bash
python -m venv venv

venv\Scripts\activate
```

### Mac/Linux

```bash
python3 -m venv venv

source venv/bin/activate
```

---

## 3. Install Dependencies

```bash
pip install pandas numpy sqlalchemy pymysql pyodbc jupyter
```

---

## 4. Create MySQL Database

Open MySQL and execute:

```sql
CREATE DATABASE retail_customer_analysis;
```

---

## 5. Update Database Connection

Inside:

```text
Customer Shopping behaviour.ipynb
```

Update your SQLAlchemy connection string:

```python
from sqlalchemy import create_engine

engine = create_engine(
    "mysql+pymysql://username:password@localhost/retail_customer_analysis"
)
```

---

## 6. Run the Notebook

Launch Jupyter:

```bash
jupyter notebook
```

Open:

```text
Customer Shopping behaviour.ipynb
```

Run all notebook cells.

Outputs generated:

```text
updated_data.csv
```

and

```text
MySQL database tables
```

---

## 7. Execute SQL Analysis

Open:

```text
Customer_shopping_behaviour sql.sql
```

Execute queries using:

- MySQL Workbench
- DBeaver
- Azure Data Studio
- VS Code SQL Extensions

---

## 8. Open Power BI Dashboard

Launch:

```text
Customer behaviour Dashboard.pbix
```

Refresh data sources if required.

---

## 9. Review Executive Report

Open:

```text
Customer_Behavior_Analysis_Report.pdf
```

for the complete business analysis and recommendations.

---

# 📈 Deliverables

✅ Data Cleaning & Transformation

✅ Feature Engineering

✅ MySQL Data Warehousing

✅ SQL Business Analysis

✅ Customer Segmentation

✅ Power BI Dashboard

✅ Executive Reporting

✅ End-to-End Analytics Pipeline

---

# 🤝 Contact

If you would like to discuss this project, collaborate on analytics initiatives, or explore data engineering and business intelligence opportunities, feel free to connect.

**Author:** *Your Name*  
**Role:** Data Analytics & Engineering Professional  
**LinkedIn:** https://linkedin.com/in/your-profile  
**GitHub:** https://github.com/your-username

---

## ⭐ Support

If you found this project useful, consider giving the repository a **Star ⭐**.

It helps others discover the project and supports continued development of analytics and data engineering portfolio work.

---

**Transforming retail transaction data into actionable business intelligence through analytics engineering, SQL, and executive storytelling.**
