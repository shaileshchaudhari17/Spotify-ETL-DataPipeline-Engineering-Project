# Spotify-ETL-Data-Engineering-Project

Built ETL Pipeline for fetching spotify global trending songs using the spotify apis,

Extraction part is written in python and deployed on AWS using Lambda function and s3 bucket to store the fetched raw data data

In Transformation part fetched the data from S3 bucket generated by the Extraction Process and done data transformation using AWS lambda function and stored the transformed data to S3 Used trigger of AWS for automation of extraction and transformation process.

Finally data is loaded to Snowflake using Snowpipe. Using the AWS and snowflake integration.
