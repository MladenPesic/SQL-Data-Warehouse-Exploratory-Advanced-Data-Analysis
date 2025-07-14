# SQL Data Warehouse – Exploratory and Advanced Analytics

## Project Overview

This repository extends the **[SQL Data Warehouse Project](https://github.com/MladenPesic/SQL_Data_Warehouse_Project)** by performing **Exploratory Data Analysis (EDA)** and **Advanced Business Analytics** directly on the **Gold Layer** of the star schema.

The goal was to derive **actionable insights for business decision-making using pure SQL**.

---

## Objectives

### Exploratory Data Analysis (EDA)

- Explore the **database structure and metadata**
- Calculate core KPIs:
  - Total Sales
  - Total Orders
  - Total Customers
  - Total Products
- Analyze distributions:
  - Geography
  - Gender
  - Product Categories
- Identify top-performing and underperforming products/customers
- Generate business health reports using magnitude and ranking analysis

---

### Advanced Analytics

- Perform time-series analysis (monthly/annual trends, seasonality)
- Calculate cumulative metrics (running totals, moving averages)
- Conduct Year-over-Year performance comparisons
- Segment customers into:
  - VIP
  - Regular
  - New
- Segment products into:
  - High-Performer
  - Mid-Range
  - Low-Performer
- Build Customer and Product Reports for ongoing operational use


| **Analysis**                | **Findings**                                                   | **Business Impact**                                         |
| --------------------------- | -------------------------------------------------------------- | ----------------------------------------------------------- |
| **Customer Segmentation**   | Identified VIP customers with high spending & long tenure      | Enables targeted loyalty programs and retention strategies  |
| **Product Performance**     | Detected 80/20 sales rule – few products generate most revenue | Focus inventory and marketing on top products               |
| **Low-Performer Detection** | Found products and customers contributing minimally to revenue | Consider product phase-out, or targeted reactivation offers |
| **Sales Trends**            | Identified monthly/annual growth patterns and seasonality      | Helps in forecasting and financial planning                 |
| **Category Contribution**   | Measured each product category's share of total sales          | Guides category management and marketing focus              |
| **Customer Behavior**       | Segmented customers by age, geography, and order behavior      | Enables personalized marketing and CRM initiatives          |

## Conclusion

This analysis demonstrates how a well-designed SQL Data Warehouse can serve as a powerful foundation for business intelligence. By leveraging advanced SQL techniques on the gold layer, the project provides valuable insights that support strategic decision-making and operational efficiency. This work not only highlights key performance indicators but also segments customers and products to identify growth opportunities and risks. Overall, it underscores the importance of integrating data warehousing with analytics to drive data-informed business outcomes.
