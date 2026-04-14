# Retail Analytics Portfolio

A collection of SQL queries and Power BI dashboards built on retail 
sales data, developed as part of a structured 8-week self-study program 
targeting Business Analyst roles in the retail and apparel industry.

---

## Tools & Technologies
- **PostgreSQL** — database and query engine
- **DBeaver** — SQL client
- **Power BI Desktop** — dashboards and visualisations
- **Dataset** — Superstore Sales Dataset (Kaggle)

---

## Repository Structure

### Week 1 — SELECT, WHERE, ORDER BY, DISTINCT
| File | Description |
|---|---|
| `01_product_catalogue.sql` | Products filtered by category, sorted by sales |
| `02_regional_orders.sql` | Orders filtered by region and year |
| `03_unique_categories.sql` | Distinct category and sub-category list |
| `04_top20_orders.sql` | Top 20 highest-value orders |
| `05_profit_filter.sql` | Orders filtered by profit conditions |

### Week 2 — GROUP BY, Aggregates, HAVING
| File | Description |
|---|---|
| `06_sales_by_category.sql` | Total revenue and units by category |
| `07_aov_by_region.sql` | Average order value by region |
| `08_high_revenue_categories.sql` | Categories filtered by revenue threshold |
| `09_margin_by_subcategory.sql` | Profit margin broken down by sub-category |
| `10_monthly_sales_trend.sql` | Monthly revenue trend using DATE_TRUNC |

### Week 3 — JOINs
| File | Description |
|---|---|
| `11_orders_with_products.sql` | Orders joined to products table |
| `12_dead_stock.sql` | Products with no orders using LEFT JOIN |
| `13_full_sales_detail.sql` | Three-table join across orders, products, customers |
| `14_top10_customers.sql` | Top 10 customers by lifetime spend |

### Week 4 — CTEs & Synthesis
| File | Description |
|---|---|
| `15_category_summary_cte.sql` | Category summary rewritten with CTE |
| `16_above_avg_customers.sql` | Customers above average spend using subquery |
| `17_portfolio_analysis.sql` | Full synthesis query combining all techniques |

### Week 5 — Window Functions
| File | Description |
|---|---|
| `18_product_rank_by_category.sql` | Products ranked by revenue within category |
| `19_top5_per_category.sql` | Top 5 products per category using ROW_NUMBER() |
| `20_running_total.sql` | Cumulative sales running total |
| `21_mom_comparison.sql` | Month-over-month comparison using LAG() |
| `22_moving_average.sql` | 3-month moving average of sales |

### Weeks 6–8 — Power BI
| Deliverable | Description |
|---|---|
| `superstore_model.pbix` | Star schema data model with Power Query cleaning |
| `kpi_dashboard.pbix` | DAX measures, calendar table, YTD and YoY KPIs |
| `portfolio_dashboard.pbix` | Full 3-page capstone dashboard with drill-through |

---

## Status
🟡 In progress — Week 1 complete

---

## About
BCom graduate (UBC Sauder, 2023) building toward Business Analyst roles 
in retail and apparel. Background in accounting and business technology 
management with experience in process improvement and data analysis.
