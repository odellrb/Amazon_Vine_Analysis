![Amazon_vine_header](BigData.png)
# Amazon_Vine_Analysis

## Overview of Analysis
This project analyzes the Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses Google colab with PySpark and Jupyter notebook with pandas to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for pet products.

## Results

* There were 170 Vine reviews and 37,340 non-Vine reviews.
* There were 65 Vine 5 star reviews and 20,612 non-Vine 5 star reviews.
* 38.24% were Vine 5 str reviews and 54.47% were non-Vine 5 star reviews.

## Summary

38.24% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 54.47%. These results do not suggest that there is a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
