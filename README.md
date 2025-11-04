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
<img width="700" height="305" alt="image" src="https://github.com/user-attachments/assets/520abe2b-4888-43a9-8f61-80938861cf5c" />

- Query Results
<img width="939" height="560" alt="image" src="https://github.com/user-attachments/assets/e04579b6-cec8-4fec-afd6-2ba0517127f0" />

### Question 2: Calc % YoY growth rate by SubCategory & release top 3 cat with highest grow rate. Can use metric: quantity_item. Round results to 2 decimal.
- SQL Code
<img width="723" height="502" alt="image" src="https://github.com/user-attachments/assets/55ba6518-0849-4c58-8a16-72c1d3a3833c" />

- Query Results
<img width="942" height="226" alt="image" src="https://github.com/user-attachments/assets/5bca39a2-08a8-41cc-bece-42006776f054" />

### Question 3: Ranking Top 3 TeritoryID with biggest Order quantity of every year. If there's TerritoryID with same quantity in a year, do not skip the rank number
- SQL Code
<img width="599" height="328" alt="image" src="https://github.com/user-attachments/assets/04d90600-f5a9-4464-a542-d66b3c8d2b64" />

- Query Results
<img width="933" height="460" alt="image" src="https://github.com/user-attachments/assets/eba281ec-d8b2-4290-90fc-ed2ee7d92221" />

### Question 4: Calc Total Discount Cost belongs to Seasonal Discount for each SubCategory.
- SQL Code
<img width="685" height="411" alt="image" src="https://github.com/user-attachments/assets/16023745-c14e-4a1b-818a-a1fa329867d7" />

- Query Results
<img width="942" height="206" alt="image" src="https://github.com/user-attachments/assets/9241ce6b-579a-441a-b8b8-d8a13e12787a" />

### Question 5: Retention rate of Customer in 2014 with status of Successfully Shipped (Cohort Analysis)
- SQL Code
<img width="711" height="494" alt="image" src="https://github.com/user-attachments/assets/184d0018-0702-4ccc-ab90-4180f82a4487" />

- Query Results
<img width="941" height="697" alt="image" src="https://github.com/user-attachments/assets/d37daf56-5f00-4efa-aab3-8f4eaade827f" />

### Question 6: Trend of Stock level & MoM diff % by all product 2011. If %gr rate is null then 0. Round to 1 decimal.
- SQL Code
<img width="647" height="493" alt="image" src="https://github.com/user-attachments/assets/c50095d9-5dc5-4f3c-94ea-3bba4b9fb26c" />

- Query Results
<img width="1013" height="632" alt="image" src="https://github.com/user-attachments/assets/db0b354b-017d-4636-8b28-eabcaad3682e" />

### Question 7: Calc Ratio of Stock / Sales in 2011 by product name, by month. Order results by month DESC, ratio DESC. Round Ratio to 1 decimal mom yoy.
- SQL Code
<img width="595" height="647" alt="image" src="https://github.com/user-attachments/assets/a6deb97a-af2d-4f1d-87d5-3f969d57604c" />

- Query Results
<img width="1056" height="623" alt="image" src="https://github.com/user-attachments/assets/2b678fc3-2665-4034-aeee-5b2fcc70a0c1" />

### Question 8: No of order and value at Pending status in 2014.
- SQL Code
<img width="435" height="162" alt="image" src="https://github.com/user-attachments/assets/4db67655-5547-409b-8629-ab5a67c3f5eb" />

- Query Results
<img width="1047" height="160" alt="image" src="https://github.com/user-attachments/assets/012574f0-1aa4-4b82-b101-369775df3880" />

## V. Conclusion
- Write efficient and scalable SQL queries for analytical purposes.
- Design metrics and KPIs across multiple business domains.
- Translate raw data into actionable insights for business stakeholders.

