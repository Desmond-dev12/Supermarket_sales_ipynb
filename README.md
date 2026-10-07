# 🛒 Supermarket Sales Analysis Notebook

This repository contains a Jupyter notebook for cleaning, exploring, and analyzing a supermarket sales dataset. The notebook focuses on turning messy retail data into structured insights that support business decisions about sales performance, customer behavior, product lines, and payment trends.

## 📌 Project Goal

The notebook is designed to help answer practical retail questions such as:

- Which branch generates the highest sales?
- Which product line contributes the most revenue?
- What payment methods are most common?
- How do customer type and gender affect purchasing behavior?
- What does the sales data reveal about missing values, inconsistent formatting, and data quality issues?
- Which product categories and customer segments need more attention?

## 📊 Dataset Overview

The dataset used in this notebook is a supermarket sales file with fields such as:

- Invoice ID
- Branch
- City
- Customer type
- Gender
- Product line
- Unit price
- Quantity
- Tax
- Total
- Date
- Payment method
- COGS
- Gross margin
- Gross income
- Rating

The data was intentionally messy and required cleaning before analysis.

## 🧹 Notebook Workflow

The notebook includes steps to:

- upload the source CSV file
- inspect the dataset shape and structure
- view the first and last rows
- review column names
- standardize column names
- clean spacing and formatting issues
- rename fields for consistency
- check data types and missing values
- prepare the dataset for exploratory data analysis

## 🧠 Tools Used

- Python
- Pandas
- Jupyter Notebook / Google Colab
- Data cleaning and exploratory analysis techniques

## 📁 Repository Structure

```text
Supermarket_sales_ipynb/
├── supermarket_sale.ipynb
├── README.md
└── supermarket_messy.csv   (uploaded when running the notebook)
```

## ✅ Requirements

To run the notebook locally, install:

```bash
pip install jupyter pandas numpy matplotlib seaborn
```

If using Google Colab, the notebook can run directly without additional setup.

## ▶️ How to Use

### Option 1: Jupyter Notebook

1. Open the notebook in Jupyter.
2. Upload or place the supermarket CSV file in the same folder.
3. Run all cells sequentially.

### Option 2: Google Colab

1. Open the notebook in Colab.
2. Upload the CSV file when prompted.
3. Run the notebook cells in order.

## 📈 Business Value

This notebook supports retail and business analysis by helping users:

- clean messy sales data
- understand data quality issues
- prepare a dataset for reporting and dashboards
- identify sales patterns and operational insights
- build a foundation for future BI or dashboard projects

## 👤 Author

Desmond Pimpong

## 📬 Contact

- GitHub: https://github.com/Desmond-dev12
- LinkedIn: https://linkedin.com/in/desmond-pimpong-563899433

## 📄 License

This project is available for educational and portfolio use.
