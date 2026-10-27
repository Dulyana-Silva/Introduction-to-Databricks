# Introduction-to-Databricks
Databricks is a unified, cloud-based data and AI platform that merges the scale of data lakes with the reliability and structure of data warehouses into a ***Data lakehouse Architecture.***

### What is a Data Lakehouse?

- Combines Two Worlds: Traditional data lakes store cheap, unformatted data, while data warehouses store clean, fast data tables. A lakehouse does both on top of low-cost cloud storage.
- Single Source of Truth: Data engineers, analysts, and AI/ML engineers work from the same governed dataset without syncing separate systems.

### Core Technologies

- Apache Spark: The foundational, high-speed engine for large-scale distributed data processing and streaming.
- Delta Lake: An open-format storage layer that brings reliability, versioning, and ACID transactions (guaranteeing safe, accurate database updates) to data lakes.
- MLflow: An open-source tool to manage, test, and deploy machine learning models.
- Unity Catalog: A unified governance and security system for data and AI assets across teams

----
  

 ----
Free Edition: Includes one serverless workspace (no classic compute clusters) with daily usage limits. It is excellent for learning, prototyping, and building the core logic (Python notebooks, basic ML models). However, it locks certain enterprise features and restricts heavy compute. 

Paid (Premium/Enterprise): Unlocks classic clusters (for heavy processing), Unity Catalog (advanced governance and role-based access control), Databricks Apps (hosting web UIs), and higher compute quotas. 

Cost Optimization Tip: In the paid version, use Serverless compute for scheduled tasks (it auto-scales to zero when idle) and only spin up clusters when actively developing.
