# EDA_and_DE_Pipeline
# Local Data for Better Health (CDC PLACES) — Distributed & Scalable Data Engineering Pipeline

This project implements a fully cloud-native **data engineering pipeline** for the CDC’s  
**PLACES: Local Data for Better Health** dataset (County-Level, 2020–2023).  
The goal is to design an **end-to-end distributed system** capable of ingesting, processing, 
storing, analyzing, and modeling large-scale multi-year health data using AWS services.

This project was completed as part of the  
**Distributed and Scalable Data Engineering** course,  
M.S. in Data Science, University of New Haven.

---

## 🚀 Project Highlights

- End-to-end **AWS Data Lake** (S3 Raw → Processed → Curated)
- **Distributed ETL** using AWS Glue (Spark)
- Schema enforcement, geolocation parsing, numerical cleaning
- **Optimized Parquet** datasets for fast analytics
- **Interactive querying** using Amazon Athena
- **Python analytics & visualization pipeline**
- **K-Means clustering** to segment U.S. counties by health indicators
- Covers all PLACES measures for all U.S. counties (2020–2023)

---

## 📊 Dataset Description: CDC PLACES

CDC’s PLACES dataset provides **model-based county estimates** for:

- Health Outcomes  
- Health Behaviors  
- Preventive Services  
- Social Needs  
- Disabilities  
- Health Status  

The dataset includes **36 measures** across all U.S. states and counties.  
Each annual release is ~50–60 MB and provided in CSV format.

---

## 🏗️ System Architecture
<img width="1290" height="1184" alt="CloudArchitecture" src="https://github.com/user-attachments/assets/0d75fea1-6fd4-41b4-a51d-db459cfcf50f" />
