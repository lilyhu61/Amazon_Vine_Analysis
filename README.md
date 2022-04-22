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
     
![Screen Shot 2022-04-21 at 5 34 29 PM](https://user-images.githubusercontent.com/95242493/164567713-ee6e8efa-286f-400e-ab03-828378c54830.png)

 - Non-Vine reviews
 
 ![Screen Shot 2022-04-21 at 5 35 17 PM](https://user-images.githubusercontent.com/95242493/164567780-7524f400-6f3f-4d2c-805b-38c5bab50077.png)
 
### 2. Total number of 5-star reviews
  - Vine reviews 

![Screen Shot 2022-04-21 at 5 38 29 PM](https://user-images.githubusercontent.com/95242493/164568054-9fec37f3-e383-4499-9c92-4ad0b03c0d76.png)

  - Non-Vine reviews


![Screen Shot 2022-04-21 at 5 39 16 PM](https://user-images.githubusercontent.com/95242493/164568120-bcb95d7f-ef11-4366-b7d8-e3af72e8eb56.png)

### 3. Percentage of 5-star reviews

  - Vine reviews 
  
![Screen Shot 2022-04-21 at 5 41 57 PM](https://user-images.githubusercontent.com/95242493/164568332-8b0bc656-712f-43b4-955b-a8d297889305.png)

  - Non-Vine reviews 
  
 ![Screen Shot 2022-04-21 at 5 43 13 PM Dark](https://user-images.githubusercontent.com/95242493/164568433-b0736e73-9a83-4ea6-b7d8-8f63423e3e2e.png)




