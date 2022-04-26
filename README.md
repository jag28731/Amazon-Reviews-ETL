# Amazon Reviews ETL Analysis

## Overview of Project
Since my work with Jennifer on the SellBy project was so successful, I was tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

### Purpose
In this project, I picked the pet product dataset and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. I used PySpark, Pandas, or SQL to determine if there was any bias toward favorable reviews from Vine members in my dataset. 

## Amazon Reviews ETL Results
Below are the results after performing the ETL process, transforming the data, connecting to an AWS RDS instance, and loading the data into pgAdmin:

- How many Vine reviews and non-Vine reviews were there?

  - Vine Reviews:
  
  ![1](https://github.com/jag28731/Amazon-Reviews-ETL/blob/main/Resources/Vine%20Reviews.PNG)

  - Non-Vine reviews:
  
  ![2](https://github.com/jag28731/Amazon-Reviews-ETL/blob/main/Resources/Non%20Vine%20Reviews.PNG)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

  - Vine 5 Star Reviews:
  
  ![3](https://github.com/jag28731/Amazon-Reviews-ETL/blob/main/Resources/Vine%20%205%20Star.PNG)

  - Non-Vine 5 Star Reviews:
  
  ![4](https://github.com/jag28731/Amazon-Reviews-ETL/blob/main/Resources/Non%20Vine%205%20Star.PNG)

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

  - Percentage of Vine 5 Star Reviews:
  
  ![5](https://github.com/jag28731/Amazon-Reviews-ETL/blob/main/Resources/Vine%20Percentage.PNG)

  - Percentage of Non-Vine 5 Star Reviews:
  
  ![6](https://github.com/jag28731/Amazon-Reviews-ETL/blob/main/Resources/Non%20Vine%20Percentage.PNG)

## Amazon Reviews ETL Summary

As a result of my analysis, in the pet product data set, there is no positivy bias for the Vine program.  The Vine program has 170 total reviews with 65 of those being a 5-star review for an average of ~38%. In the non-Vine program results, there was a total of 37,840 reviews with 20,612 of those being a 5-star review for a average of ~54%. Non-Vine programs members left more review, 5-star reviews for a higher percentage than the Vine program members. Additional testing that could be run to determine bias is checking the other star reviews. What percentage is 4 star, 3 star, ect. Also, try to determine how many Vine and non-Vine program reviews are not completed. Are there more or less Vine program non-reviews?
