# Walmart Sales Analysis Project Overview

In this project, we are tasked with analyzing Walmart sales data to identify the **top-performing branches**, **highlight key products**, analyze **product sales trends**, and gain insights into **customer behavior**. The primary goal is to develop strategies for improving store performance and optimizing profits. Through a comprehensive examination of sales data, we aim to provide actionable recommendations to enhance overall store efficiency and financial outcomes.
## Data Understanding:
- The data we got is from **Kaggle** in the form of CSV files, the file contains one sheet named Walmart sales data.
- Here in the sheet, there are 17 columns and 1000 rows, you can access the data from here: https://drive.google.com/file/d/1EeybxdUqwWhVNLcoX1u25wTAILys1_qZ/view?usp=sharing
## Data Exploration :

Here is the classification of the given columns into nominal, ordinal, discrete, and continuous data types:

| Column                  | Description                             | Data Type        | Classification   |
| :---------------------- | :-------------------------------------- | :--------------- | :--------------- |
| invoice_id              | Invoice of the sales made               | VARCHAR(30)      | Nominal          |
| branch                  | Branch at which sales were made         | VARCHAR(5)       | Nominal          |
| city                    | The location of the branch              | VARCHAR(30)      | Nominal          |
| customer_type           | The type of the customer                | VARCHAR(30)      | Nominal          |
| gender                  | Gender of the customer making purchase  | VARCHAR(10)      | Nominal          |
| product_line            | Product line of the product sold        | VARCHAR(100)     | Nominal          |
| unit_price              | The price of each product               | DECIMAL(10, 2)   | Continuous       |
| quantity                | The amount of the product sold          | INT              | Discrete         |
| VAT                     | The amount of tax on the purchase       | FLOAT(6, 4)      | Continuous       |
| total                   | The total cost of the purchase          | DECIMAL(10, 2)   | Continuous       |
| date                    | The date on which the purchase was made | DATE             | Ordinal (if sorted by date) |
| time                    | The time at which the purchase was made | TIMESTAMP        | Ordinal (if sorted by time) |
| payment_method          | The total amount paid                   | DECIMAL(10, 2)   | Continuous       |
| cogs                    | Cost Of Goods Sold                      | DECIMAL(10, 2)   | Continuous       |
| gross_margin_percentage | Gross margin percentage                 | FLOAT(11, 9)     | Continuous       |
| gross_income            | Gross Income                            | DECIMAL(10, 2)   | Continuous       |
| rating                  | Rating                                  | FLOAT(2, 1)      | Ordinal          |


## Data Cleaning:
