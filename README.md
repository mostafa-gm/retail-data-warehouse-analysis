# 📊 Retail Data Analytics 

## 🎯 Project Overview
A comprehensive SQL-based business intelligence analysis of a retail data warehouse, demonstrating end-to-end analytical capabilities from data exploration to executive reporting. This project simulates real-world BI tasks using a **star schema** design with 14 distinct analytical techniques.

## 📈 Business Context
Analyzes customer purchasing behavior, product performance, and sales trends to derive actionable business insights for a retail organization. The analysis answers critical business questions across multiple domains including customer segmentation, product optimization, and revenue forecasting.

## 🛠️ Technologies Used
- **SQL:** T-SQL (SQL Server)
- **Database Design:** Star Schema (Fact & Dimension Tables)
- **Analytical Techniques:** 14 different SQL analysis methods
- **Version Control:** Git & GitHub
- **Documentation:** Markdown

- ### Star Schema Design
<img width="791" height="811" alt="schema" src="https://github.com/user-attachments/assets/a8d17f8c-c7d2-46dc-b4d3-3d7c9b512bfe" />


### Table Details
- **`gold.dim_customers`**: 10+ customer attributes with `customer_key` as PRIMARY KEY
- **`gold.dim_products`**: 10+ product attributes with `product_key` as PRIMARY KEY  
- **`gold.fact_sales`**: Transactional data with FOREIGN KEY constraints to both dimensions


- ## 📁 Analysis Pipeline
| # | Analysis Type | Purpose | Key SQL Functions |
|---|--------------|---------|-------------------|
| 1 | **Database Exploration** | Understand structure & metadata | `INFORMATION_SCHEMA`, `DISTINCT` |
| 2 | **Dimensions Exploration** | Profile dimension tables | `DISTINCT`, `ORDER BY` |
| 3 | **Date Range Exploration** | Temporal boundaries analysis | `MIN()`, `MAX()`, `DATEDIFF()` |
| 4 | **Measures Exploration** | Aggregate key metrics | `SUM()`, `AVG()`, `COUNT()` |
| 5 | **Magnitude Analysis** | Data distribution across dimensions | `GROUP BY`, aggregate functions |
| 6 | **Ranking Analysis** | Identify top/bottom performers | `RANK()`, `DENSE_RANK()`, `ROW_NUMBER()` |
| 7 | **Change Over Time** | Trend & seasonality analysis | `DATEPART()`, window functions |
| 8 | **Cumulative Analysis** | Running totals & moving averages | `SUM() OVER()`, `AVG() OVER()` |
| 9 | **Performance Analysis** | YoY/MoM comparisons | `LAG()`, window functions |
| 10| **Data Segmentation** | Customer/product categorization | `CASE`, `GROUP BY` |
| 11| **Part-to-Whole Analysis** | Contribution analysis | Window aggregates |
| 12| **Customer Report** | Consolidated customer intelligence | Multiple joins, derived columns |
| 13| **Product Report** | Comprehensive product performance | Complex aggregations |

### Customer Insights
- **Segmentation**: Identified VIP, Regular, and New customer segments based on spending behavior
- **Demographics**: Sales distribution across countries, gender, and age groups

### Product Insights  
- **Revenue Leaders**: products generating highest revenue identified
- **Category Performance**: Bikes contributes 96.46% to total sales
- **Cost Analysis**: Average cost per category with profitability metrics

### Sales Trends
- **Temporal Patterns**: Monthly sales trends with running totals
- **Growth Analysis**: Year-over-year performance comparison
- **Seasonality**: Identified peak sales periods

### 🗂️ Project Structure

<pre>
retail-data-analysis/
│
├── <b>sql_scripts/</b>                    # All SQL analysis files
│   ├── 00_database_exploration.sql     # Database structure analysis
│   ├── 01_dimensions_exploration.sql   # Dimension table profiling
│   ├── 02_date_range_exploration.sql   # Temporal boundary analysis
│   ├── 03_measures_exploration.sql     # Key metric calculations
│   ├── 04_magnitude_analysis.sql       # Data distribution analysis
│   ├── 05_ranking_analysis.sql         # Top/bottom performer ranking
│   ├── 06_change_over_time.sql         # Trend & seasonality analysis
│   ├── 07_cumulative_analysis.sql      # Running totals & averages
│   ├── 08_performance_analysis.sql     # YoY/MoM comparisons
│   ├── 09_data_segmentation.sql        # Customer/product segmentation
│   ├── 10_part_to_whole_analysis.sql   # Contribution analysis
│   ├── 11_customer_report.sql          # Comprehensive customer insights
│   └── 12_product_report.sql           # Complete product performance
│
├── <b>README.md</b>                      # Project documentation
└── <b>.gitignore</b>                     # Git ignore file
</pre>
### Customer Segmentation
```sql
-- VIP/Routine/New Customer Segmentation
WITH customer_spending AS (
    SELECT
        c.customer_key,
        SUM(f.sales_amount) AS total_spending,
        MIN(order_date) AS first_order,
        MAX(order_date) AS last_order,
        DATEDIFF(month, MIN(order_date), MAX(order_date)) AS lifespan
    FROM gold.fact_sales f
    LEFT JOIN gold.dim_customers c
        ON f.customer_key = c.customer_key
    GROUP BY c.customer_key
)
SELECT 
    customer_segment,
    COUNT(customer_key) AS total_customers
FROM (
    SELECT 
        customer_key,
        CASE 
            WHEN lifespan >= 12 AND total_spending > 5000 THEN 'VIP'
            WHEN lifespan >= 12 AND total_spending <= 5000 THEN 'Regular'
            ELSE 'New'
        END AS customer_segment
    FROM customer_spending
) AS segmented_customers
GROUP BY customer_segment
ORDER BY total_customers DESC;
```

