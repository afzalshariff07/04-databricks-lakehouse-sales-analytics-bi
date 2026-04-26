# Databricks Dashboards

This folder contains exported dashboard definitions from Databricks.

## Dashboards

### Sales Performance Dashboard
- Revenue trends over time
- Category performance
- Country-level analysis
- KPI metrics (Sales, Orders, Customers, AOV)

<p align="center">
  <img src="images/Sales_Performance_Dashboard.jpg" width="800"/>
</p>

### Customer Insights Dashboard
- Customer segmentation (VIP, Regular, New)
- Customer behavior (recency, lifespan)
- Top customers by revenue
- Age group analysis

<p align="center">
  <img src="images/Customer_Insights_Dashboard.jpg" width="800"/>
</p>

## Folder Structure

```
databricks_dashboards/
├── images/     # Dashboard screenshots (JPG)
├── json/       # Exportable Databricks dashboard definitions (.lvdash.json)
└── pdf/        # PDF exports of dashboards
```

## Notes
- Dashboards are built using gold-layer datasets
- SQL transformations are available in the `/sql_scripts` folder
- JSON files can be imported directly into any Databricks workspace
