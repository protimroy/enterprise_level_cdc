# Enterprise Level CDC project on AWS

This repository is a complete enterprise level CDC data ingestion project.

It uses the following technologies and services:
    
    -AWS EC2 instance
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



Here is the overview of the project:
![My Image](images/enterprise_cdc_pipeline.png)


sources:
[1] https://www.youtube.com/watch?v=eQPtuLwJxHA
[2] https://www.youtube.com/watch?v=E9D3sgVA6YA
