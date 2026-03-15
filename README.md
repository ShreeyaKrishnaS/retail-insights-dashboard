# Retail Insights & Performance Dashboard

Power BI dashboard analyzing 98K+ Instacart transactions to surface actionable sales insights.

## What it does
- Identifies top and worst-selling products across categories
- Calculates Average Order Value ($29.00) and 6-week revenue trends
- Tracks weekly best/worst sellers and category-level performance
- Built with Advanced SQL for data extraction and Python (Pandas) for transformation

## Files
| File | Description |
|------|-------------|
| `Retail_transaction.ipynb` | Main analysis and data processing notebook |
| `IIS_project.ipynb` | Additional analysis notebook |
| `Instakart_sales_rev.pbix` | Power BI dashboard file |
| `products.csv` | Products reference data |
| `aisles.csv` | Aisle categories data |
| `departments.csv` | Department categories data |
| `sample_data.csv` | Sample dataset for quick reference |
| `summary_sales.csv` | Aggregated sales summary |
| `weekly_best_sellers.csv` | Weekly top performing products |
| `weekly_worst_sellers.csv` | Weekly lowest performing products |
| `weekly_category_sales.csv` | Sales breakdown by category |

## Data Source
Full dataset (order_products_prior.csv, orders.csv, order_products__train.csv) excluded due to size.  
Available on Kaggle: [Instacart Market Basket Analysis](https://www.kaggle.com/competitions/instacart-market-basket-analysis/data)

## Tools Used
- Python (Pandas) — data cleaning and transformation
- Power BI + DAX — dashboard and measures
- SQL — data querying and aggregation
- Excel — data exploration

## Key Results
- Analyzed 98,000+ transactions to identify top/worst
