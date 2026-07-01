# Data Warehouse Engineer

## Work Experience

**Data Warehouse Engineer @ NBC News - July 2022 - Present**
- Designed and maintained dbt models powering enterprise reporting, writing custom macros and Jinja-templated SQL for reusable transformation logic across Bronze, Silver, and Gold layers, with all models version-controlled, tested, and queryable via Databricks Unity Catalog.
- Built scalable Medallion Architecture (Bronze/Silver/Gold) on AWS using PySpark and Delta Lake in Databricks, transforming raw API and CRM data into curated datasets consumed by analytics teams.
- Configured and deployed Databricks Genie Spaces with curated datasets and semantic layers, enabling self-service analytics for non-technical stakeholders and reducing ad-hoc data request volume.
- Centralized data governance using Databricks Unity Catalog, streamlining access controls and ensuring consistent security across curated data layers.
- Built and optimized ETL/ELT pipelines in Databricks, reducing runtime by 35% and enabling faster reporting in Looker and Domo.
- Applied performance tuning and cost optimization to Spark jobs and SQL transformations, reducing compute cost and improving data freshness.
- Orchestrated complex data workflows using Apache Airflow and Databricks Workflows, building reliable job pipelines to ensure SLA compliance.
- Improved data discoverability by 40% by automating ingestion into AWS S3 and implementing AWS Glue crawlers.
- Designed and deployed Dockerized data services using GCP Cloud Run, enhancing modularity and reducing infrastructure overhead.
- Integrated AI coding assistants and agents into data engineering workflows, building custom agents with Model Context Protocol (MCP) integrations to accelerate development and enable self-service data tooling.

**BI Data Engineer @ Blue Cross Blue Shield of Alabama - March 2020 - July 2022**
- Automated ETL processes using Python and Apache Airflow on AWS EC2, reducing manual intervention and improving processing speed by 40%.
- Processed JSON data with Python, extracting key fields to enhance data cleansing and transformation.
- Utilized AWS Glue for reliable, high-performance ETL operations, ensuring pipeline integrity.
- Configured Amazon QuickSight for analytics, designing visualizations including charts and drill-down reports.
- Designed and developed interactive dashboards in Looker and Domo, improving data accessibility and decision-making.
- Created and monitored AWS Glue jobs to maintain data quality and optimize performance.
- Used Python scripting for ad hoc data analysis, delivering timely insights to stakeholders.
- Performed unit testing on all developed programs to ensure quality and adherence to specifications.
- Built and optimized WebFOCUS dashboards and portals with KPIs and visuals using App Studio.
- Managed schedules in ReportCaster to automate report generation, streamlining delivery into the Report Library for timely access.

**SQL DBA/BI Developer @ Amtex Systems Inc - March 2017 - February 2020**
- Enhanced MS SQL Server performance by optimizing query response times and transaction processing speed.
- Implemented robust Transactional Replication and disaster recovery strategies for SQL Database servers.
- Designed and engineered databases, tables, and stored procedures to improve system functionality and efficiency.
- Conducted in-depth SQL query analysis and optimization, improving data quality and processing efficiency by 50%.
- Developed a performance monitoring dashboard using the TICK stack and Grafana for real-time operational insights.
- Built Business Portals and BI dashboards in WebFOCUS AppStudio and InfoAssist+, increasing user engagement by 40%.
- Enhanced dashboard UI/UX with HTML, CSS, JavaScript, and jQuery, reducing support tickets by 25%.
- Supported .NET web applications in C#, leveraging MVC patterns and Entity Framework.
- Ensured high availability and scalability by optimizing ETL processes and monitoring system health.

## Education
Computer Science <br/>
Lamar University • US, TX, Beaumont • 2016

## Skills

- Data Engineering : Data pipelines, ETL/ELT, data quality, data modeling, working with nested and unstructured data
- Database Management : SQL, PostgreSQL, MS SQL Server
- Transformation & Orchestration : dbt, Apache Airflow, Databricks Workflows
- Data Modeling : Medallion Architecture, Star Schema, ER Diagrams
- Distributed Computing : Spark, PySpark, Spark SQL in Databricks
- Cloud Computing : AWS S3, AWS Glue, AWS Athena, AWS Lambda, GCP Cloud Run
- Data Platforms : Databricks, Delta Lake, Unity Catalog, Genie Spaces
- Programming Languages : Python, PySpark, SQL
- Containerization : Docker
- Version Control : Git, GitHub, GitHub Actions
- BI & Analytics : Looker, Domo, Amazon QuickSight
- AI Tooling : AI Coding Agents, Model Context Protocol (MCP)

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

