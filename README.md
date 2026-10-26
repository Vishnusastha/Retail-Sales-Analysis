# Retail-Sales-Analysis

An end-to-end sales analysis using **Python (Pandas)**, **MySQL/XAMPP**, and **Power BI**. The project explores sales, profit, quantity, product categories, customer segments, regions, discounts, and time trends.

## Business question

How can retail sales data show where the business is performing well and where profitability needs further investigation?

## Dataset

The dataset contains **10,194 sales-line records** and **21 columns**, covering order and shipping dates, customers, products, segments, regions, sales, quantity, discount, and profit. It contains no age, gender, review, subscription, or sales-channel fields.

## Tools and workflow

1. **Python/Pandas:** inspect, prepare, validate, and analyze the data.
2. **MySQL/XAMPP:** store the prepared records.
3. **Power BI:** explore KPIs and trends in an interactive dashboard.

## Key findings

- **Total sales:** $2,326,534.35
- **Total profit:** $292,296.81
- **Overall profit margin:** 12.56% (total profit ÷ total sales)
- **Quantity sold:** 38,654 units
- No missing values or fully duplicated rows were found; `Row ID` is unique.

**Profit by category:** Technology $146,543.38; Office Supplies $126,023.44; Furniture $19,730.00.

**Profit by region:** West $110,798.82; East $94,883.26; South $46,749.43; Central $39,865.31.

These are descriptive findings. They show where profit is concentrated, but do not explain why differences occur.

## Power BI dashboard

The dashboard includes KPI cards, a year slicer, and views of monthly quantity, category sales, segment profit margin, monthly sales, regional profit, and quarterly profit.

> The visual titled “Sales & Profit Month by Month” appears to show sales only. Add the profit measure or rename the chart.

Add your `.pbix` file and a dashboard screenshot to this repository to let visitors explore the report.

## Run the project

1. Add the Python notebook and dataset (if redistribution is permitted).
2. Install the libraries used by the notebook, such as `pandas` and the appropriate CSV/Excel reader.
3. Run the notebook from top to bottom.
4. Start MySQL in XAMPP and import the prepared data.
5. Open the `.pbix` file in Power BI Desktop and check the data connection and refresh settings.

Do not commit database passwords or other credentials. If you cannot share the dataset, add its source and access instructions instead. Confirm Power BI refresh settings before describing the report as live-connected.

## Repository contents

Add your actual project files under folders such as `notebooks/`, `data/`, `sql/`, `powerbi/`, and `images/`. Update this section once those files are in the repository.

## Limitations

The dataset does not support demographic or sales-channel conclusions. Category and regional profit totals are not profit margins. Investigate discounts and unusually high or negative profit records at product and transaction level before making business decisions. Compare the same complete time periods when reviewing trends.

## Author

**[K J Vishnu Sastha]**
