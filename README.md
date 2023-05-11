# Uber Data Analytics Modern Data Engineering
##### My first end to end modern data engineering project GCP project

## Introduction 
The goal of this project is to perform data analytics on Uber data using various tools and technologies, including GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio.

## Architecture
<img width="960" alt="Screen Shot 2023-05-11 at 2 51 55 PM" src="https://github.com/kutluk-ken/Uber-Data-Analytics/assets/56012015/b63ebe2a-10d9-4a23-8135-189bdef6a9db">

## Technology Used
- Programming Language - Python
- Google Cloud Platform
  - Google Storage
  - Compute Instance
  - BigQuery
  - Looker Studio
 - Modern Data Pipeine Tool - https://www.mage.ai/
 - Contibute to this open source project - https://github.com/mage-ai/mage-ai

## Dataset Used
TLC Trip Record Data Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

Here is the dataset used in the video - https://github.com/darshilparmar/uber-etl-pipeline-data-engineering-project/blob/main/data/uber_data.csv

More info about dataset can be found here:
  1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
  2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
<img width="1151" alt="Screen Shot 2023-05-11 at 2 57 44 PM" src="https://github.com/kutluk-ken/Uber-Data-Analytics/assets/56012015/71ae46ba-09a0-477c-93b9-b5c70fabae79">

## ETL
Using mordern data pipeline tool for transforming and integrating data.
<img width="1491" alt="Screen Shot 2023-05-11 at 3 13 21 PM" src="https://github.com/kutluk-ken/Uber-Data-Analytics/assets/56012015/02163eeb-2bbc-475a-9f85-84496abf3f67">

## BigQuery
<img width="1505" alt="Screen Shot 2023-05-11 at 3 14 07 PM" src="https://github.com/kutluk-ken/Uber-Data-Analytics/assets/56012015/93d9b15c-fad4-4443-b303-5c3320f153fa">



## To do
- Increase data file size: Add more rows to the data file to increase the data size beyond 100k rows. (Also change the format from csv to parquet)
- ETL process using Airflow
