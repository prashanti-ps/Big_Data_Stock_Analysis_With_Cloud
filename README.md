# Big Data Stock Analysis with Cloud (A Data pipeline and Analysis Project)

This project aims to analyze daily and historical stock data of 1500+ stocks to provide valuable insights and improve decision-making. The project leverages tools and technologies such as Spark, Dataproc, Google Cloud Storage, BigQuery, and visualization to implement a scalable big data pipeline with Python / PySpark.

## Data Source  
The data source used in this project is the Polygon.io API, which provides real-time and historical stock data, as well as news data for all stocks. The project also includes historical data of the last 40 years of all stocks' high, low, and end-of-day (EOD) price.

## Process
The data pipeline includes the following steps:  

- Data collection using Spark on Dataproc from the Polygon.io API.  
- Data optimization using Spark and partitioning it by year, month, and day.  
- Storing the optimized data in GCS.  
- Loading the optimized data from GCS to the data warehouse using Spark on Dataproc and BigQuery.  
- Connecting the data warehouse to PowerBI or any visualization tool to create multiple visualizations to get stocks news and history as well as new data.  


## High Level Data Architechture Workflow

![image](https://user-images.githubusercontent.com/78148121/223528929-d4fc965d-8a97-40e1-8c1d-4fa820c62423.png)

<img width="1224" alt="image" src="https://github.com/prashanti-ps/Big_Data_Stock_Analysis_With_Cloud/assets/78148121/2b684c1a-7bba-42b3-8a6a-92486a7053d8">



## Dimensional Model

![image](https://github.com/prashanti-ps/Big_Data_Stock_Tracker/assets/78148121/314e02da-39a6-4789-a8fd-c0085b9d4677)



## Key Features
The key features of the project are:  

- A scalable big data pipeline that improves query response time and provides valuable insights to make better decisions.  
- Automated dashboard updates with real-time stock insights and news, eliminating 80% of manual effort.  
- Enhanced stock data processing by leveraging data optimization techniques, resulting in a 40% increase in processing speed.  
