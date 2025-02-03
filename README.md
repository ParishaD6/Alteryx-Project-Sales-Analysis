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

## Phase 1 - Data Cleanup
Filtered Unnecessary Columns (e.g., product_class, product_size).
Converted Data Types for compatibility.
Renamed Columns for clarity.
Performed Data Quality Checks to ensure integrity

Tools used: 
Select Tool – Used for selecting required fields, renaming columns, and changing data types.
Filter Tool – Used to filter out unwanted records based on conditions.
Formula Tool – Applied calculations such as profit calculations (list_price - standard_cost).
Data Cleansing Tool – Ensured data consistency and handled missing values.

## Phase 2 - Cohort Analysis
Customer Segmentation: Grouped customers into cohorts based on transaction behavior.
Cohort Metrics: Computed key metrics like retention rate and average spend per cohort.
Tabular Representation: Generated a Cohort Retention Rate Table for comparison.
For a detailed view, refer to the Alteryx Workflow file (.yxmd).

Tools used:
Summarize Tool – Grouped data by cohorts (month-year, transaction behavior).
Join Tool – Merged datasets to analyze customer transactions over time.
Cross Tab Tool – Converted grouped cohort data into a tabular format for retention analysis.
Sort Tool – Sorted data for better visualization and analysis.

## Phase 3 - Business Insights Generation
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

Tools Used: 
Summarize Tool – Aggregated key metrics like total revenue, customer spending, and product line contributions.
Append Fields Tool – Merged different datasets for comprehensive insights.
Charting Tool – Visualized metrics such as average list price per product line.
Basic Table Tool – Created tabular reports for key insights.

## Phase 4: Report Generation and Auomation
Created a workflow to generate an **automated PDF report**, capturing the metrics derived from each individual workflow.  
[Download the PDF Report](https://github.com/ParishaD6/Alteryx-Project-Sales-Analysis/blob/main/Ecommerce%20Sales%20analysis%20Report_%20Alteryx.pdf)

Tools Used: 
Render Tool – Generated automated PDF and image reports.
Multiple Join Tool – Combined various reporting elements for structured report layouts.

## Workflow File  
[Click here to download](https://github.com/ParishaD6/Alteryx-Project-Sales-Analysis/blob/main/Alteryx%20Project_Sales%20Analysis.yxmd)

![image](https://github.com/user-attachments/assets/c980e2f9-2cf2-4831-b3f9-617f8e4ff1cb)
![image](https://github.com/user-attachments/assets/984fe3f9-0206-42f3-b939-660b2be093be)
![image](https://github.com/user-attachments/assets/c395335f-15ab-4a21-a4ce-655988d6bc76)

