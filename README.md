# -Amazon_Vine_Analysis

# Overview of Project
During this project an analysis of the Amazon Vine program was conducted to determine if there is a bias in reviews from Vine members. This project utilized PySpark to run an ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin, and to calculate various metrics determined by the manager. 

Resources:
Big Datasets from AWS
PySpark 
AWS Simple Storage Service (S3)
Postgres
SQL & PgAdmin
Google Colab Notebook


#Results
Attached below are the created tables populated with the appropriate data.
Product table
<img width="1440" alt="Screen Shot 2022-10-17 at 10 51 51 AM" src="https://user-images.githubusercontent.com/80330988/196392624-02a50afc-a0da-4242-a71e-1d449ddde1cf.png">
Review table 
<img width="1433" alt="Screen Shot 2022-10-17 at 10 49 53 AM" src="https://user-images.githubusercontent.com/80330988/196393067-8c596e13-bd67-4ab7-bbc3-7c18970c10e4.png">

Customer table 
<img width="1437" alt="Screen Shot 2022-10-17 at 10 55 49 AM" src="https://user-images.githubusercontent.com/80330988/196392741-0d95c1cc-8abb-46e6-86f2-38d92cddd055.png">

Vine Table
<img width="669" alt="Screen Shot 2022-10-17 at 12 33 59 PM" src="https://user-images.githubusercontent.com/80330988/196392787-12b89f13-60e0-48dd-8f50-cd64a46e3dca.png">

#Summary 
The results of the analysis suggest a bias towards the unpaid reviews in the amazon vine program. Additional analysis are recommended to reveal other trends in dataset include the calculation of statitical distribution of the vine and non-vine reviews. e.g Mean, median, IQR, SD

The result of the analysis conducted 
<img width="566" alt="Screen Shot 2022-10-18 at 7 39 23 AM" src="https://user-images.githubusercontent.com/80330988/196419559-6864ee18-8799-4a48-a5bc-04c9dc55c486.png">

<img width="567" alt="Screen Shot 2022-10-18 at 7 40 01 AM" src="https://user-images.githubusercontent.com/80330988/196419670-727c34c8-40c5-42d3-8acc-5cefe628ca36.png">

