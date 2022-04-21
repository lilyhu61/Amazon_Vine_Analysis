# Amazon_Vine_Analysis
## Resources
- Data source: [ Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
- Software: AWS, PostgreSQL, pgAdmin 4, Google Colab Notebook
## Overview of the analysis
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.The analysis uses PySpark 
to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and 
calculate different metrics. We focused on the US reviews for baby.

## Results
- How many Vine reviews and non-Vine reviews were there?
  - Vine reviews
     



