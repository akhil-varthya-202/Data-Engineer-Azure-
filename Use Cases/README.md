# 📁 Real-Time Azure Data Engineering Use Cases

This folder contains practical, scenario-based use cases built on Azure Data Factory and its ecosystem. Each use case is focused on solving real-world data engineering problems — such as notifications, incremental loads, scheduling automation, and cross-database integration — using Azure-native services like Logic Apps, Triggers, Azure SQL, and MySQL.

---

## 📌 Use Case Index

| No. | Use Case Title | Description |
|-----|----------------|-------------|
| 1️⃣ | Multiple Tables (MySQL ➝ Azure SQL) | Demonstrates copying data from multiple MySQL tables into Azure SQL using parameterized pipelines. |
| 2️⃣ | Incremental Load | Implements delta data loading using Watermark/Last Modified Date logic for efficient processing. |
| 3️⃣ | Automate Pipeline using Logic Apps & Triggers | Shows how to schedule, automate, and monitor ADF pipelines using Logic Apps and Event-based triggers. |
| 4️⃣ | Pipeline Status Notification via Logic Apps | Sends automated email or Teams notifications based on pipeline success/failure using Azure Logic Apps. |
| 5️⃣ | Copy Data from Last 2 Days | Dynamic pipeline that filters and loads only the last 2 days' data using expressions and date functions. |

---

## 🔧 Tools & Services Used

- **Azure Data Factory (ADF)**
- **Azure Logic Apps**
- **Azure SQL Database**
- **MySQL (on-prem or cloud)**
- **Triggers (Scheduled, Event-based)**
- **Dynamic content expressions (for date filtering & parameters)**

---

## 🧠 Concepts Demonstrated

- Dynamic parameterization for looping through multiple tables
- Incremental data loading (Watermark pattern)
- Event-driven orchestration via Logic Apps
- Notifications based on pipeline run status (success/failure)
- Time-window-based data filtering
- End-to-end pipeline automation

---

## 🗂 Folder Contents

usecases/
├── Multiple Tables (MySQL ➝ Azure SQL Database) - Use Case (1).pdf
├── Incremental Load - Use Case (2).pdf
├── Automate Pipeline Using Logic Apps and Triggers - Use Case (3).pdf
├── Pipeline Status Notification via Logic Apps - Use Case (4).pdf
├── Copy Data from Last 2 Days - Use Case (5).pdf
---

## ✅ Ideal For

- Azure Data Engineer interviews (scenario-based prep)
- Proof-of-concept and client demos
- Practical learning of ADF + Logic Apps integration
- Setting up alerting and automation in enterprise-grade pipelines

---

## 📬 Feedback or Collaboration


> If this repository helps you, please consider giving it a ⭐️ and sharing it with your network!

