# Hi, I'm Danny Han

**Data Engineer & Business Intelligence Analyst | PySpark, SQL, GCP, BigQuery, Power BI**  
**Microsoft Certified: Power BI Data Analyst Associate**

I build data systems that turn operational data into reliable analytical datasets and decision-ready reporting. My work spans data engineering, SQL data modelling, data-quality controls, dimensional design, PySpark pipelines, cloud warehousing, KPI development, dashboarding, validation, and documentation.

I am currently completing an Honours Bachelor of Science in Computer Science and Statistics at the University of Toronto Mississauga. I am particularly interested in data engineering and analytics roles where I can build trustworthy pipelines, model data carefully, and make downstream analysis easier to use and defend.

I care about the engineering details that make data trustworthy: explicit schemas, correct grain, sound keys and relationships, reproducible transformations, strong validation, and documentation that someone else can actually follow.

## Featured projects

### [NullMarket — Retail Data Engineering Platform](https://github.com/code-of-toad/nullmarket-retail-data-engineering-platform)

**PySpark • Apache Spark • SQL • Google Cloud Storage • BigQuery • Parquet • pytest**

A batch retail data engineering platform that ingests five simulated operational sources, validates and quarantines bad records, transforms trusted data with PySpark, persists curated Parquet to Google Cloud Storage, and loads a dimensional BigQuery warehouse for analytical SQL.

`Synthetic Sources → GCS Raw → PySpark / Managed Spark → Data Quality → Curated Parquet → BigQuery → Analytical SQL`

- Built explicit PySpark `StructType` schemas and reusable data-quality validation for required fields, key uniqueness, referential integrity, and business rules
- Designed conformed date, product, and store dimensions with separate sales and inventory fact tables at defensible grains
- Reused the same transformation logic for local Spark and Google-managed Spark execution
- Implemented raw, rejected, and curated GCS storage layers with rejected-record quarantine and inspectable validation reasons
- Persisted curated datasets as Parquet and validated schema, grain, row counts, business measures, and round-trip values
- Built partitioned and clustered BigQuery fact tables for analytical SQL
- Added automated pytest coverage, warehouse reconciliation, idempotent reruns, and deterministic batch-scoped incremental processing
- Implemented retry-safe insert-only BigQuery `MERGE` loading using deterministic business keys

### [ClinicalPulse — Healthcare Business Intelligence Platform](https://github.com/code-of-toad/clinical-pulse-healthcare-bi)

[![ClinicalPulse Executive Overview](https://raw.githubusercontent.com/code-of-toad/clinical-pulse-healthcare-bi/main/powerbi/screenshots/executive_overview.png)](https://github.com/code-of-toad/clinical-pulse-healthcare-bi)

A governed hospital BI platform built with synthetic EHR data, SQL Server, Python, and Power BI.

- Built bronze, silver, and gold SQL Server data layers from seven source entities
- Designed a reporting-ready dimensional model with 20 gold-layer objects
- Developed seven Power BI report pages for patient flow, length of stay, readmissions, service utilization, observation activity, and reporting trust
- Reconciled governed KPI logic across SQL and DAX
- Implemented ingestion auditing, data-quality controls, lineage, asset scorecards, and security documentation
- Delivered the project through Git, GitHub, and Azure DevOps Boards

### [Anti-Money Laundering Risk Detection and Decision-Support Pipeline](https://github.com/code-of-toad/AML-Detection-Pipeline-Project)

<p align="center">
  <a href="https://github.com/code-of-toad/AML-Detection-Pipeline-Project">
    <img src="assets/aml_pipeline_overview.jpg" alt="AML risk detection and explanation pipeline architecture" width="100%">
  </a>
</p>

An end-to-end AML analytics system that combines domain-informed risk rules with unsupervised machine-learning models to identify and explain potentially suspicious customer behaviour.

- Earned a top-five placement in an AML analytics competition hosted by the University of Toronto IMI BigDataAIHub and Scotiabank, involving approximately 490 participants across 90 teams
- Built reproducible workflows for feature preparation, behavioural clustering, rule-based risk scoring, anomaly detection, score fusion, and output generation
- Combined rule-based indicators with model-generated anomaly scores to produce interpretable customer risk assessments
- Created plain-language explanations that connect model outputs to AML red-flag categories for non-technical reviewers
- Built an explanation viewer for browsing, filtering, and searching customer-level risk explanations
- Designed a modular model interface that allows additional detection algorithms to be incorporated without changing the core pipeline

<p align="center">
  <a href="https://github.com/code-of-toad/AML-Detection-Pipeline-Project">
    <img src="assets/aml_explanations_viewer.png" alt="AML customer risk explanation viewer" width="78%">
  </a>
</p>

### [CSSU Rewards System API](https://github.com/code-of-toad/project_ecommerce_system_backend)

A RESTful backend API for a points-based rewards platform, designed around secure access, relational data integrity, and maintainable business logic.

- Built the application with Node.js, Express.js, Prisma ORM, and SQLite using a layered routes, controllers, services, and middleware architecture
- Implemented JWT authentication, password hashing, input validation, and four-tier role-based access control
- Designed a relational schema for users, transactions, promotions, events, and password-reset tokens with version-controlled migrations
- Developed transaction, promotion, and points-management workflows with pagination, validation, and consistent error handling

## Additional analytics work

| Project | What it demonstrates | Core tools |
|---|---|---|
| [Student Mental Health Analysis](https://github.com/code-of-toad/data_analysis_student_mental_health) | Statistical analysis of survey data from 1,192 students, including hypothesis tests, effect sizes, scale scoring, and visual reporting | R, tidyverse, ggplot2 |
| [PSY100 Student Well-Being Analysis](https://github.com/code-of-toad/psy100_data_analysis_infographic) | Data cleaning, descriptive statistics, correlation, resampling, visualization, and communication through a one-page infographic | R, ggplot2, statistical analysis |
| [SQL Server RetailOps Practice](https://github.com/code-of-toad/sql-server-retailops-practice) | A structured SQL Server learning environment covering schemas, constraints, joins, CTEs, window functions, and business-style analysis | SQL Server, T-SQL |

## Technical toolkit

| Area | Tools and capabilities |
|---|---|
| Data engineering | PySpark, Apache Spark, Parquet, batch processing, data quality, dimensional modelling, incremental processing |
| Cloud and warehousing | Google Cloud Platform, Google Cloud Storage, BigQuery |
| Business intelligence | Power BI, DAX, Power Query, dashboard design, KPI development |
| Data and databases | SQL Server, T-SQL, SQL, relational modelling, ETL/ELT |
| Analysis | Excel, Python, pandas, R, statistical analysis, data visualization |
| Development | Git, GitHub, Azure DevOps, JavaScript, C, Java, Bash |

## Certifications

- Microsoft Certified: Power BI Data Analyst Associate (PL-300)
- LearnSQL.com Certificate of Competency in SQL

## A little more about me

Outside analytics, I make music, build small games, and tend to turn anything I want to learn into a project. I value curiosity, dependable work, and the ability to explain technical ideas without making them needlessly complicated.

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Danny_Han-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dannyhan-data/)
[![Portfolio](https://img.shields.io/badge/Portfolio-code--of--toad.github.io-24292F?style=flat&logo=githubpages&logoColor=white)](https://code-of-toad.github.io/)
[![Email](https://img.shields.io/badge/Email-codeoftoad%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:codeoftoad@gmail.com)
