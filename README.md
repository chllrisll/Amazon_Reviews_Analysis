# Amazon_Vine_Analysis
Pick one of the 50 datasets. Use PySpark to perform the ETL process, connect to an AWS RDS instance, and load the transformed data into pgAdmin.

## Results

-How many Vine reviews and non-Vine reviews were there?

![Vine_ReviewsvsNonVine](https://user-images.githubusercontent.com/49954261/154023204-f56a1ea6-6780-40a6-abf5-2ffae49545e3.png)

-How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![5Star_Review-paid-vs-nonpaid](https://user-images.githubusercontent.com/49954261/154023234-ef9edb7a-2287-4d2b-b28c-f9446e8126d4.png)

-What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![Perc_5Star_Rev](https://user-images.githubusercontent.com/49954261/154023264-aa7da8b4-15e0-4c83-9478-173cd7578efd.png)


## Summary

1.) The majority of reviews 99.9% are non-vine reviewers
 
2a.) Percent of 5 star app reviews from paid/, 'helpful' dataset: = 25%


2b.) Percent of 5 star app reviews from nonpaid/, 'helpful' dataset: = 49%

3.) Additionally we would recommend testing a larger sample the 'helpful' parameters reduced the count considerably.

