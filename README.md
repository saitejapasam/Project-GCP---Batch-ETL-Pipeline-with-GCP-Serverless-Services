# Project-GCP---Batch-ETL-Pipeline-with-GCP-Serverless-Services
Cloud-native ETL pipeline built with GCP services (BigQuery, Cloud Storage, Airflow). Implements medallion architecture with data ingestion, transformation, and analytics for retail data.
**GCP Retail Analytics Pipeline**
A production-ready, cloud-native ETL pipeline built on Google Cloud Platform that processes retail sales data and transforms it into actionable business insights.

**Overview**
This project demonstrates a complete Data Engineering workflow implementing the Medallion Architecture (Bronze → Silver → Gold layers) using fully serverless GCP services. The pipeline ingests raw sales data, performs transformations, and creates analytical views for business intelligence.

**Architecture**
<img width="3933" height="785" alt="Arch" src="https://github.com/user-attachments/assets/ad4b43d9-a9f2-4afb-bebd-33cb945c1e5a" />

**Tech Stack**
Cloud Services:

Google Cloud Storage - Data Lake (Bronze Layer)

Google BigQuery - Data Warehouse (Silver/Gold Layers)

Cloud Composer - Orchestration (Apache Airflow)

Cloud Functions - Serverless Compute

IAM & Security - Access Management

Data Engineering Tools:

Apache Airflow - Pipeline Orchestration


**Project Structure**
gcp-retail-analytics/
├── dags/
│   └── retail_pipeline.py          # Airflow DAG definition
├── scripts/
│   ├── data/
│   │   └── generate_sample_data.py # Synthetic data generation
│   └── transform_data.py           # Data transformation logic
├── terraform/
│   └── main.tf                     # Infrastructure as Code
├── config/
│   └── requirements.txt            # Python dependencies
└── README.md
PySpark - Data Processing

SQL - Data Transformation & Analysis

Python - Scripting & Automation

Terraform - Infrastructure as Code
