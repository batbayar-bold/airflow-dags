# DAG: Data_Analytics

This DAG orchestrates the data pipeline by monitoring the availability of raw files in an S3 bucket, loading the data into Snowflake, executing DBT models for staging, dimensions, and facts, running test cases, and sending a success alert via Slack.