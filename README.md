# Amazon Reviews ETL Analysis

## Overview of Project
Since my work with Jennifer on the SellBy project was so successful, I was tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

### Purpose
In this project, I had access to approximately 50 datasets and each one contained reviews of a specific product, from clothing apparel to wireless products. I picked one of these datasets and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. I used PySpark, Pandas, or SQL to determine if there was any bias toward favorable reviews from Vine members in my dataset. 

## Amazon Reviews ETL Results
Below are the results after performing the ETL process, transforming the data, connecting to an AWS RDS instance, and loading the data into pgAdmin:

- How many Vine reviews and non-Vine reviews were there?

  - Vine Reviews:
![1]()

  - Non-Vine reviews:
![2]()

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - Vine 5 Star Reviews:
![3]()

  - Non-Vine 5 Star Reviews:
![4]()

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - Percentage of Vine 5 Star Reviews:
![5]()

  - Percentage of Non-Vine 5 Star Reviews:
![6]()

## Amazon Reviews ETL Summary

XXX
