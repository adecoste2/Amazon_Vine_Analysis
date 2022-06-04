# Amazon_Vine_Analysis

## Overview
The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Using PySpark in Google Colaboratory to perform the ETL pipeline on gift card datasets, then connect to an AWS RDS instance and load the transformed data into a SQL database using PgAdmin 4. Finally, an analysis of the data was performed to determine if there was a bias toward positive reviews from Vine members in the dataset. 

## Results
Using the vine_table DataFrame the following was able to be ascertained:
* The total number of reviews
* The number of 5-star reviews
* The number and percentage of 5-star reviews for paid vines
* number and percentage of 5-star reviews for unpaid vines
![vine_df_dataFrame](https://github.com/adecoste2/Amazon_Vine_Analysis/blob/main/Resources/vine_df_dataFrame.png?raw=true)
![all_reviews](https://github.com/adecoste2/Amazon_Vine_Analysis/blob/main/Resources/all_reviews.png?raw=true)

## Summary
Because there are 0 paid 5-star reviews in the dataset for gift cards the analysis it is hard to determine if any bias exists with paying Vine members. 
One measure that could be taken to establish if a bias exists with paying Amazon Vine members in relation to the gift card dataset would be to perform a similar analysis for the next best rating, i.e., 4-stars reviews.  
