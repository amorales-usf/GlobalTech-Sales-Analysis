# 📊 GlobalTech Quarterly Sales Analysis (Pandas Project)

## 📌 Overview
This project is a **data analysis application built with Python and Pandas** that analyzes quarterly sales data for GlobalTech. It demonstrates core data analysis skills including:

- Data loading and exploration
- Data cleaning and missing value analysis
- Filtering and querying datasets
- Aggregation and grouping
- Business insights and reporting

The dataset simulates real-world sales transactions across multiple regions, products, and categories.

---

## 🧰 Technologies Used
- Python 3
- Pandas
- NumPy

---

## 📂 Dataset Description

The dataset contains the following columns:

| Column        | Description |
|--------------|------------|
| Date         | Transaction date (YYYY-MM-DD) |
| Region       | Sales region (North America, Europe, Asia, Latin America) |
| Store        | Store ID |
| Category     | Product category |
| Product      | Product name |
| Units        | Number of units sold |
| Unit_Price   | Price per unit (USD) |
| Total_Sales  | Total transaction value (USD) |
| Promotion    | Whether item was on promotion (Yes/No) |

⚠️ Some values are missing (`NaN`) to simulate real-world data issues.

---

## 🚀 Features

### 🔍 Data Exploration
- View dataset structure (`head`, `info`, `shape`)
- Summary statistics using `describe()`

### 📊 Data Analysis
- Total units sold and revenue
- Average unit price
- Sales by region and category
- Best-selling product identification

### 🎯 Filtering & Querying
- Regional filtering (e.g., North America)
- High-volume sales detection
- Promotion-based filtering
- Date-based filtering (e.g., February sales)

### 📈 Aggregations
- Revenue by region (sorted)
- Average units sold per category
- Product-level revenue contributions (% of total)

### 🏷️ Promotion Analysis
- Compare promoted vs non-promoted sales:
  - Average sales
  - Total revenue

### ⚠️ Data Quality Checks
- Missing value counts per column
- Missing value percentages
- Data quality reporting

### 📌 Business Insights
- Top-performing categories by region
- Average pricing by category
- Key recommendations for business improvement

---

## 📊 Key Variables (for grading/reference)

| Variable | Description |
|--------|------------|
| `sales_df` | Main DataFrame |
| `total_units` | Total units sold |
| `total_revenue` | Total revenue |
| `avg_unit_price` | Average unit price |
| `na_sales` | North America sales |
| `high_volume_sales` | Sales with Units > 20 |
| `phonex_promo` | PhoneX sales on promotion |
| `feb_sales` | February sales |
| `best_product` | Highest revenue product |
| `sales_by_region` | Revenue grouped by region |
| `avg_units_by_category` | Avg units per category |
| `promo_comparison` | Promotion performance metrics |
| `missing_counts` | Missing values per column |
| `missing_percentages` | % missing values |

---

## 📈 Example Outputs

### Overall Performance
```

* Total Revenue: $XXX,XXX.XX
* Total Units Sold: XXX
* Average Sale Value: $XXX.XX

```

### Regional Performance
```

North America: $XXX,XXX.XX
Europe: $XXX,XXX.XX
...

```

### Promotion Effectiveness
```

* Promoted Items Avg Sale: $XXX.XX
* Non-Promoted Items Avg Sale: $XXX.XX
* Revenue from Promotions: $XXX,XXX.XX

````

---

## 🧠 Concepts Demonstrated

- Pandas DataFrame operations
- Boolean indexing and filtering
- GroupBy operations
- Aggregation functions (`sum`, `mean`)
- Handling missing data (`isna`)
- Data transformation and reshaping
- Basic business analytics

---

## ▶️ How to Run

1. Ensure Python is installed (3.x recommended)
2. Install dependencies:
   ```bash
   pip install pandas numpy
````

3. Run the script:

   ```bash
   python main.py
   ```

---

## 💡 Key Insights

* Promotions can significantly impact revenue
* Regional performance varies and should guide strategy
* Missing data can affect analysis accuracy
* Certain product categories outperform others consistently

---

## 🔮 Future Improvements

* Visualizations (matplotlib / seaborn)
* Interactive dashboard (Streamlit or Power BI)
* Real CSV file integration
* Advanced analytics (trend forecasting)

---

## 📄 License

This project is for educational purposes only.

---

## 👨‍💻 Author

Developed as part of a Module 9 assignment on data analysis with Pandas.

