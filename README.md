# Overview of the analysis of the Vine program:

## The purpose of this analysis is well defined 

 Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.



## Results:

### There is a bulleted list that addresses the three questions for unpaid and paid program reviews

![results](https://user-images.githubusercontent.com/115379848/232918671-3a1b7890-4bdd-4299-b7ba-6285d5fcf7ff.png)

## Summary:

### The summary states whether or not there is bias, and the results support this statement


54.4% of the Vine reviews were 5-star reviews

47.1% of the Non-vine reviews were 5-star reviews

36038 Unpaid reviews (non-vine)

272 Paid reviews (vine)

148 Vine 5-star reviews

16964 Non-vine 5-star reviews


### An additional analysis is recommended to support the statement 

The Amazon vine Analysis to provide a favorable dataset on five star rating.
The data isn't Vine reviews over specfic product which may restrict te results and create a different dataset on Vine products.
