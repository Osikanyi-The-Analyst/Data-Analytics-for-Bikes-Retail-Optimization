**📊 Data Quality Assessment and Recommendations 🚀**

***🚲 Problem Statement 📈***

Sprocket Central Pty Ltd, a medium-sized bikes and cycling accessories organization, has provided 🎁 KPMG with three datasets 📊 - Customer Demographic 🕵️‍♂️, Customer Addresses 🏠, and Transactions data 💰 in the past 3 months. They require KPMG's expertise in Analytics 📈, Information & Modelling 🕸️ team to effectively analyze these datasets to help optimize their marketing strategy 🎯 and grow their business 🚀.

However, the client's team is unsure how to effectively analyze their large customer dataset 🤔, and the Associate Director at KPMG has emphasized the importance of optimizing the quality of customer datasets to drive company growth 🌱.

Therefore, the main problem is to improve the quality of Sprocket Central Pty Ltd's data 📈 and identify ways to effectively analyze the datasets to optimize their marketing strategy 🎯 and grow their business 🚀. The focus will be on the customer and transactions data provided by the client 💼.
**Table of Contents 📜**
Overview 📝
Data Quality Framework 🛠️
Datasets 🗃️
Customer Demographics 🧑‍🤝‍🧑
Customer Address 🏠
Transaction Data 💳
Recommendations 📌

**Overview 🌟**
This repository contains a 📊 data quality assessment and recommendations report for a dataset provided by a client. The report includes findings on the data quality for each dataset, as well as recommendations for improving data quality. The goal of this report is to help the client improve the accuracy, completeness, consistency, currency, relevancy, validity, and uniqueness of their data.

**Data Quality Framework 🛠️**
We use the following dimensions to assess data quality:

✔️ Accuracy
✔️ Completeness
✔️ Consistency
✔️ Currency
✔️ Relevancy
✔️ Validity
✔️ Uniqueness

For more details, please refer to the Data Quality Framework Table.

**Datasets 🗃️**
Customer Demographics 🧑‍🤝‍🧑
The dataset contains customer demographic information. The following findings were identified:

❌ There are missing values in 'last_name', 'DOB', 'job_title', 'job_industry_category', 'default' and 'tenure' columns.
❌ The 'gender' column has six unique values, including invalid or incorrect values.
❌ One customer has a year of birth listed as '1843', which is likely an error.
❌ The 'default' column seems to have no relevance to the goals of the analysis.

Customer Address 🏠
The dataset contains customer address information. The following findings were identified:

❌ One customer with customer ID '3' doesn't have data in the address dataset.
❌ The 'state' column has inconsistent values.
❌ There are duplicates in the dataset based on the values in the address, postcode, state, country, and property_valuation columns.

Transaction Data 💳
The dataset contains transactional data. The following findings were identified:

❌ There are missing values in several columns, including 'online_order', 'brand', 'product_line', 'product_class', 'product_size', 'standard_cost', and 'product_first_sold_date'.
❌ Some rows have missing data in several columns.
❌ The 'product_first_sold_date' column has incorrect data.

Recommendations 📌
Based on the findings identified, the following recommendations were made to improve data quality:

✔️ Investigate and fill in missing values in the 'last_name', 'DOB', 'job_title', 'job_industry_category', 'default', and 'tenure' columns in the Customer Demographics dataset.
✔️ Clean and standardize the 'gender' column to have only two unique values, male and female, and remove any incorrect or invalid values in the Customer Demographics dataset.
✔️ Investigate and correct any errors in the 'DOB' column, such as the year of birth listed as '1843', in the Customer Demographics dataset.
✔️ Remove the 'default' column from the Customer Demographics dataset as it has no relevance to the analysis goals.
✔️ Gather the missing data in the address dataset for customer ID '3' or confirm if the customer does not have any address data.
✔️ Standardize the values in the 'state' column to avoid inconsistencies in the Customer Address dataset.
✔️ Investigate and verify the duplicates in the Customer Address dataset and take appropriate actions, such as merging the duplicate records or keeping them as separate records if they represent unique customers.
✔️ Implement measures to prevent or minimize the occurrence of duplicate records in the
