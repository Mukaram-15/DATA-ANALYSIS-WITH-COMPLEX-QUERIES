# DATA-ANALYSIS-WITH-COMPLEX-QUERIES

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: MOHAMMED MUKARAM ALI 

*INTERN ID*: E8EDB396AAFEF80D

*DOMAIN*: SQL 

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH  

Advanced Data Analysis Using SQL: Window Functions, Subqueries, and CTEs

Advanced data analysis in SQL goes beyond basic SELECT, WHERE, and GROUP BY clauses. Techniques such as Window Functions, Subqueries, and Common Table Expressions (CTEs) enable analysts to perform complex calculations, identify trends, and uncover hidden patterns directly within the database. These features are essential for generating meaningful analytical reports from large datasets.

Window Functions for Trend Analysis

Window functions allow calculations across a set of rows related to the current row without collapsing the result set. Unlike aggregate functions, window functions retain individual rows while performing computations such as running totals, rankings, and moving averages. Functions like ROW_NUMBER(), RANK(), DENSE_RANK(), SUM() OVER(), and AVG() OVER() are commonly used.

For example, window functions can be used to calculate monthly sales trends, cumulative revenue, or rank employees by performance within each department. By using the PARTITION BY clause, data can be segmented (e.g., by region or category), while ORDER BY helps analyze trends over time. This makes window functions ideal for time-series analysis and comparative reporting.

Subqueries for Pattern Identification

Subqueries are queries nested inside another SQL query and are useful for filtering, aggregation, and comparative analysis. They help break down complex logic into manageable components. Subqueries can be used in SELECT, FROM, or WHERE clauses.

For instance, a subquery can identify customers whose spending is above the average purchase value or products with sales higher than the overall average. Subqueries are especially useful when analyzing outliers, above-average performance, or conditional patterns. They allow analysts to compare individual records against aggregated results, leading to more insightful conclusions.
Common Table Expressions (CTEs) for Readable and Modular Analysis
CTEs, introduced using the WITH clause, improve the readability and maintainability of complex SQL queries. They act as temporary result sets that can be referenced multiple times within a query. CTEs are particularly useful for step-by-step analysis and hierarchical data processing.
In advanced reporting, CTEs can be used to first clean and aggregate data, then apply window functions or additional filters in subsequent steps. For example, a CTE may calculate daily sales totals, while the main query uses a window function to compute running totals or growth percentages. Recursive CTEs can also analyze hierarchical patterns such as organizational structures or category trees.
Generating Analytical Reports
By combining window functions, subqueries, and CTEs, SQL can generate powerful analytical reports that highlight trends, rankings, growth patterns, and performance comparisons. These techniques reduce the need for external analytical tools and ensure that insights are derived directly from the source data, improving accuracy and efficiency.
Conclusion
Window functions, subqueries, and CTEs are essential tools for advanced SQL data analysis. Together, they enable the discovery of trends and patterns, support complex business logic, and produce clear, structured analytical reports. Mastering these features allows organizations to make data-driven decisions using SQL alone.

*OUTPUT*: 

<img width="585" height="373" alt="Image" src="https://github.com/user-attachments/assets/d2945a9d-6cb1-4d84-b2fb-38d5c262b93c" />
<img width="587" height="337" alt="Image" src="https://github.com/user-attachments/assets/6ae807d1-ed2e-46db-822c-456ffceef607" />
