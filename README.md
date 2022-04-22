# Amazon_Vine_Analysis
## Resources
- Data source: [ Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
- Software: AWS, PostgreSQL, pgAdmin 4, Google Colab Notebook
## Overview of the analysis
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.The analysis uses PySpark 
to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and 
calculate different metrics. We focused on the US reviews for baby.

## Results
### 1. Total number of reviews
  - Vine reviews
     
![Screen Shot 2022-04-21 at 8 55 26 PM](https://user-images.githubusercontent.com/95242493/164587193-7cb47508-cdff-4172-8033-ee3dd48cb238.png)

 - Non-Vine reviews
 
![Screen Shot 2022-04-21 at 9 02 24 PM](https://user-images.githubusercontent.com/95242493/164587976-67b3b908-26c6-4b06-83bf-933728a81b7d.png)


### 2. Total number of 5-star reviews
  - Vine reviews 

![Screen Shot 2022-04-21 at 9 02 45 PM](https://user-images.githubusercontent.com/95242493/164588019-7385338d-be03-48a2-a5d3-3eaf2bd7b22e.png)


  - Non-Vine reviews


![Screen Shot 2022-04-21 at 9 03 51 PM](https://user-images.githubusercontent.com/95242493/164588109-c130c0a6-45e1-4ab7-9ce3-cbd54bc7d717.png)


### 3. Percentage of 5-star reviews

  - Vine reviews 
  

![Screen Shot 2022-04-21 at 9 04 33 PM](https://user-images.githubusercontent.com/95242493/164588206-c4b70f6b-7b38-4f94-ae62-c869e4f6e916.png)

  - Non-Vine reviews 
  

![Screen Shot 2022-04-21 at 9 04 09 PM](https://user-images.githubusercontent.com/95242493/164588145-5998ca83-1f33-424f-a5cc-9db10eeda11d.png)

## Summary
The percentage of 5-star reviews in the Vine program is 48%, whereas the percentage of 5-star reviews in the non-Vine reviews is 44%. This describes that there is not any positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.

 

