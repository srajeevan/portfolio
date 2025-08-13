# Data Engineer

## Work Experience

**Data Warehouse Engineer @ Insight Global - July 2022 - Present**
- Implemented **Medallion Architecture** on **AWS**, transforming raw API and CRM data (JSON, Parquet, CSV) into curated **Silver** and **Gold Delta tables** using **PySpark** in **Databricks**.
- Developed **scalable ETL pipelines** in Databricks to generate Delta tables for Silver and Gold layers, enabling faster reporting and ad hoc analysis in **Looker** and **Domo**.
- Optimized large-scale data transformations with **PySpark**, reducing ETL runtime by **35%** and improving downstream data freshness.
- Streamlined raw data ingestion to **AWS S3** and automated metadata management via **AWS Glue crawlers**, improving **Athena** data discoverability by **40%**.
- Maintained and extended **Apache Airflow DAGs** to orchestrate complex workflows, ensuring SLA compliance and reducing pipeline maintenance by **40%**.
- Orchestrated data workflows in **Apache Airflow**, improving pipeline reliability and reducing manual interventions by **50%**.
- Built a **unified subscription reporting model** consolidating metrics across products, enhancing stakeholder visibility into customer behavior and retention trends.
- Engineered an **OLAP subscription data model** to replace legacy architecture, cutting query time by **45%** and improving reporting accuracy.
- Designed an **eCommerce data model** to track affiliate performance, revenue, and commissions, improving ROI tracking accuracy by **30%**.
- Created **SQL views** and **Athena-accessible datasets** to support flexible querying and validation of curated data layers for analysts and data scientists.
- Collaborated with BI teams to integrate curated datasets into **Domo** and **Looker** dashboards, reducing report delivery time by **35%**.
- Leveraged **Databricks Unity Catalog** to centralize data governance, streamline access control, and ensure consistent security and compliance across Silver and Gold layers.
- Implemented **GCP Cloud Run** services to support modular ETL/ELT operations with emphasis on reusability.
- Built and maintained **Docker containers** for encapsulating custom scripts and services, ensuring consistent deployment across local and cloud platforms.
- Programmed **Cloud Run** deployments for data transformation functions, reducing infrastructure overhead and manual intervention.

**BI Engineer @ Marchon Partners - March 2020 - July 2022**
- Automated **ETL processes** using **Python** and **Apache Airflow** on **AWS EC2**, reducing manual intervention and improving processing speed by **40%**.
- Processed **JSON** data with Python, extracting key fields to enhance data cleansing and transformation.
- Utilized **AWS Glue** for reliable, high-performance ETL operations, ensuring pipeline integrity.
- Configured **Amazon QuickSight** for analytics, designing visualizations including charts and drill-down reports.
- Designed and developed **interactive dashboards** in **Looker** and **Domo**, improving data accessibility and decision-making.
- Created and monitored **AWS Glue jobs** to maintain data quality and optimize performance.
- Used **Python scripting** for ad hoc data analysis, delivering timely insights to stakeholders.
- Performed **unit testing** on all developed programs to ensure quality and adherence to specifications.
- Built and optimized **WebFOCUS** dashboards and portals with KPIs and visuals using **App Studio**.
- Managed schedules in **ReportCaster** to automate report generation, streamlining delivery into the Report Library for timely access.

**SQL DBA/BI Developer @ Amtex Systems Inc - March 2017 - February 2020**
- Enhanced **MS SQL Server** performance by optimizing query response times and transaction processing speed.
- Implemented robust **Transactional Replication** and disaster recovery strategies for SQL Database servers.
- Designed and engineered **databases**, **tables**, and **stored procedures** to improve system functionality and efficiency.
- Conducted in-depth **SQL query analysis and optimization**, improving data quality and processing efficiency by **50%**.
- Developed a **performance monitoring dashboard** using the **TICK stack** and **Grafana** for real-time operational insights.
- Built **Business Portals** and **BI dashboards** in **WebFOCUS AppStudio** and **InfoAssist+**, increasing user engagement by **40%**.
- Enhanced dashboard **UI/UX** with **HTML**, **CSS**, **JavaScript**, and **jQuery**, reducing support tickets by **25%**.
- Supported **.NET** web applications in **C#**, leveraging MVC patterns and **Entity Framework**.
- Ensured high availability and scalability by optimizing ETL processes and monitoring system health.

## Education
Computer Science <br/>
Lamar University • US, TX, Beaumont • 2016

## Skills

- Data Engineering : Analyze, Organize data, build data systems, data analysis, interpret trends and patterns, improving data quality, working
with nested data unstructured data.
- Database Management : SQL,PL SQL
- ETL Technologies : Airflow
- Data Modeling : Star Schema, Snowflake, ER Diagrams, UML Class Diagrams
- Distributed Computing : Spark, Pyspark in Databricks
- Cloud Computing : AWS services like S3, EC2, Athena, Redshift, Azure
- Programming Languages : Python, Pyspark, Javascript
- Containerization : Knowledge in Docker.
- Version Control : Git and GitHub
- Analytical Skills : Analytical and problem-solving skills, Looker, TIBCO Webfocus

## Projects

### AWS-Python_ETL_Pipeline_using_Airflow

This project demonstrates how to build and automate an ETL pipeline written in Python and schedule it using open source Apache Airflow orchestration tool on AWS EC2 instance.
#### AWS Services Used
- AWS EC2
- AWS S3
- Apache Airflow

#### Architecture Diagram

![Architecture_Diagram](https://github.com/srajeevan/AWS-Python_ETL_Pipeline_using_Airflow/assets/16627503/45e4047a-2d7b-4134-9b9f-d2ef31dba318)


### Youtube-Data-Analysis---AWS

This project securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.
Used a Kaggle dataset which contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.
Here is the link to the dataset
https://www.kaggle.com/datasets/datasnaek/youtube-new

#### Architecture Diagram

![Architecture_Diagram](https://raw.githubusercontent.com/srajeevan/Youtube-Data-Analysis-AWS/main/Assets/architecture_diagram.png)

#### AWS Services used in this project
- Amazon S3
- AWS Glue
- AWS Lambda
- AWS Athena
- AWS IAM
- Amazon QuickSight

