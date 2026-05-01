# GlobalTech Quarterly Sales Analysis

## Module 9 Assignment: Introduction to Data Analysis with Pandas

A Python-based data analysis project focused on **quarterly sales performance for GlobalTech**, a multinational consumer electronics retailer.

This project demonstrates foundational **data analysis techniques using Pandas**, including:

- Data loading and exploration
- Data filtering
- Aggregation and grouping
- Missing value detection
- Business performance analysis
- Revenue reporting

---

## Project Overview

This project analyzes simulated **Q1 2024 sales data** from GlobalTech across multiple international regions.

The analysis evaluates:

- Revenue performance
- Regional sales distribution
- Product performance
- Promotion effectiveness
- Category trends
- Data quality issues

The goal is to extract actionable business insights using Pandas for data manipulation and analysis.

---

## Objectives

This project introduces core data analysis workflows in Python.

### Key Tasks Completed

### 1. Load and Explore Data
- Load sales data from a simulated CSV file
- Preview dataset structure
- Inspect DataFrame information
- Generate descriptive statistics

---

### 2. Perform Basic Analysis
Calculate:

- Total units sold
- Total revenue
- Average unit price

---

### 3. Filter Data
Extract subsets including:

- North America sales
- High-volume transactions
- Promotional PhoneX sales
- February 2024 sales

---

### 4. Advanced Analysis
Identify:

- Highest-performing product
- Revenue by region
- Average units sold by category
- Promotion impact on sales

---

### 5. Detect Missing Values
Analyze:

- Missing value counts
- Missing value percentages
- Data quality concerns

---

### 6. Generate Business Insights
Produce:

- Regional performance summaries
- Product revenue contribution analysis
- Category performance metrics
- Strategic business recommendations

---

## Technologies Used

- **Python 3**
- **Pandas**
- **NumPy**

---

## Dataset Information

The simulated dataset contains sales records with the following fields:

| Column | Description |
|--------|------------|
| Date | Date of sale |
| Region | Sales region |
| Store | Store identifier |
| Category | Product category |
| Product | Product name |
| Units | Units sold |
| Unit_Price | Price per unit |
| Total_Sales | Revenue generated |
| Promotion | Promotion status |

---

## Regions Included

- North America
- Europe
- Asia
- Latin America

---

## Product Categories

- Smartphones
- Computers
- Audio
- Accessories
- Wearables

---

## Analysis Performed

## Sales Performance Metrics

The script calculates:

### Total Revenue
Overall revenue generated across all transactions.

---

### Total Units Sold
Total product units sold during Q1 2024.

---

### Average Unit Price
Mean selling price across all products.

---

## Regional Analysis

Revenue is grouped and ranked by region to identify strongest-performing markets.

**Purpose:**  
Understand geographic sales performance.

---

## Product Performance Analysis

The analysis identifies:

- Best-selling products
- Revenue contribution by product
- Percentage share of total sales

---

## Category Analysis

For each category, the script calculates:

- Average units sold
- Average product pricing

---

## Promotion Effectiveness Analysis

Compares promoted vs non-promoted products based on:

- Average sale value
- Total promotional revenue

**Purpose:**  
Evaluate the effectiveness of sales promotions.

---

## Missing Data Analysis

The project identifies incomplete records in:

- Unit pricing
- Units sold

This helps assess data quality and reporting reliability.

---

## Key Business Insights

The analysis highlights important performance trends.

### Promotion Impact
Promotional products generate strong revenue performance.

---

### Smartphone Dominance
Smartphones, especially **PhoneX**, are the primary revenue drivers.

---

### Regional Opportunities
Latin America presents growth opportunities through stronger promotional campaigns.

---

### Data Quality Concerns
Missing transaction values indicate the need for stricter reporting validation.

---

## Business Recommendations

### 1. Expand Promotions
Increase promotional campaigns in underperforming regions.

---

### 2. Prioritize Smartphone Inventory
Maintain strong stock levels for top-performing smartphone products.

---

### 3. Improve Data Validation
Implement store-level validation rules to eliminate missing transaction data.

---

## Project Structure

```text
globaltech-sales-analysis/
│
├── globaltech_sales_analysis.py
├── README.md
```

---

## Core Variables Generated

| Variable | Description |
|---------|-------------|
| `sales_df` | Main DataFrame |
| `total_units` | Total units sold |
| `total_revenue` | Total revenue |
| `avg_unit_price` | Average unit price |
| `na_sales` | North America sales |
| `high_volume_sales` | High-volume transactions |
| `phonex_promo` | PhoneX promotional sales |
| `feb_sales` | February sales |
| `best_product` | Highest revenue product |
| `sales_by_region` | Revenue by region |
| `avg_units_by_category` | Category unit averages |
| `promo_comparison` | Promotion metrics |
| `missing_counts` | Missing value counts |

---

## Example Output

```text
GLOBALTECH Q1 2024 SALES ANALYSIS REPORT

Overall Performance:
- Total Revenue: $XXX,XXX.XX
- Total Units Sold: XXX
- Average Sale Value: $XXX.XX

Regional Performance:
North America: $XX,XXX.XX
Europe: $XX,XXX.XX
Asia: $XX,XXX.XX
Latin America: $XX,XXX.XX
```

---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/globaltech-sales-analysis.git
cd globaltech-sales-analysis
```

---

### Install Dependencies

```bash
pip install pandas numpy
```

---

### Run the Script

```bash
python globaltech_sales_analysis.py
```

---

## Learning Outcomes

This project demonstrates practical experience with:

- DataFrame manipulation
- Filtering and querying
- GroupBy operations
- Descriptive statistics
- Missing value analysis
- Business intelligence reporting

---

## Author

**Jennifer**

Module 9 Assignment  
Introduction to Data Analysis with Pandas

---

## License

This project is intended for academic and educational purposes.
