# Alteryx-Project-E-Commerce-Sales-Analysis


The project utilizes the transaction_dataset.csv dataset, containing detailed customer transaction information, including transaction IDs, product details, customer IDs, transaction dates, order statuses, and more. It consists of 20,000 rows across 13 columns.

Key Attributes:
1. Transaction ID
2. Product ID
3. Customer ID
4. Transaction Date
5. Online Order (True/False)
6. Order Status (Approved/Unapproved)
7. Brand
8. Product Line
9. List Price
10. Standard Cost
11. Product First Sold Date

Project Phases
This Alteryx workflow is designed to analyze customer transactions through three key phases:

Phase 1 - Data Cleanup
Column Filtering: Removed unnecessary columns (product_class, product_size) using the SELECT tool.
Data Type Conversion: Ensured data compatibility using the SELECT tool.
Column Renaming: Standardized column names for better clarity.
Quality Assurance: Checked data integrity using the BROWSE tool.

Phase 2 - Cohort Analysis
Customer Segmentation: Grouped customers into cohorts based on transaction behavior.
Cohort Metrics: Computed key metrics like retention rate and average spend per cohort.
Tabular Representation: Generated a Cohort Retention Rate Table for comparison.
For a detailed view, refer to the Alteryx Workflow file (.yxmd).

Phase 3 - Business Insights Generation
This phase involved building workflows to extract the following insights:

1. Brand & Customer Insights
Distinct Brands: Identified unique brands in the dataset.
Unique Customers: Counted the number of distinct customers who made transactions.
Approved vs. Unapproved Orders: Analyzed transaction approval status.

2. Sales & Revenue Insights
Average List Price by Product Line: Ranked product lines based on average list price.
Customer Spending Analysis:
a. Total transactions per customer
b. Total amount spent
c. Average profit per transaction
Customer who purchased from all product line
Top Product Lines by Revenue Contribution: Identified product lines generating the most revenue.

Phase 4: Created workflow to create a automated pdf report capturing the metrics derived from each individual workflow

Workflow created
![image](https://github.com/user-attachments/assets/c980e2f9-2cf2-4831-b3f9-617f8e4ff1cb)
![image](https://github.com/user-attachments/assets/984fe3f9-0206-42f3-b939-660b2be093be)
![image](https://github.com/user-attachments/assets/c395335f-15ab-4a21-a4ce-655988d6bc76)

