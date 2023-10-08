# YouTube-Data-Analysis

## Project Overview

The primary objective of this project is to securely manage, streamline, and conduct analysis on structured and semi-structured YouTube video data, focusing on video categories and trending metrics.

## Project Objectives
1. Data Ingestion: Create a mechanism for data ingestion from various sources.
2. ETL System: Transform raw data into the appropriate format.
3. Data Lake: Establish a centralized repository for storing data from multiple sources.
4. Scalability: Ensure the system can scale effectively as the data volume increases.
5. Cloud Integration: Utilize cloud resources, specifically AWS, for processing large datasets.
6. Reporting: Develop a dashboard to answer key analytical questions.

## Selected Services
1. Amazon S3: Employ Amazon S3 for object storage, offering scalability, data security, availability, and performance.
2. AWS IAM: Utilize AWS Identity and Access Management for secure management of access to AWS services and resources.
3. Amazon QuickSight: Leverage Amazon QuickSight as a serverless, scalable, machine learning-powered business intelligence (BI) service.
4. AWS Glue: Utilize AWS Glue as a serverless data integration service for data discovery, preparation, and aggregation.
5. AWS Lambda: Implement AWS Lambda as a serverless computing service to run code without server management.
6. AWS Athena: Utilize AWS Athena as an interactive query service for data stored in Amazon S3, eliminating the need for data loading.

## Dataset Information
The Kaggle dataset used in this project comprises CSV files containing statistics on daily popular YouTube videos spanning several months. Each day, up to 200 trending videos are published across various locations. The dataset includes information such as video titles, channel titles, publication timestamps, tags, views, likes, dislikes, descriptions, and comment counts. Additionally, the dataset includes a category_id field specific to each region, detailed in the linked JSON file.

For access to the dataset, visit: [YouTube Dataset on Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new)