### Product Yearly Performance 
```sql
WITH yearly_product_sales AS (
    SELECT
        YEAR(f.order_date) AS order_year,
        p.product_name,
        SUM(f.sales_amount) AS current_sales
    FROM gold.fact_sales f
    LEFT JOIN gold.dim_products p
        ON f.product_key = p.product_key
    WHERE f.order_date IS NOT NULL
    GROUP BY 
        YEAR(f.order_date),
        p.product_name
)
SELECT
    order_year,
    product_name,
    current_sales,
    AVG(current_sales) OVER (PARTITION BY product_name) AS avg_sales,
    current_sales - AVG(current_sales) OVER (PARTITION BY product_name) AS diff_avg,
    CASE 
        WHEN current_sales - AVG(current_sales) OVER (PARTITION BY product_name) > 0 THEN 'Above Avg'
        WHEN current_sales - AVG(current_sales) OVER (PARTITION BY product_name) < 0 THEN 'Below Avg'
        ELSE 'Avg'
    END AS avg_change,
    -- Year-over-Year Analysis
    LAG(current_sales) OVER (PARTITION BY product_name ORDER BY order_year) AS py_sales,
    current_sales - LAG(current_sales) OVER (PARTITION BY product_name ORDER BY order_year) AS diff_py,
    CASE 
        WHEN current_sales - LAG(current_sales) OVER (PARTITION BY product_name ORDER BY order_year) > 0 THEN 'Increase'
        WHEN current_sales - LAG(current_sales) OVER (PARTITION BY product_name ORDER BY order_year) < 0 THEN 'Decrease'
        ELSE 'No Change'
    END AS py_change
FROM yearly_product_sales
ORDER BY product_name, order_year;
```

### Technical SQL Skills
- **Advanced Queries**: Complex joins, subqueries, CTEs, window functions
- **Data Modeling**: Star schema design with PK/FK relationships
- **Analytical Functions**: RANK(), LAG(), SUM() OVER(), CASE statements
- **Performance Optimization**: Efficient aggregation and filtering

### Business Intelligence
- **KPI Development**: Customer Lifetime Value, AOV, Recency
- **Segmentation Analysis**: demographic, behavioral segmentation
- **Trend Analysis**: Time series, YoY growth, moving averages
- **Reporting**: Executive-level summary reports

### Data Analysis Methodology
- **Exploratory Data Analysis (EDA)**: Comprehensive data profiling
- **Comparative Analysis**: Part-to-whole, benchmarking
### Setup Instructions
1. Clone the repository
2. Execute the SQL scripts in numerical order
3. Review the analytical outputs

### For Recruiters & Hiring Managers
- **Review files 04-10** for core analytical capabilities
- **Review files 11-12** for business reporting skills
- **Check the README** for methodology documentation

### Learning Objectives
This project demonstrates:
- Real-world business problem solving with SQL
- Progressive complexity in analytical techniques
- Professional documentation and code organization

- 1. **Mastered 14 analytical techniques** used in production BI environments
2. **Developed ability to translate** business questions into SQL queries
3. **Gained experience with** complete analytics pipeline from raw data to reports
4. **Learned to document** technical work for professional audiences
5. **Built a portfolio piece** demonstrating job-ready SQL skills

## 📞 Contact Information

<div align="center">

### **Mostafa Galal**  
*Data Analyst | Business Intelligence*

✉️ **Email:** [mostafagalal.mansour@gmail.com](mailto:mostafagalal.mansour@gmail.com)  
💼 **LinkedIn:** [Mostafa Galal](https://linkedin.com/in/mostafa-galal-2a10123a1)  
💻 **GitHub:** [mostafa-gm](https://github.com/mostafa-gm)  
📍 **Based in:** Egypt

*Open to data analyst, business intelligence, and SQL developer roles*

</div>
-LinkedIn: [linkedin.com/in/mostafa-galal-2a10123a1]
-Email: mostafagalal.mansour@gmail.com
