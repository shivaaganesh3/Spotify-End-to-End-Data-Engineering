# Spotify Data Pipeline: Serverless ETL on AWS 🎧⚡

![AWS Serverless](https://img.shields.io/badge/AWS_Serverless-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Spotify API](https://img.shields.io/badge/Spotify_API-1ED760?style=for-the-badge&logo=spotify&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)


A cloud-native data pipeline that extracts, transforms, and analyzes Spotify streaming data using AWS serverless technologies. This solution demonstrates modern data engineering practices for processing music streaming data at scale.



## 📋 Project Overview
This implementation demonstrates a cloud-native ETL pipeline that processes Spotify music data using AWS serverless services. The solution enables:

- **Hourly data synchronization** from Spotify's Web API
- **Auto-scaling data processing** with AWS Lambda
- **Schema-aware storage** in Amazon S3
- **SQL-based analytics** via Amazon Athena

## Technical Architecture


**Automated music data pipeline for streaming analytics using AWS serverless architecture**
![Architecture Diagram](https://github.com/shivaaganesh3/Spotify-End-to-End-Data-Engineering/blob/main/Project%20Architecture%20Diagram.png)

## Key Features
- **Automated Data Extraction**: Hourly sync of Spotify streaming history via AWS Lambda
- **Schema Enforcement**: JSON schema validation and type conversion
- **Incremental Loading**: S3 partitioning by date/hour for efficient querying
- **Serverless Transformation**: AWS Glue ETL jobs for data normalization
- **Interactive Querying**: Amazon Athena SQL interface for analytics
- **CI/CD Pipeline**: Infrastructure-as-Code using AWS SAM

## Technologies Used
**Cloud Services**:
- AWS Lambda (Python 3.9)
- Amazon S3
- AWS Glue
- Amazon Athena
- AWS IAM
- Amazon EventBridge

**Development Tools**:
- Spotify Web API
- Python 3.9
- Boto

