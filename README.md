# Bicycle-Manufacturer

## I. OVERVIEW
- This project explores the AdventureWorks2019 Bicycle Manufacturer dataset using SQL on Google BigQuery.
The dataset contains detailed information about sales, production, and purchasing operations from a fictional bicycle company.
- The objective of this project is to analyze business performance through SQL queries — focusing on metrics such as sales growth, discount effectiveness, production stock trends, and customer retention — and to generate meaningful insights for data-driven decision-making.

## II. OBECJECTIVES
- Strengthen SQL analytical skills on a real-world structured dataset
- Calculate and evaluate business KPIs for Sales, Production, and Purchasing departments
- Measure year-over-year (YoY) growth, order performance, and customer retention rate
- Identify the top-performing categories, regions, and time periods
- Build SQL logic that supports business insight generation for decision makers

## III. DATASET ACCESS
The AdventureWorks2019 dataset used in this project is hosted on Google BigQuery. You can access and explore it directly from the public datasets section in BigQuery.
Steps to Access the Dataset:
1. Log in to your Google Cloud Platform account
2. Open the BigQuery Console in your project.
3. Navigate to: bigquery-public-data.adventureworks
4. Use the SQL editor to run queries directly in the BigQuery Console.

## VI. EXPLORING THE DATASET
In this project, I will write 08 query in Bigquery base on Google Analytics dataset.
### Question 1: Calc Quantity of items Sales value & Order quantity by each Subcategory in L12M
- SQL Code
<img width="694" height="298" alt="image" src="https://github.com/user-attachments/assets/15ec9a74-578a-4e1d-9ea5-2610f3e58d0c" />

- Query Results
<img width="937" height="736" alt="image" src="https://github.com/user-attachments/assets/e82e78e5-0e7e-4a9d-904f-dad89897ddcc" />

### Question 2: Calc % YoY growth rate by SubCategory & release top 3 cat with highest grow rate. Can use metric: quantity_item. Round results to 2 decimal.
- SQL Code
<img width="711" height="501" alt="image" src="https://github.com/user-attachments/assets/d959954e-6119-4c49-ab1d-8f65786de5a1" />

- Query Results
<img width="940" height="232" alt="image" src="https://github.com/user-attachments/assets/02c17e2b-b297-4224-916e-b4936adec8e6" />

### Question 3: Ranking Top 3 TeritoryID with biggest Order quantity of every year. If there's TerritoryID with same quantity in a year, do not skip the rank number
- SQL Code
<img width="661" height="332" alt="image" src="https://github.com/user-attachments/assets/979975d1-a34b-4330-b608-eb4ebe9d7c3f" />

- Query Results
<img width="949" height="466" alt="image" src="https://github.com/user-attachments/assets/80dfbf1b-dfa1-4be7-b823-be23e58873be" />

### Question 4: Calc Total Discount Cost belongs to Seasonal Discount for each SubCategory.
- SQL Code
<img width="733" height="421" alt="image" src="https://github.com/user-attachments/assets/5c9b4b33-5c36-4707-89ea-17752a205333" />

- Query Results
<img width="930" height="189" alt="image" src="https://github.com/user-attachments/assets/8da9da4f-866c-4440-9592-c7a86fc3f09c" />

### Question 5: Retention rate of Customer in 2014 with status of Successfully Shipped (Cohort Analysis)
- SQL Code
<img width="723" height="508" alt="image" src="https://github.com/user-attachments/assets/9dff2f2a-d2b1-4718-b083-8be3d640b01d" />

- Query Results
<img width="925" height="613" alt="image" src="https://github.com/user-attachments/assets/87336949-f5f1-4040-bdba-eb7dc542f4cb" />

### Question 6: Trend of Stock level & MoM diff % by all product 2011. If %gr rate is null then 0. Round to 1 decimal.
- SQL Code
<img width="639" height="510" alt="image" src="https://github.com/user-attachments/assets/f822e8ca-6910-4c8c-838a-c1bc96169fd6" />

- Query Results
<img width="948" height="698" alt="image" src="https://github.com/user-attachments/assets/48e4be3c-f040-4c55-a1fe-7882bedc3fee" />

### Question 7: Calc Ratio of Stock / Sales in 2011 by product name, by month. Order results by month DESC, ratio DESC. Round Ratio to 1 decimal mom yoy.
- SQL Code
<img width="579" height="649" alt="image" src="https://github.com/user-attachments/assets/3dfbce63-7cee-480d-afbb-3c1806eb6d3a" />

- Query Results
<img width="601" height="651" alt="image" src="https://github.com/user-attachments/assets/ed67057f-b4a0-4620-b2cd-2e66d4659cda" />


### Question 8: No of order and value at Pending status in 2014.
- SQL Code
<img width="455" height="167" alt="image" src="https://github.com/user-attachments/assets/a06a9ad5-00e3-455f-861c-653383e017b7" />

- Query Results
<img width="942" height="151" alt="image" src="https://github.com/user-attachments/assets/95ad1f76-a3eb-4275-a9f3-c8142536fe1a" />


## V. Conclusion
- Write efficient and scalable SQL queries for analytical purposes.
- Design metrics and KPIs across multiple business domains.
- Translate raw data into actionable insights for business stakeholders.

