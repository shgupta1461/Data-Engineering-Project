# Data-Engineering-Project
ETL Pipeline design on AWS

## Project: End-to-End E-Commerce Analytics Platform on AWS

### Objective: To design, implement, and automate a scalable data platform to process a multi-table e-commerce dataset, transforming raw data into actionable business insights and demonstrating core principles of large-scale data engineering.

### Key Accomplishments & Responsibilities:
- Data Infrastructure & ETL Pipelines:
- Architected a serverless data pipeline on AWS to ingest, transform, and load data from a wide variety of sources, mirroring the charter of Amazon's UDAI.
- Designed and built a robust ETL job using AWS Glue (a managed Spark service) to join, clean, and process multiple raw datasets (orders, products, customers, order_items).
- Implemented data quality improvements by renaming columns and handling data inconsistencies, ensuring the final dataset was reliable and user-friendly.

### Scalability & Performance Optimization:
- Leveraged Amazon S3 to build a structured Data Lake, organizing data into raw, processed, and analytics zones for efficient management and access control.
- Transformed data into the columnar Apache Parquet format, significantly improving query performance and reducing storage costs, a key practice for managing petabyte-scale data efficiently.
- Utilized Amazon Athena for serverless, interactive querying, enabling efficient data exploration and experimentation on large datasets without managing underlying infrastructure.

### Automation & Operational Excellence:
- Automated the schema discovery process using an AWS Glue Crawler, eliminating manual effort and ensuring the data catalog remained synchronized with the source data.
- Designed the pipeline for full automation, where the next logical step would be orchestration with AWS Step Functions to reduce operational overhead and ensure data availability.
- Focused on building a cost-effective solution by prioritizing serverless technologies (Glue, Athena, S3), aligning with the need to manage massive data infrastructure economically.

### Data Modeling & Analytics Enablement:
- Performed logical data modeling by joining disparate data sources into a denormalized, analytics-ready table, simplifying data access for business users.
- Enabled business intelligence by connecting Amazon QuickSight to the processed data layer, creating interactive dashboards to visualize key metrics like revenue by product category, order status distribution, and customer geography.

### Technical Environment:
- Cloud Platform: Amazon Web Services (AWS)
- Core Services: S3, AWS Glue (ETL & Data Catalog), Amazon Athena, Amazon QuickSight
- Data Formats: CSV, Apache Parquet
- Languages: SQL (in Athena), Python (underlying language for AWS Glue)
