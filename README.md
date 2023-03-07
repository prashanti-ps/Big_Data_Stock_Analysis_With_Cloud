# Big Data Stock Tracker (A Data pipeline and Analysis Project)

This project aims to analyze daily and historical stock data of 1500+ stocks to provide valuable insights and improve decision-making. The project leverages tools and technologies such as Spark, Dataproc, Google Cloud Storage, BigQuery, and visualization to implement a scalable big data pipeline.

## Data Source  
The data source used in this project is the Polygon.io API, which provides real-time and historical stock data, as well as news data for all stocks. The project also includes historical data of the last 40 years of all stocks' high, low, and end-of-day (EOD) price.

## Process
The data pipeline includes the following steps:  

Data collection using Spark on Dataproc from the Polygon.io API.  
Data optimization using Spark and partitioning it by year, month, and day.  
Storing the optimized data in GCS.  
Loading the optimized data from GCS to the data warehouse using Spark on Dataproc and BigQuery.  
Connecting the data warehouse to PowerBI to create multiple visualizations to get stocks news and history as well as new data.  


## High Level Data Architechture Workflow

![image](https://user-images.githubusercontent.com/78148121/223528929-d4fc965d-8a97-40e1-8c1d-4fa820c62423.png)


## Dimensional Model for BI Schema 



## Key Features
The key features of the project are:  

A scalable big data pipeline that improves query response time and provides valuable insights to make better decisions.  
Automated dashboard updates with real-time stock insights and news, eliminating 80% of manual effort.  
Enhanced stock data processing by leveraging data optimization techniques, resulting in a 40% increase in processing speed.  
