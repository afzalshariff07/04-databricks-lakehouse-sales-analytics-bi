# SQL Scripts

This folder contains Databricks SQL notebooks used for data exploration and dashboard preparation.

## Files

| File | Purpose |
|------|---------|
| `phase_1_data_exploration.dbquery.ipynb` | Exploratory analysis — schema inspection, KPIs, trends, segmentation |
| `phase_2_sales_dashboard_data.dbquery.ipynb` | Gold-layer CTE query powering the Sales Performance Dashboard |

## How to Use

1. Open your Databricks workspace
2. Import the `.ipynb` files via **File → Import**
3. Attach to a running cluster and execute cells sequentially
4. Ensure the `workspace.gold` schema is available with `fact_sales`, `dim_customers`, and `dim_products` tables

## Layer

Both scripts operate on the **Gold layer** (`workspace.gold`) — business-ready, pre-transformed data.
