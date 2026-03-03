# Rocío Baigorria  
**Data Engineer | AWS Data Platforms | Streaming & Batch Architectures**

I design and operate **AWS-native data platforms** that support analytics, real-time processing, and machine learning under real operational constraints.

My work focuses on building systems that are **reliable, observable, and cost-aware** — designed not as demos, but as platforms that teams could realistically run in production.

I transitioned into data engineering from an engineering background by building complete end-to-end systems: ingestion, processing, storage, observability, and infrastructure automation.

**Core principle:** data systems must survive failures, scale predictably, and remain understandable by the teams operating them.

---

## What I Build

I design systems that:

- Ingest and process data reliably (batch and streaming)
- Support analytics and ML workloads
- Follow cloud-native and event-driven architecture principles
- Optimize cost, scalability, and operational visibility
- Are deployable and maintainable by real teams

My work sits at the intersection of **Data Engineering, Distributed Systems, and AWS Cloud Architecture**.

---

## Selected Projects

### Ecommerce Data Warehouse — AWS Redshift Serverless
**Production-style analytics warehouse with incremental pipelines**

Designed a modern ecommerce warehouse handling evolving datasets and late-arriving events using AWS-native architecture.

**Key Decisions**
- Star schema modeling for analytical performance
- Incremental ingestion to reduce compute cost
- Late-arriving data handling strategy
- Infrastructure defined with Terraform

**Architecture Highlights**
- Redshift Serverless
- Incremental pipelines
- Data modeling (facts & dimensions)
- IaC and reproducible environments

**Tech:** AWS Redshift, S3, Terraform, SQL, Data Modeling  
Repository: https://github.com/tuni56/ecommerce-data-warehouse-redshift

---

### Serverless Data Lake Platform
**AWS-native data lake designed for analytics workloads**

Built a cost-efficient serverless data lake separating raw and curated layers with automated metadata discovery.

**Key Decisions**
- Serverless-first architecture to eliminate idle compute
- Columnar storage (Parquet) for query efficiency
- Automated schema discovery using Glue Crawlers

**Architecture Highlights**
- S3 data lake layers
- AWS Glue catalog & ETL
- Athena querying
- Infrastructure automation

**Tech:** AWS S3, Glue, Athena, CloudFormation, Python  
Repository: https://github.com/tuni56/serverless-aws-data-lake-with-kiro

---

### Real-Time Event-Driven Data Pipeline
**Streaming platform for high-velocity event processing**

Designed a real-time ingestion and processing system capable of handling burst traffic while maintaining observability and reliability.

**Key Decisions**
- Event-driven decoupling using Kafka
- Schema evolution with Schema Registry
- Monitoring-first design

**Architecture Highlights**
- Streaming ingestion
- Event routing and processing
- Production-style monitoring dashboards

**Tech:** Kafka, Python, Redis, Grafana, Terraform  
Repository: https://github.com/tuni56/real-time-event-driven-data-pipeline

---

### IoT Data Architecture on AWS
**Long-term scalable ingestion architecture for sensor data**

Designed a cost-optimized architecture to ingest and query multi-year IoT datasets.

**Key Decisions**
- Storage lifecycle optimization
- Serverless ingestion patterns
- Queryable historical storage

**Focus Areas**
- Scalability
- Cost optimization
- Long-term data retention strategy

**Tech:** AWS Serverless, Data Lake Architecture, Kafka  
Repository: https://github.com/tuni56/iot-data-architecture-aws

---

### AWS Serverless Cost Dashboard
**Operational visibility for cloud spending**

Built an automated dashboard to monitor and analyze AWS costs using event-driven processing.

**Highlights**
- Automated cost ingestion
- Serverless processing pipeline
- Operational monitoring mindset

**Tech:** AWS Lambda, S3, CloudWatch, SNS, Python  
Repository: https://github.com/tuni56/AWS-Cost-Dashboard-Serverless-

---

## Technical Stack

### Data Engineering
- Python, SQL
- Batch & Streaming Pipelines
- Data Modeling (Star Schema)
- Event-Driven Architectures
- Kafka Ecosystem

### Cloud & Infrastructure
- AWS (S3, Lambda, DynamoDB, Redshift, Glue, Athena, SageMaker)
- Infrastructure as Code (Terraform, CloudFormation)
- IAM & Least-Privilege Design
- Serverless Architectures

### Observability & Operations
- Monitoring & Metrics (Grafana, CloudWatch)
- Failure handling & retries
- Cost-aware architecture decisions

### Distributed Systems Background
- Java
- Spring Boot / Spring Cloud
- Microservices & Messaging Systems

---

## Current Focus

- AWS-native data platform design
- Infrastructure as Code maturity
- Observability-driven architectures
- Preparing for Data Engineer / Data Platform Engineer roles

---

## Location & Availability

Argentina (GMT-3) — Open to Remote Roles and Relocation

US Citizen open to relocating to the United States.  
Relocation support required during transition.

- LinkedIn: https://www.linkedin.com/in/rociobaigorria/
- Email: rociomnbaigorria@gmail.com

---

## Engineering Philosophy

Data systems are not pipelines — they are **living systems**.

They must handle pressure, failures, scale changes, and human operators.  
My goal is to design platforms where data flows reliably and decisions can happen with confidence.

![GitHub Space Invaders](game.gif)

---
