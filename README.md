# Real-Time YouTube Trending Data Pipeline

This project simulates a real-time data engineering pipeline that ingests trending YouTube video data, processes it, and stores it in a PostgreSQL database using Kafka, Airflow, and Python.

## Project Overview

**Objective:**  
Simulate near real-time streaming of YouTube trending video data → clean and transform it → store in PostgreSQL → optionally visualize using **Grafana**, **Power BI**, or **Tableau**.

## 🛠 Tech Stack

- **Apache Kafka** – Stream data in real time
- **Apache Airflow** – Schedule and manage workflows
- **Python** – Build ETL logic and Kafka producer
- **PostgreSQL** – Store structured, cleaned data
- **Docker** – Containerize the entire stack
- **Grafana / Power BI / Tableau** *(optional)* – Visualize top trending content
