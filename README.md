# Customer Shopping Behavior Analysis

A complete data analytics project that analyzes customer shopping behavior using **Python, MySQL, SQL, and Power BI**. The project demonstrates the end-to-end data analytics workflow, including data cleaning, database integration, SQL analysis, and dashboard visualization.

---

## Project Overview

This project analyzes customer shopping behavior to uncover valuable business insights such as:

- Customer demographics
- Shopping trends
- Purchase behavior
- Product category performance
- Payment method preferences
- Revenue distribution

The objective is to transform raw customer data into meaningful insights that can support business decision-making.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- MySQL
- SQLAlchemy
- MySQL Workbench
- Power BI
- Jupyter Notebook
- VS Code

---

## Project Workflow

```
Raw CSV Dataset
        │
        ▼
Data Cleaning (Python + Pandas)
        │
        ▼
Clean Dataset
        │
        ▼
Load Data into MySQL
        │
        ▼
SQL Analysis
        │
        ▼
Power BI Dashboard
        │
        ▼
Business Insights
```

---

## Project Structure

```
Customer_Analysis/
│
├── data/
│   ├── raw_data_customer_shopping_behavior.csv
│
├── notebook/
│   └── data_cleaning.ipynb
│
├── sql/
│   └── business_queries.sql
│
├── powerbi/
│   └── Customer_Analysis.pbix
│
├── images/
│
└── README.md
```

---

## Data Cleaning

The dataset was cleaned using Pandas by performing the following operations:

- Removed duplicate records
- Checked and handled missing values
- Corrected data types
- Verified column consistency
- Prepared the dataset for database import

---

## MySQL Integration

After cleaning, the dataset was imported into MySQL using SQLAlchemy.

```python
df.to_sql(
    "customer",
    engine,
    if_exists="replace",
    index=False
)
```

The cleaned dataset was then stored in MySQL for SQL-based analysis.

---

## SQL Analysis

Example business questions answered:

- Which product categories generate the highest revenue?
- What is the average purchase amount by gender?
- Which age groups spend the most?
- Which payment methods are most popular?
- What are the highest-selling product categories?
- Which customer segments contribute the most revenue?

---

## Power BI Dashboard

The dashboard includes:

- Total Revenue KPI
- Total Customers
- Gender Distribution
- Purchase Amount Analysis
- Product Category Analysis
- Payment Method Analysis
- Customer Age Distribution
- Interactive Filters & Slicers

---

## Key Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis
- Database Integration
- SQL Query Writing
- Data Visualization
- Dashboard Development
- Business Insight Generation

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/customer-shopping-behavior-analysis.git
```

Create a virtual environment

```bash
python -m venv .venv
```

Activate the environment

```bash
.venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Future Improvements

- Add advanced customer segmentation
- Build predictive sales models
- Perform RFM analysis
- Create customer lifetime value analysis
- Deploy dashboard online

---

## Author

**Shivam**

LinkedIn: *Add your LinkedIn profile*

GitHub: *Add your GitHub profile*
this is a project i am making 
