# ETL-Data-Pipeline-on-Google-Cloud-with-Cloud-Data-Fusion-Airflow-

## Architecture

![image](https://github.com/vishal-bulbule/etl-pipeline-datafusion-airflow/assets/143475073/0ea51bdb-99cc-4abf-8ccc-8be721462fc3)
# ☁️ ETL Data Pipeline on Google Cloud with Cloud Data Fusion & Airflow

## 📌 Overview
This project implements an **ETL (Extract, Transform, Load) data pipeline** on **Google Cloud Platform (GCP)** using **Cloud Data Fusion and Apache Airflow** for automated data processing and orchestration. It enables efficient ingestion, transformation, and loading of data from multiple sources into a centralized repository.

## 📁 Repository Structure


📂 ETL-GCP-Data-Pipeline 

│── 📄 README.md             
# Project documentation
│── 📂 data/           
# Raw & processed datasets
│── 📂 pipelines/          
# Cloud Data Fusion pipeline configurations 
│── 📂 dags/                  
# Airflow DAGs for workflow orchestration 
│── 📂 scripts/               
# Python & SQL scripts for data processing
│── 📂 results/               
# Reports, logs, & analytics from pipeline execution 
│── 📂 config/                 
# Configuration files (GCP credentials, settings) 
│── 📄 requirements.txt     
# Dependencies for cloud-based ETL
│── 📄 LICENSE               
# Legal information about usage

## ⚙️ ETL Pipeline Components
1️⃣ **Data Ingestion** – Extract data from various sources (databases, APIs, files).  
2️⃣ **Data Transformation** – Clean, filter, and enrich data using **Cloud Data Fusion**.  
3️⃣ **Data Loading** – Store processed data into **BigQuery, Cloud Storage, or relational databases**.  
4️⃣ **Workflow Orchestration** – Automate execution with **Apache Airflow DAGs**.  
5️⃣ **Monitoring & Logging** – Track pipeline performance, detect failures, and alert on anomalies.  

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ETL-GCP-Data-Pipeline.git
   cd ETL-GCP-Data-Pipeline


- Install dependencies:
pip install -r requirements.txt
- Set up Google Cloud Data Fusion and configure pipelines.
- Deploy Apache Airflow and execute DAGs for data workflow automation.
- 
**📜 License**
  
This project is open-source and available for data engineering, analytics, and cloud computing research.

**🙌 Acknowledgments**

Special thanks to contributors, Google Cloud Platform, Cloud Data Fusion, and Airflow for enabling scalable data pipelines
