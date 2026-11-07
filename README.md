<div align="center">

# Hi, I'm Kishore Donipudi 👋

### Data Engineer · Databricks · SQL · Python · Cloud Data Platforms

<a href="https://www.linkedin.com/in/kishore-donipudi-2a9009307">
  <img src="https://img.shields.io/badge/LinkedIn-Kishore%20Donipudi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="https://github.com/Kishore-donipudi">
  <img src="https://img.shields.io/badge/GitHub-Kishore--donipudi-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>
<a href="mailto:kishoredonipudi921@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact%20me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
</a>

</div>

## 👨‍💻 Professional Summary

Detail-oriented **Data Engineer** with a strong foundation in **SQL, Python, and data analysis**, complemented by specialized training in the Full Stack Data Engineer with Databricks stream. Hands-on experience building ETL/ELT pipelines on Databricks across AWS and Azure using medallion architecture, file-based ingestion, automated data quality checks, and live dashboards.

Experienced in documenting workflows end to end, troubleshooting data issues, supporting production workflows, and working with Apache Airflow, MLflow, and Mosaic AI.

## 🛠️ Core Competencies & Skills

### 💻 Programming & Databases

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
</p>

**Libraries:** Pandas · NumPy · Matplotlib · boto3

### 🧱 Data Engineering

<p>
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks">
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Apache Airflow">
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" alt="dbt">
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="Apache Spark">
</p>

ETL/ELT pipelines · Medallion architecture · Lakeflow Spark Declarative Pipelines (DLT) · Auto Loader · Incremental models · dbt snapshots · Semantic marts · File-based ingestion · Pipeline monitoring

### ✅ Data Quality & Governance

DLT data quality constraints · Null and duplicate handling · SQL data checks · Source-to-target reconciliation · Unity Catalog volumes · External locations · Managed tables · Data documentation · Runbooks

### ☁️ Cloud Platforms

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white" alt="Amazon S3">
  <img src="https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Microsoft Azure">
</p>

AWS S3 · IAM access through external locations · Azure external locations

### 📊 Analytics, AI/ML & Serving

Databricks AI/BI Dashboards · Streamlit · Databricks Apps · MLflow · Mosaic AI · Churn analysis · Recommendations · AI-ready curated marts

### ⚙️ Orchestration, DevOps & Operations

Apache Airflow · Databricks Workflows / Lakeflow Jobs · Task dependencies · Retries · Azure DevOps · Git · GitHub · ServiceNow incident management · First-level troubleshooting · Production support workflows

## 🚀 Projects & Professional Training

### 🎬 Netflix-Style Streaming Analytics Platform

**Active project** · [View on GitHub](https://github.com/Kishore-donipudi/databricks_end_to_end_project_01)

- Designed a medallion architecture where a data generator feeds a scheduled Databricks Job, lands data in AWS S3, and uses Lakeflow DLT with Auto Loader to stream data into five Bronze tables: users, content, watch events, ratings, and subscriptions.
- Built incremental dbt Silver models keyed on business IDs with null filtering, deduplication, standardized data types, and `updated_at`-based processing.
- Tracked user history with a dbt snapshot and published dbt Gold marts through `ref()` dependencies.
- Created dashboard and AI layers covering active users, subscriptions, content, watch time, top users, churn analysis, and content recommendations.
- **In progress:** Airflow orchestration, live dashboard, MLflow churn model, Mosaic AI model serving, and CI/CD.

**Tech stack:** Databricks · Lakeflow DLT & Jobs · Auto Loader · dbt · AWS S3 · SQL · Python · Git/GitHub · Apache Airflow · MLflow · Mosaic AI

### 🍔 End-to-End Food Delivery Data Platform

**Live project** · [View on GitHub](https://github.com/Kishore-donipudi/aws_e2e_de)

- Built an end-to-end pipeline from raw CSV files in AWS S3 to a public live dashboard.
- Used boto3 to list and download files into Unity Catalog Volumes, configured an AWS external location, and created Unity Catalog managed tables.
- Created Lakeflow Spark Declarative Pipeline Bronze, Silver, and Gold layers with Auto Loader streaming tables, data cleansing, validation, and business aggregates.
- Built a Databricks AI/BI “Food Delivery Analytics” dashboard covering overview, delivery agents, restaurants, customers, and locations.
- Orchestrated the Lakeflow Job with task dependencies and three retries, then deployed a Streamlit app as a Databricks App for public access.
- Documented the workflow with an architecture diagram, step-by-step README, and project structure.

**Tech stack:** AWS S3 · boto3 · Databricks · Unity Catalog · Auto Loader · Lakeflow Pipelines & Jobs · AI/BI Dashboards · Streamlit · Databricks Apps · Python

### 🍽️ DineDash ETL & Analytics Pipeline

**Active project**

- Engineered a medallion architecture pipeline using Databricks DLT to ingest streaming JSON and static CSV files from landing zones.
- Implemented strict Silver-layer data quality constraints to filter null records and normalize complex datasets.
- Used full joins across customer, restaurant, and delivery-agent dimensions to enrich order data.
- Designed Gold-layer views for daily revenue trends and top-selling items to power an interactive AI/BI metrics dashboard.
- Automated pipeline execution and dashboard refreshes with Databricks Job Workflows.

### 🎓 Full Stack Data Engineer Trainee

- Configured Databricks external locations and securely ingested raw datasets from Azure Cloud environments.
- Simulated production support workflows by logging pipeline failures, creating ServiceNow incident tickets, and maintaining runbooks.
- Monitored scheduled pipelines, verified file arrivals, and validated successful data loads.
- Performed SQL-based first-level validation, troubleshooting, and source-to-target reconciliation.

### 🏥 Data Analyst Projects

- Conducted MySQL analysis to investigate healthcare and insurance dataset anomalies and optimize queries.
- Used Python, Pandas, NumPy, and Matplotlib for data cleaning, anomaly detection, and validation checks.

## 🎓 Education

**B.Tech in Electrical & Electronics Engineering**

Pragati Engineering College · November 2021 – June 2025 · **CGPA: 7.5/10**

## 📜 Certifications

- **Databricks:** Databricks Fundamentals · Databricks Fundamentals Accreditation
- **Microsoft:** Azure DP-750 Certification
- **Udacity:** Data & AI Foundations for Actionable Insights · DevOps for Actionable Insights
- **DataCamp:** SQL · Python · SQL for Data Science · Intermediate Python
- **Accenture:** Delivery Learning
- **Deloitte:** Data Analysis Job Simulation

## 📫 Let's Connect

I'm interested in data engineering, analytics, cloud data platforms, and projects that solve real-world problems.

- 💼 [LinkedIn](https://www.linkedin.com/in/kishore-donipudi-2a9009307)
- 🐙 [GitHub](https://github.com/Kishore-donipudi)
- 📧 [Email](mailto:kishoredonipudi921@gmail.com)
