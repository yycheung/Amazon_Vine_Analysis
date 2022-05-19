# Amazon_Vine_Analysis

## Overview
The purpose of this analysis is to analyze Amazon reviews written by members of the paid Amazon Vine program, to determine if there is any bias toward favorable reviews from Vine members in our dataset. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

First, we pick one of Amazon review datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then, we use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in our dataset. Finally, a written summary of the analysis is prepared for submission to the SellBy stakeholders.


