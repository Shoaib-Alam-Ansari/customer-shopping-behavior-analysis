# Customer Activity & Trends Analysis Insights

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)
![MySQL](https://img.shields.io/badge/MySQL-8.0+-orange.svg)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

## 📋 Project Overview

A complete end-to-end data analytics project that transforms raw customer transaction data into actionable business insights. This project demonstrates the full data analytics workflow: data cleaning, exploratory analysis, SQL querying, and interactive dashboard creation.

## 🎯 Key Business Questions Answered

- Which customer segments generate the highest revenue?
- What products drive sales in each category?
- How do discounts and promotions impact purchase behavior?
- Which seasons perform best for different product categories?
- What are the spending patterns across age groups and genders?

## 📊 Dataset Overview

| Metric | Value |
|--------|-------|
| **Total Records** | 3,900 transactions |
| **Total Features** | 18 columns |
| **Customer Age Range** | 18-70 years |
| **Purchase Range** | $20 - $100 |

### Features Included

| Category | Features |
|----------|----------|
| **Customer Info** | Age, Gender, Location, Subscription Status |
| **Product Details** | Item Purchased, Category, Size, Color, Season |
| **Transaction Data** | Purchase Amount, Discount Applied, Promo Code Used, Shipping Type |
| **Customer Behavior** | Previous Purchases, Purchase Frequency, Review Rating |

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Data cleaning, preprocessing, EDA |
| **Pandas/NumPy** | Data manipulation |
| **Matplotlib/Seaborn** | Data visualization |
| **MySQL** | Data storage and querying |
| **Power BI** | Interactive dashboard |
| **Jupyter Notebook** | Development environment |

## 📁 Project Structure
```
customer-behavior-analysis/
│
├── data/
│ ├── raw/
│ │ └── customer_shopping_behavior.csv
│
├── notebooks/
│ ├── data_cleaning.ipynb
│ └── sql.ipynb
│
├── dashboard/
│ └── powerbi_dashboard.pbix
│
├── reports/
│ └── Project_Report.pdf
│
├── src/
│ ├── main.py
│
├── logs/
│ └── pipeline.log
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

## 🔄 Data Pipeline Workflow

### Key Pipeline Features:
- ✅ Automated logging for error tracking
- ✅ Configurable file paths
- ✅ Modular functions for reusability
- ✅ Error handling at each stage
- ✅ Database integration

## 📈 Key Findings

### Revenue by Category
- **Clothing** dominates with **$104,264** (44.7% of total revenue)
- **Accessories** follows at **$74,200** (31.8%)
- **Footwear** and **Outerwear** contribute remaining 23.5%

### Customer Segmentation
| Segment | Count | % of Total |
|---------|-------|------------|
| Loyal | 3,116 | 79.9% |
| Returning | 701 | 18.0% |
| New | 83 | 2.1% |

### Seasonal Performance
- **Fall** is peak season: $60,018 revenue
- **Summer** is slowest: $55,777 revenue
- Clothing is top category in ALL seasons

### Gender Analysis
- Male customers contribute **68%** of total revenue
- Male:Female spending ratio is approximately **2.1:1** across all categories

## 💻 Getting Started

### Prerequisites
- Python 3.9+
- MySQL 8.0+
- Power BI Desktop (for dashboard)

## 📊 Dashboard Preview
  ![Executive Overview](images/)

