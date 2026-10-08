# 🛒 Supermarket Sales Data Cleaning Notebook

This repository contains a Jupyter notebook for cleaning and preparing a messy supermarket sales dataset for analysis and reporting. The notebook focuses on data quality assessment, standardization, and preparation—not visualization.

## 📌 Project Goal

Transform raw, messy retail data into a clean, structured dataset ready for:
- Business Intelligence dashboards
- Statistical analysis
- Exploratory Data Analysis (EDA)
- Reporting and presentations

## 🎯 What This Notebook Does

### Data Cleaning Tasks
- **Upload XLSV file** from Google Colab file system
- **Inspect data structure** – shape, head, tail, and column overview
- **Standardize column names** – convert to lowercase, strip whitespace, replace spaces with underscores
- **Rename fields** for clarity and consistency (e.g., `unit_price_(ghs)` → `unit_price`)
- **Check data types** – identify numeric vs. text columns
- **Identify missing values** – detect NULL/NaN entries per column
- **Data quality assessment** – spot inconsistencies and formatting issues

### Issues Found & Fixed
The notebook reveals common data quality problems:
- Missing values in `branch`, `customer_type`, `gender`, `total`, and `rating` columns
- Inconsistent date formats (mixed `3/24/2019`, `March 21, 2019` formats)
- Unit price stored as text with "GHS" currency symbol (needs conversion to float)
- Trailing/leading spaces in column names
- Inconsistent column name capitalization

## 📊 Dataset Overview

**Size:** 205 rows × 16 columns

**Fields:**
- `invoice_id` – Transaction identifier
- `branch` – Store location (A, B, C)
- `city` – City name
- `customer_type` – Member or Normal
- `gender` – Male or Female
- `product_line` – Category of goods
- `unit_price` – Price per unit (currently as text with currency)
- `quantity` – Items purchased
- `tax` – 5% tax amount
- `total` – Transaction total
- `date` – Purchase date
- `payment` – Cash, Credit card, or E-wallet
- `cogs` – Cost of goods sold
- `gross_margin` – Margin percentage
- `gross_income` – Profit amount
- `rating` – Customer satisfaction (1-10 scale)

## 🧹 Notebook Workflow

```
1. Upload CSV File
   ↓
2. Load with Pandas
   ↓
3. Inspect Data (shape, head, tail, columns)
   ↓
4. Clean Column Names (lowercase, strip, replace spaces)
   ↓
5. Rename Fields (standardize naming)
   ↓
6. Check Data Types & Missing Values
   ↓
7. Document Data Quality Issues
   ↓
8. Ready for Analysis!
```

## ⚠️ Important Notes

This notebook is **data preparation only**. It does NOT include:
- ❌ Charts or visualizations
- ❌ Statistical analysis
- ❌ EDA (Exploratory Data Analysis)
- ❌ Predictive modeling


## 🛠️ Tools Used

- Python 3
- Pandas (data manipulation)
- Jupyter Notebook / Google Colab
- NumPy (optional, for further processing)

## 📁 Repository Structure

```text
Supermarket_sales_ipynb/
├── supermarket_sale.ipynb          # Main cleaning notebook
├── README.md                         # This file
└── supermarket_messy.csv            # Input data (upload when running)
```

## ✅ Requirements

### Local Jupyter Setup
```bash
pip install jupyter pandas numpy
```

### Google Colab
No setup needed. Simply upload the CSV when the notebook asks.

## ▶️ How to Use

### Option 1: Run in Google Colab
1. Open the notebook link in Colab
2. Click "Run all" or execute cells sequentially
3. Upload `supermarket_messy.csv` when prompted
4. Review the cleaned data output

### Option 2: Run Locally with Jupyter
1. Clone or download this repository
2. Place the CSV file in the same folder
3. Open the notebook: `jupyter notebook supermarket_sale.ipynb`
4. Run cells in order

## 📈 Expected Output

After running the notebook, you'll have:
- A cleaned DataFrame with standardized column names
- Missing value report per column
- Data type confirmation
- Ready-to-export CSV for dashboards or analysis tools

## 💡 Business Value

This notebook supports data teams by:
- Reducing manual data cleaning time
- Ensuring consistent naming conventions
- Identifying data quality gaps
- Creating a reusable template for similar datasets
- Preparing data for automated reporting pipelines

## 🚀 Next Steps

After cleaning, consider:
1. **Create a Streamlit Dashboard** – Use the Supermarket Sales Web App repo
2. **Run EDA** – Generate statistics and visualizations
3. **Build BI Reports** – Connect to Tableau/Power BI
4. **Export for Analysis** – Use cleaned CSV for statistical tools (R, Python, SQL)

## 👤 Author

Desmond Pimpong

## 📬 Contact

- GitHub: https://github.com/Desmond-dev12
- LinkedIn: https://linkedin.com/in/desmond-pimpong-563899433

## 🔗 Related Projects

- **[Supermarket Sales Web App](https://github.com/Desmond-dev12/Supermarket-sales-Wep-App)** – Interactive Streamlit dashboard with visualizations
  

## 📄 License

This project is available for educational and portfolio use.
