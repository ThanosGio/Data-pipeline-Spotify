# Spotify Data Pipeline: End-to-End Python Data Engineering Project

This project demonstrates an end-to-end data pipeline for integrating with Spotify's API, extracting data, and deploying it on AWS for automated processing and analytics. The pipeline includes automated extraction, transformation, and storage processes, as well as analytics using AWS Glue and Athena.

## Project Overview

This data engineering project showcases how to:
- Integrate with the Spotify API to extract music data.
- Automate the data extraction process by deploying Python code on AWS Lambda.
- Set up triggers for automatic execution of the extraction job.
- Write transformation functions to clean and preprocess the extracted data.
- Store transformed files in Amazon S3 in an organized manner.
- Build analytics tables using AWS Glue and query the data with Athena.

## Key Features

1. **Spotify API Integration**  
   Extracts music-related data (e.g., tracks, artists, albums) from the Spotify API.

2. **AWS Lambda for Automation**  
   The extraction code is deployed on AWS Lambda, ensuring the process is lightweight and scalable.

3. **Automated Triggers**  
   A scheduled trigger is configured to automatically run the data extraction at regular intervals.

4. **Data Transformation**  
   Includes Python functions to transform and clean the extracted data for downstream processing.

5. **S3 Data Storage**  
   Extracted and transformed data is stored in Amazon S3, organized for efficient retrieval and analytics.

6. **Analytics with AWS Glue and Athena**  
   Data files in S3 are processed using AWS Glue to create crawlers and tables. AWS Athena is then used to query the data for analysis.

## Technologies Used

- **Python**: For data extraction and transformation logic.
- **Spotify API**: To fetch real-time music data.
- **AWS Lambda**: For deploying and automating the data extraction process.
- **AWS S3**: To store extracted and transformed data.
- **AWS Glue**: For cataloging and processing data stored in S3.
- **AWS Athena**: For querying data and generating insights.
