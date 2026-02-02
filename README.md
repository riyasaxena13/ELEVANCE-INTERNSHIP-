# *📊 Elevance Sales Data Analysis & Dashboard*

*Internship Project – Data Analyst*
*Organization:* Elevance Skills Technology


## *📌 Project Overview*

This project focuses on analyzing sales performance data to generate actionable business insights for different teams such as Marketing, Sales, Operations, and Campaign Management.

The analysis covers:

* Product and category performance
* Sales trends over time
* Profitability analysis
* Weekend vs weekday sales comparison
* Year-over-year sales comparison

An interactive dashboard was built using *Google Looker Studio* to visualize key insights and support data-driven decision-making.

## *🛠 Tools & Technologies Used*

* *SQL* – Data aggregation and analytical queries
* *Python (Pandas)* – Data cleaning, transformation, and analysis
* *Google Colab / Jupyter Notebook* – Python execution environment
* *Google Looker Studio* – Interactive dashboard creation


## *🗂 Dataset Description*

The analysis is based on transactional sales data containing the following key features:

* order_date
* category
* sku_name
* qty_ordered
* before_discount
* after_discount
* cogs
* is_valid
* Derived date fields (year, month, day)

## *🔄 Data Preparation*

Multiple task-specific CSV files were initially generated during the analysis phase.
Using *Python (Pandas), these datasets were cleaned, standardized, and merged into a **single consolidated dataset* named:


finaldata_output.csv


This final dataset was used for *all analytical tasks and dashboard creation* to ensure:

* Consistent metrics across tasks
* Accurate aggregations strictly aligned with task questions
* A real-world, industry-standard analytical workflow


## *📈 Analytical Tasks Performed*

### *🔹 Task 1: Top 5 Products by Sales Quantity (2022)*

* Identified top 5 products in the Mobiles & Tablets category
* Filtered for valid orders
* Ranked by total quantity sold

### *🔹 Task 2: Average Quantity Sold per Category*

* Calculated average quantity sold for each product category
* Identified potential inventory issues

### *🔹 Task 3: Product Category Performance by Net Profit*

* Calculated net profit using after_discount - cogs
* Ranked categories by profitability

### *🔹 Task 4: Sales Trends for Multiple Categories (2022)*

* Monthly time-series analysis
* Compared category-wise sales performance

### *🔹 Task 5: Products with Largest Decrease in Sales (2022 vs 2021)*

* Compared year-over-year sales
* Identified top 10 products with the biggest decline

### *🔹 Task 6: Weekend vs Weekday Sales (Q4 2022)*

* Compared average daily sales on weekends vs weekdays
* Evaluated campaign effectiveness

---

## *📊 Dashboard*

An interactive dashboard was built using *Google Looker Studio*, featuring:

* KPI scorecards
* Bar charts and time-series visualizations
* Filters for year, category, and date ranges
* Weekend vs weekday performance comparison

🔗 *Live Dashboard Link:*
[https://lookerstudio.google.com/reporting/5d7e675f-d9fb-43eb-a2ea-74262d6c7ffd](https://lookerstudio.google.com/reporting/5d7e675f-d9fb-43eb-a2ea-74262d6c7ffd)


## *🔁 Project Workflow*

1. Raw data ingestion
2. Data cleaning and transformation using Python
3. Feature engineering (date fields, profit metrics, day type)
4. Task-wise analysis using SQL and Pandas
5. Interactive dashboard creation in Looker Studio
6. Business insight generation and reporting


## *🧠 Key Skills Demonstrated*

* SQL aggregation and analytical querying
* Python data analysis with Pandas
* Time-series analysis
* Business insight generation
* Data storytelling through dashboards

## *✅ Conclusion*

This project demonstrates an end-to-end data analytics workflow — from raw data processing to interactive dashboard creation — following real-world best practices.
The insights generated can help stakeholders improve campaign planning, inventory management, and profitability.


### *🚀 Status: Project Completed & Ready for Submission*


## 👩‍💻 Author
*Riya Saxena*  
Data Analyst Intern – Elevance Skills Technology
