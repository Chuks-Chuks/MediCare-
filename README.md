# Enterprise Data Warehouse and Analytics Platform for MediCare Analytics

## Project Overview

**MediCare Analytics** is a fictional healthcare organization managing patient records, treatment histories, and operational hospital data across a distributed network. This project focuses on designing and implementing a modern, Azure-based enterprise data warehouse to centralize disparate datasets, enable historical and real-time analytics, and ensure regulatory compliance in healthcare data management.

---

## Objectives

- Design and deploy an OLAP data warehouse using **Azure Synapse Analytics**.
- Develop scalable **batch and real-time ingestion pipelines** with **ADF** and **Databricks**.
- Build a hybrid **Star Schema** and **Data Vault 2.0** model for analytics and auditability.
- Integrate **Great Expectations** and **Purview** for data validation and governance.
- Deliver **Power BI dashboards** with real-time metrics from Synapse.
- Automate infrastructure and pipelines using **Terraform** and **Azure DevOps**.

---

## Architecture Overview

![Architecture Diagram](./architecture/architecture-diagram.png)

This architecture supports batch, streaming, and structured/semi-structured data ingestion through a layered data lake (Bronze → Silver → Gold), optimized for analytical queries and compliance.

---

## Tools & Technologies

| Category               | Tools/Services Used                                                                 |
|------------------------|--------------------------------------------------------------------------------------|
| Cloud & Storage        | Azure Data Lake Gen2, Azure Blob Storage                                            |
| Orchestration & ETL    | Azure Data Factory, Azure Databricks, Event Hubs                                    |
| Data Warehouse         | Azure Synapse Analytics (Dedicated SQL + Serverless SQL Pools)                      |
| Governance & Security  | Azure Purview, Azure Key Vault, Dynamic Data Masking                                |
| Monitoring & Ops       | Azure Monitor, Log Analytics, Great Expectations, Azure DevOps                      |
| Reporting & BI         | Power BI (DirectQuery + Real-Time Dashboards)                                       |
| Infrastructure as Code | Terraform, YAML pipelines                                                           |

---

## Repository Structure

