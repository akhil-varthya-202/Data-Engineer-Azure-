
# 📁 Azure Data Engineering Pipelines

This folder contains a curated collection of real-world data integration and transformation pipelines implemented using the Microsoft Azure ecosystem. Each pipeline is documented in PDF format and demonstrates end-to-end scenarios using services like Azure Data Factory (ADF), Synapse Analytics, Databricks, Streaming Analytics, IoT Hub, Azure SQL Database, Power BI, and more.

---

## 📌 Pipeline Index

| No. | Pipeline Name | Description |
|-----|----------------|-------------|
| 1️⃣ | Blob ➝ Azure SQL (Using Dataflow) | ADF pipeline using Mapping Data Flows for transformation and loading. |
| 2️⃣ | Blob ➝ Azure SQL (Using Power Query) | ADF pipeline with Power Query-based data wrangling. |
| 3️⃣ | Blob ➝ Azure SQL (Dataflow + Power Query) | Hybrid approach combining Data Flows and Power Query. |
| 4️⃣ | Blob/Data Lake ➝ Azure SQL (Dataflow) | Ingests from blob and data lake to Azure SQL using Data Flows. |
| 5️⃣ | MySQL ➝ Azure SQL | Data migration pipeline from MySQL to Azure SQL. |
| 6️⃣ | On-Prem MySQL ➝ ADF ➝ Blob | Integration of on-prem MySQL with Azure via SHIR and blob sink. |
| 7️⃣ | Cosmos DB ➝ ADF ➝ Blob | Pulls data from Cosmos DB to Blob using ADF. |
| 8️⃣ | Blob ➝ Databricks ➝ Azure SQL | Uses Databricks notebooks to transform and load data. |
| 9️⃣ | ADLS ➝ Azure SQL (Synapse DF) | Data pipeline using Synapse Data Flows. |
| 🔟 | ADLS ➝ Azure SQL (Synapse Spark Pool) | Uses Spark notebooks in Synapse Analytics for transformation. |
| 1️⃣1️⃣ | IoT Hub ➝ Data Lake (Streaming Analytics) | Real-time streaming ingestion from IoT Hub to Data Lake. |
| 1️⃣2️⃣ | IoT Hub ➝ Power BI (Streaming Analytics) | Real-time analytics from IoT Hub directly to Power BI dashboard. |

---

## 🔧 Tools & Services Used

- **Azure Data Factory (ADF)**
- **Azure Synapse Analytics** (Spark & Data Flows)
- **Azure Databricks**
- **Azure Streaming Analytics**
- **Azure IoT Hub**
- **Azure SQL Database**
- **Azure Data Lake Storage (ADLS)**
- **Azure Blob Storage**
- **Power BI**
- **MySQL (On-Prem and Cloud)**
- **Cosmos DB**

---

## 🧠 Use Case Coverage

- Batch and real-time data ingestion
- ETL & ELT pipeline design
- Power Query and Mapping Data Flows
- IoT-based streaming integration
- Spark-based transformation using Synapse & Databricks
- Data movement from on-premises to cloud
- Visualization and analytics in Power BI

---

## 🗂 Folder Structure

Pipelines/
├── 1st pipeline (blob2asql) using Dataflow.pdf
├── 2nd pipeline (blob2asql) using powerquery .pdf
├── 3rd pipeline (blob2asql) using dataflow and powerquery.pdf
├── ...
├── 12th pipeline IOT Hub to Power BI using azure streaming analytics.pdf
---

## ✨ Contribution & Usage

These pipeline documents can be referenced for:

- Learning Azure Data Engineering patterns
- Interview preparation
- Internal documentation or training
- Project blueprint inspiration

> 📌 If you find this repository helpful, feel free to ⭐️ the repo and share it with others.

---

## 📬 Contact

For suggestions or custom use cases, feel free to reach out via GitHub Issues or Discussions tab.

