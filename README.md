# enterprise_level_cdc

This repository is a complete enterprise level CDC data ingestion project.
It uses the following technologies and services:
    - AWS EC2 instance
    - AWS VPC
    - AWS Lambda to scrape Rest APIs
    - AWS Aurora Postgres DB to store data
    - Docker, docker-compose, Dockerfile for instrasture
    - Debezium for monitoring row-level changes
    - AWS Kafka(MSK)

Here are the technologies planned to be used for an complete enterprise data engineering project:
    - AWS Glue
    - Apache Hudi
    - AWS Athena
    - Quicksight
    - Terraform to perhaps wrap the entire infrasture setup and teardown as code
