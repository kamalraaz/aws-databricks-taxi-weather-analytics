# aws-databricks-taxi-weather-analytics
Enterprise-grade Data Engineering Pipeline using AWS, Databricks, Delta Lake, Amazon Redshift, and Power BI.
# 🚖 End-to-End Taxi & Weather Analytics Platform

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![Databricks](https://img.shields.io/badge/Databricks-Lakehouse-red)
![Apache Spark](https://img.shields.io/badge/Apache-Spark-E25A1C)
![Delta Lake](https://img.shields.io/badge/Delta-Lake-00ADD8)
![Redshift](https://img.shields.io/badge/Amazon-Redshift-blue)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![Python](https://img.shields.io/badge/Python-3.11-blue)
![SQL](https://img.shields.io/badge/SQL-Analytics-lightgrey)

Enterprise-grade Data Engineering project demonstrating an end-to-end AWS Lakehouse architecture using Amazon S3, AWS Lambda, Databricks, Delta Lake, Amazon Redshift, and Power BI.

---

# 📌 Business Problem

Transportation companies collect millions of taxi trips every day.

However,

- Taxi trip data exists separately.
- Weather data comes from external APIs.
- Business teams cannot understand how weather affects demand.
- Pricing strategies become inefficient.
- Driver allocation is suboptimal.
- Revenue opportunities are missed.

The goal of this project is to integrate both datasets into a centralized analytics platform that enables business users to analyze demand, optimize pricing, and improve operational planning.

---

# 🎯 Solution

This project builds an enterprise-scale Lakehouse architecture that

- Ingests Taxi data into AWS S3
- Fetches Weather data using AWS Lambda
- Processes data using Databricks
- Implements Medallion Architecture
- Loads curated data into Amazon Redshift
- Builds interactive dashboards using Power BI

---

# 🏗 Architecture

(Add architecture image here)

---

# 🔄 End-to-End Pipeline

Weather API
↓

AWS Lambda
↓

Amazon S3 Landing

+

NYC Taxi Dataset
↓

Amazon S3 Landing

↓

Bronze Layer

↓

Silver Layer

↓

Gold Layer

↓

Amazon Redshift

↓

Power BI

---

# 🧱 Medallion Architecture

Bronze

- Raw Data
- Immutable
- Delta Format

↓

Silver

- Cleansed
- Validated
- Standardized

↓

Gold

- Business Ready
- Aggregated
- Analytics Optimized

---

# ⚙ Technology Stack

| Layer | Technology |
|--------|------------|
| Cloud | AWS |
| Storage | Amazon S3 |
| Compute | Databricks |
| Processing | Apache Spark |
| Data Lake | Delta Lake |
| Warehouse | Amazon Redshift |
| BI | Power BI |
| Programming | Python |
| Query | SQL |
| Infrastructure | CloudFormation |

---

# 📂 Repository Structure

```text
architecture/
docs/
lambda/
cloudformation/
notebooks/
sql/
images/
sample-data/
setup/
```

---

# 🚀 Features

✔ Automated Weather API ingestion

✔ AWS Lambda

✔ Amazon S3 Data Lake

✔ Medallion Architecture

✔ Bronze Silver Gold

✔ Delta Lake

✔ Apache Spark

✔ Databricks

✔ Amazon Redshift

✔ Power BI Dashboard

✔ CloudFormation

✔ Enterprise Documentation

---

# 📈 Data Flow

Taxi Data

↓

Landing

↓

Bronze

↓

Silver

↓

Gold

↓

Redshift

↓

Power BI

---

# 📷 Screenshots

(Add screenshots)

- Architecture
- Databricks
- Bronze
- Silver
- Gold
- Redshift
- Power BI

---

# 📚 Documentation

| Document | Description |
|----------|-------------|
| BRD | Business Requirement Document |
| HLD | High Level Design |
| LLD | Low Level Design |
| ETL Design | ETL Workflow |
| Architecture | Solution Design |

---

# 🔮 Future Improvements

- Unity Catalog
- Databricks Asset Bundles
- Apache Airflow
- Databricks Auto Loader
- Incremental MERGE
- CI/CD
- Terraform
- AWS Secrets Manager
- Monitoring & Alerting

---

# 👨‍💻 Author

Raj Kamal

Data Engineer

LinkedIn

GitHub
