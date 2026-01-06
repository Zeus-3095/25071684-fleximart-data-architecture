FlexiMart Data Architecture Project

Student Name: Mohit Singh
Student ID: bitsom_ba_25071684
Email: singhmohit3094@gmail.com

Submission Date: 07 January 2026

1. Problem Understanding and Scope

This project addresses the design and implementation of an end-to-end data architecture solution for FlexiMart, a retail platform requiring support for operational reporting and analytical workloads. The scope includes data ingestion, transformation, storage, and analysis across relational, NoSQL, and data warehouse systems.

2. Architecture and Design Decisions

ETL Layer: Designed a structured ETL pipeline to cleanse, standardize, and load raw customer, product, and sales data into a relational database.

Relational Modeling: Applied normalization principles to ensure data integrity and efficient transactional queries.

NoSQL Modeling: Evaluated MongoDB for flexible product catalog representation and document-oriented access patterns.

Analytical Layer: Implemented a star schema–based data warehouse to support scalable analytical queries.

3. Implementation Details

Developed ETL processes using Python and Pandas.

Implemented relational schemas and business queries in MySQL.

Modeled semi-structured data and operations using MongoDB.

Created analytical SQL queries on the data warehouse schema.

4. Repository Structure
├── data/                   # Raw input datasets
├── part1-database-etl/     # ETL pipeline and RDBMS design
├── part2-nosql/            # NoSQL analysis and MongoDB modeling
├── part3-datawarehouse/    # Data warehouse schema and analytics
└── README.md               # Project documentation

5. Technologies Used

Python 3.x, Pandas

MySQL 8.0

MongoDB 6.0

6. Setup and Reproducibility

All setup steps and configurations have been implemented strictly in accordance with the assignment instructions to ensure reproducibility of results.

7. Key Learnings and Outcomes

Designed and implemented robust ETL pipelines for structured data processing.

Applied normalization and dimensional modeling techniques effectively.

Selected appropriate database technologies based on workload characteristics.

8. Challenges and Solutions

Inconsistent source data formats: Addressed through data validation and standardization logic in the ETL layer.

Scalable analytics design: Solved by adopting a star schema optimized for analytical query performance.
