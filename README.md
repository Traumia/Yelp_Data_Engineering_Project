# Data Engineer Project - Yelp Dataset Analysis

This project focuses on processing and analyzing the Yelp Dataset using various data engineering tools and technologies.<br>
It covers data extraction, transformation, loading, and exploratory data analysis to find the top 10 popular restaurants in Philadelphia.<br>
The project also involves creating a data layer for further analysis and machine learning using BigQuery ML.<br>

## Technologies and Tools

Hadoop
HIVE
Spark
Google Cloud Platform (GCP)
BigQuery
Google Cloud Storage
DataProc
Python
SQL
Pandas
Parquet

## Key Practices

Data Extraction: Utilizing the Kaggle API, the Yelp Dataset is downloaded to the DataProc Master node. The dataset is over 8GB after unzipping <br>  
Data Transformation: The unzipped data is uploaded to the Hadoop File System (HDFS). Pyspark is used to clean and transform the dataset, and the resulting data is loaded into HIVE tables in Hadoop <br>
Exploratory Data Analysis (EDA): EDA is performed using Pyspark and Pandas to find the top 10 popular restaurants in Philadelphia <br>
Creating Data Layer: Five tables are de-normalized, processing more than 320 million records. The data is saved in Parquet format in Google Cloud Storage and loaded into BigQuery. The DataProc cluster is directly connected to Google Cloud Storage, which is used as a Data Lake <br>
Machine Learning: (TODO) Perform machine learning using BigQuery ML for further analysis and insights <br>

## Getting Started

### Prerequisites
Google Cloud Platform (GCP) account with billing enabled <br>
Kaggle account and API key <br>
Python 3.6 or higher <br>
Pyspark and Hadoop libraries installed <br>

### Setup
* Set up a Google Cloud Platform project and enable the necessary APIs (BigQuery, DataProc, Cloud Storage).
* Create a DataProc cluster with Hadoop, HIVE, and Spark installed.
* Download the Yelp Dataset using the Kaggle API and upload it to the DataProc Master node.
* Unzip the dataset and upload the files to HDFS.
* Run the provided Pyspark scripts to clean, transform, and load the data into HIVE tables.
* Perform EDA with Pyspark and Pandas to find the top 10 popular restaurants in Philadelphia.
* De-normalize the tables, save the data as Parquet files in Google Cloud Storage, and load the data into BigQuery.
* (TODO) Use BigQuery ML to perform machine learning and gain further insights.

### Contributing

Yueheng Li and Instructor Pengyuan Li

### Acknowledgements

Yelp Dataset provided by Yelp Dataset Challenge on Kaggle. 
Google Cloud Platform for providing the infrastructure and tools. 
The Pyspark, Pandas, and Hadoop communities for their open-source contributions. 

