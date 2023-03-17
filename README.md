# DE_Project

This is Data Engineer Project involves many topics and technologys:

keyworks: Hadoop, HIVE, Spark, GCP, BigQuery, CloudStorage, DataProc, Python, SQL, Pandas, Parquet

Key Practices In This project:

Data Extraction: Using Kaggle API to download the Yelp Dataset to DataProc Master node. (>8GB after unzip)
Data Transformation: Upload the unzipped data to Hadoop File System; Used pyspark to clean the transform the dataset, then load into HIVE tables in Hadoop.
Performed Exploratory Data Analysis with Pyspark and Pandas, found the best 10 popular restaurants in Philadelphia.
Created DataLayer, by de-normalizing the 5 tables ( processed >320 million records); saved the data as Parquet format in CloudStorage and loaded into BigQuery. (Connected Dataproc cluster to CloudStorage directly, used CloudStorage as DataLake)
.TODO ..perform ML using BigQuery ML.

## Table of Contents

* Spark_Hello_World
* data_cleaning_project_demo
* yelp_spark_project

## Installation

Instructions on how to install your project and its dependencies.

## Usage

Clone the repository: `git clone https://github.com/Traumia/DE_Project.git`

## Contributing

Yueheng Li and Instructor Pengyuan Li
