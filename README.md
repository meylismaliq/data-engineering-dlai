# Data Engineering Professional Certificate

> Designing, building, and managing robust data pipelines. Covers AWS, Airflow, Spark, dbt, and modern Data Lakehouse architectures.

![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=Apache%20Airflow&logoColor=white)
![DeepLearning.AI](https://img.shields.io/badge/DeepLearning.AI-Certificate-yellow)

## 📖 Overview
This repository contains my coursework, projects, and notes for the **Data Engineering Professional Certificate** offered by DeepLearning.AI and AWS.

The curriculum covers the entire **Data Engineering Lifecycle**—from generation and ingestion to storage, transformation, and serving. It focuses on building production-grade data systems using **AWS services**, **Infrastructure as Code (IaC)**, and open-source tools like **Apache Airflow** and **Spark**.

## 📂 Repository Structure

The content is organized by the four main courses in the specialization:

### 1️⃣ Course 1: Introduction to Data Engineering
* **Focus:** The mental model of a data engineer and the data lifecycle.
* **Key Concepts:**
    * The "Five Stages" of the Data Engineering Lifecycle.
    * Requirement gathering and security/privacy guardrails.
    * Introduction to AWS fundamentals (IAM, S3, EC2).

### 2️⃣ Course 2: Source Systems, Data Ingestion, and Pipelines
* **Focus:** Extracting data reliably from various sources and automating workflows.
* **Key Concepts:**
    * **Ingestion Patterns:** Batch vs. Streaming data.
    * **Orchestration:** Managing dependencies with Apache Airflow.
    * **Containerization:** Using Docker for reproducible environments.
    * **IaC:** Managing infrastructure using Terraform/CloudFormation concepts.

### 3️⃣ Course 3: Data Storage and Queries
* **Focus:** Optimizing how data is stored and retrieved for performance and cost.
* **Key Concepts:**
    * **Architectures:** Data Warehouse vs. Data Lake vs. Data Lakehouse.
    * **Storage Technologies:** Object Storage (S3), Relational (RDS), and NoSQL (DynamoDB).
    * **Big Data Formats:** Parquet, Avro, and Apache Iceberg.
    * **Query Optimization:** Partitioning, indexing, and columnar storage.

### 4️⃣ Course 4: Data Modeling, Transformation, and Serving
* **Focus:** Making data usable for analysts and ML models.
* **Key Concepts:**
    * **Data Modeling:** Star Schema, Snowflake Schema, and Data Vault.
    * **Transformation:** ELT pipelines using **dbt** (data build tool).
    * **Processing:** Distributed data processing with **Apache Spark**.
    * **Serving:** Creating views and APIs for downstream stakeholders.

---

## 🛠️ Key Projects

| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| **Streaming Ingestion Pipeline** | Built a real-time pipeline to ingest user activity logs and store them in a Data Lake. | AWS Kinesis, Lambda, S3 |
| **Data Lakehouse Implementation** | Designed a Lakehouse architecture to support both ACID transactions and analytical queries. | AWS Glue, Apache Iceberg, Athena |
| **Retail Analytics Transformation** | Modeled raw sales data into a Star Schema for business intelligence reporting. | dbt, Redshift, SQL |
| **Orchestrated ETL Workflow** | Automated a complex batch processing job with retries, alerts, and dependency management. | Apache Airflow, Python, Docker |

---

## 🧰 Tech Stack & Tools used
* **Cloud Provider:** AWS (S3, Redshift, Glue, Kinesis, Lambda, Athena)
* **Orchestration:** Apache Airflow
* **Processing:** Apache Spark, Pandas
* **Transformation:** dbt (data build tool)
* **Infrastructure:** Docker, Terraform (Concepts)
* **Languages:** Python, SQL, Bash

## 🚀 Getting Started

To run the labs or scripts in this repository, you will likely need an AWS account and a local python environment.

```bash
# Clone the repository
git clone [https://github.com/meylismaliq/data-engineering-dlai.git](https://github.com/meylismaliq/data-engineering-dlai.git)

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install common dependencies
pip install boto3 pandas pyspark apache-airflow
