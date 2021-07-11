# Amazon_Vine_Analysis

## Overview
This project I chose to analyze Music reviews. By using PySpark to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Determining if there is any bias toward paid or unpaid reviews from Vine members using PySpark was analyzed. 

## Results
- How many Vine reviews (paid) and non-Vine reviews (unpaid) were there?

<img width="403" alt="Screen Shot 2021-07-11 at 7 42 46 PM" src="https://user-images.githubusercontent.com/80358062/125213371-2d61af80-e280-11eb-9ddc-d6c5d30e0dcc.png">

- How many Vine reviews (paid) were 5 stars? How many non-Vine reviews (unpaid)
 were 5 stars?

<img width="639" alt="Screen Shot 2021-07-11 at 7 43 35 PM" src="https://user-images.githubusercontent.com/80358062/125213402-49fde780-e280-11eb-9a46-25b2d8d38256.png">

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

<img width="650" alt="Screen Shot 2021-07-11 at 7 44 12 PM" src="https://user-images.githubusercontent.com/80358062/125213459-60a43e80-e280-11eb-9f7d-7d73cd5f5fc7.png">

## Summary
based on the information presented above it appears that The percent of paid 5 star reviews was only 22% versus unpaid reviews with 70%. With this ratio it shows a negative bias towards paid reviews in the Vine Program. To add to the analysis, statistical distribution of mean, median, mode of Vine versus non-Vine reviews could be looked at to draw a better conclusion.
