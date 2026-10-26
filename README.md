# USA Regional Sales Analysis

## Project Overview

**USA Regional Sales Analysis** is a sales analytics project built with **Power BI** and a supporting CSV dataset. It explores sales performance across U.S. regions, states, products, customers, and sales channels, with a focus on revenue, costs, profit, and profit margin.

The goal is to turn sales records into a clear business view that can support performance monitoring and better-informed decisions.

## Business Questions

This project can be used to explore questions such as:

- Which U.S. regions and states contribute most to sales and profit?
- How do revenue and profit change over time?
- Which products perform best by revenue, quantity, and profitability?
- How do Wholesale, Distributor, and Export channels compare?
- How do costs and profit margins vary across different parts of the business?

## Tools & Technologies

- **Power BI** — report building and data visualization
- **CSV / tabular data** — source dataset
- **Data analysis concepts** — regional comparison, time-based analysis, product and channel performance

## Dataset

The project dataset contains **64,104 rows and 21 columns**, covering order dates from **January 1, 2014, through February 28, 2018**.

Key fields include:

| Category | Fields |
|---|---|
| Order details | `order_number`, `order_date` |
| Customer and product | `customer_name`, `product_name`, `quantity`, `unit_price` |
| Sales and profitability | `revenue`, `cost`, `total_cost`, `profit`, `profit_margin_pct`, `budget` |
| Geography | `state`, `state_name`, `us_region`, `lat`, `lon` |
| Sales channel | `channel` |
| Time analysis | `order_month_name`, `order_month_num`, `order_month` |

**Data note:** The `budget` column has missing values in a large portion of the dataset. Treat budget-based comparisons carefully and validate the relevant records before drawing conclusions.

## Dashboard Analysis Areas

Use the Power BI report to explore the analysis areas represented in the dataset:

- **Sales performance:** revenue and quantity sold
- **Profitability:** profit, costs, and profit margin
- **Regional performance:** comparisons by U.S. region and state
- **Product performance:** comparisons across product categories/names
- **Sales channels:** Wholesale, Distributor, and Export
- **Time trends:** monthly and year-over-year performance

> The exact visuals, slicers, and measures depend on the included `.pbix` report. Open the report in Power BI Desktop to review the full interactive experience.

## Repository Contents

```text
USA-Regional-Sales-Analysis/
├── README.md
├── Sales_data(EDA Exported)(1).csv
└── SALES REPORT(1).pbix
```

If you rename the files before uploading them to GitHub, update the names in this section to match the repository.

## How to Use

1. Clone or download this repository.
2. Open `SALES REPORT(1).pbix` in **Power BI Desktop**.
3. If Power BI asks for the source file, point it to `Sales_data(EDA Exported)(1).csv`.
4. Refresh the data if required.
5. Explore the report using its available filters and visuals.

## Key Takeaways

This project demonstrates a practical analytics workflow: working with structured sales data, examining performance across geography and channels, and presenting business metrics in an interactive Power BI report.

For accurate conclusions, refer to the measures and visuals in the `.pbix` file rather than assuming results from the dataset schema alone.

## Skills Demonstrated

- Power BI reporting and visualization
- Exploratory sales data analysis
- KPI-oriented business analysis
- Regional and channel comparisons
- Time-based sales analysis
- Working with CSV data

## Future Improvements

- Add a dedicated data dictionary and document business definitions for each KPI.
- Validate and document the calculation used for profit margin.
- Investigate missing budget values before using budget-versus-actual comparisons.
- Add a concise findings section with verified dashboard insights.
- Include dashboard screenshots in the repository for quick review.

## Author

**Umesh Kumawat**  
Data Analytics Portfolio Project

---

*Note: Add screenshots of the actual Power BI report to a `screenshots/` folder and embed them here once they are available. Only publish findings and KPI values after confirming them in the report.*
