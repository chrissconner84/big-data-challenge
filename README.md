# Big Data Homework - "Alexa, can you handle big data?"


## Background

In this assignment you will put your ETL skills to the test. Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. However, they are quite large and can exceed the capacity of local machines to handle. One dataset alone contains over 1.5 million rows; with over 40 datasets, this can be quite taxing on the average local computer. Your first goal for this assignment will be to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal will be to use PySpark or SQL to perform a statistical analysis of selected data.

1. Create DataFrames to match production-ready tables from two big Amazon customer review datasets.

## Instructions

* Used the furnished schema to create tables in your RDS database.

* Created two separate Google Colab notebooks and **extracted** two datasets from the list at [review dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt), one into each notebook.

    - https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Major_Appliances_v1_00.tsv.gz
    - https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Musical_Instruments_v1_00.tsv.gz

  
* For each notebook (one dataset per notebook), completed the following:

  * Counted the number of records (rows) in the dataset.

  * **Transformed** the dataset to fit the tables in the [schema file](../Resources/schema.sql). 

  * **Loaded** the DataFrames that correspond to tables into an RDS instance.


## Github

* Downloaded Google Colab notebooks as `.ipynb` files and uploaded those to GitHub.

* **Important:** Removed RDS password and endpoint for security. The notebook are for review only.


