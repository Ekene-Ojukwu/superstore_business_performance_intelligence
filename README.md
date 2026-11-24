# SUPERSTORE: BUSINESS PERFORMANCE INTELLIGENCE

## Project Overview
An end-to-end retail business analytics project examining sales performance, profitability, product performance, customer behaviour, regional trends, discounts, returns, and shipping operations.

The project uses Excel, MySQL, and Power BI to investigate business performance, identify operational and profitability issues, and translate findings into actionable business insights.

## Business Questions
- How is the business performing in terms of sales and profitability?
- Which products, categories, and sub-categories contribute most to revenue and profit?
- Which products generate losses, and how are discounts associated with those losses?
- How does performance vary across customer segments and regions?
- Which customers generate high revenue but weak profitability?
- What patterns exist in product returns and shipping performance?
- How does sales and profitability performance change over time?

## Dataset Overview
- **Source:** Sample Superstore dataset
- **Reporting period:** January 2023 – December 2026
- **Transaction records:** 10,194
- **Original transaction columns:** 21
- **Cleaned transaction columns:** 26
- **Supporting datasets:** People and Returns

The transaction data is structured at product-line level, where each row represents an individual product line within an order.

## Tools Used
- **Microsoft Excel:** Data inspection, cleaning, preparation, and exploratory analysis.
- **MySQL:** Data validation, querying, aggregation, and business analysis.
- **Power BI:** Interactive business performance dashboard and visual reporting.

## Project Workflow
1. Inspected and assessed the original datasets.
2. Cleaned and prepared the transaction data.
3. Integrated supporting information from the People and Returns datasets.
4. Conducted exploratory and business-focused analysis in Excel.
5. Loaded the prepared data into MySQL and performed structured SQL analysis.
6. Developed a Power BI dashboard to communicate key findings.

## Key Findings
- Identified product ID and product name inconsistencies affecting 343 transaction records.
- Found that discount levels above 20% were associated with aggregate losses.
- Identified regional differences in profitability, with the Central region recording the weakest profit margin.
- Found customers generating substantial sales despite weak or negative profitability.
- Examined return-record patterns and shipping performance at order level.

## Dashboard Preview
![Superstore Power BI Dashboard](images/Superstore_Dashboard_Preview.jpg)

## Business Recommendations
- Review high-discount transactions and strengthen discount approval controls.
- Investigate loss-making products and reassess their pricing and discount strategies.
- Examine regional and category-level profitability before making resource allocation decisions.
- Review high-revenue, low-profitability customer accounts.
- Investigate product data inconsistencies to improve reporting reliability.

## Limitations
- The analysis identifies associations between discounts and profitability; it does not establish causation.
- Return analysis is based on available return records and should not be interpreted as a confirmed refund or financial-loss measure.
- Small differences exist between platform-level financial totals due to rounding during CSV preparation. Each platform's reported figures are retained as calculated.

## Project Structure
```text
SUPERSTORE_BUSINESS_PERFORMANCE_INTELLIGENCE/
│
├── excel/
├── sql/
├── powerbi/
├── images/
│   └── Superstore_Dashboard_Preview.jpg
│
└── README.md

Project Deliverables

- Excel workbook containing data preparation and analysis.
- SQL script containing database setup and analytical queries.
- Power BI dashboard (.pbix).
- Dashboard preview image.

Project Focus: Turning retail transaction data into meaningful business intelligence.