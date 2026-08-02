# ISTM 637 – Databricks Lakehouse Project

**Student:** Suad Castellanos

## Project Overview

This project demonstrates the implementation of an end-to-end analytics solution using the Databricks Lakehouse Platform. The project includes data ingestion, metadata management, natural language analytics with Genie, interactive dashboards, machine learning, application deployment, and secure data sharing.

---

## Project Summary

### Part 1 – GitHub Integration
Configured Git integration for the Databricks workspace and maintained the project using version control with multiple commits and pushes.

### Part 2 – Lakeflow Data Ingestion
Created a Unity Catalog catalog and schema, uploaded the provided CSV files, and ingested the data into Unity Catalog tables using a Lakeflow Declarative Pipeline.

### Part 3 – Metadata Management
Reviewed AI-generated metadata, updated table and column descriptions, and applied governance tags to improve data documentation.

### Part 4 – Genie Agent
Built a Genie Agent that answers natural language questions about the oil and gas production data using Unity Catalog tables and generated SQL queries to support analytical questions.

### Part 5 – AI Dashboard
Created an interactive AI/BI Dashboard containing KPI cards, production trends, basin comparisons, operator summaries, and interactive filtering. The dashboard was successfully published in Databricks.

### Part 6 – Prediction Model
Executed the provided machine learning notebook to train a regression model for oil production forecasting. The model achieved strong performance (R² ≈ 0.93), was registered in Unity Catalog with the **@champion** alias, and generated the **well_forecast** table used throughout the project.

### Part 7 – Databricks Application
Built and deployed a lightweight Streamlit application using Databricks Apps. The application queries Unity Catalog tables to display historical oil production alongside forecasted production for a selected well. The application deployed successfully, although Databricks Free Edition has a known service principal permission limitation acknowledged by the instructor.

### Part 8 – OpenSharing
Configured an OpenSharing share and attempted to add a Databricks recipient using a teammate's sharing identifier. Databricks Free Edition prevented completion because External Delta Sharing is not enabled on the managed metastore. Screenshots documenting the setup and system limitation are included with the project.

---

## Technologies Used

- Databricks Lakehouse Platform
- Unity Catalog
- Lakeflow Declarative Pipelines
- SQL
- Python
- Streamlit
- Plotly
- MLflow
- Databricks Apps
- Genie Agents
- OpenSharing
- GitHub

---

## Conclusion

This project demonstrates a complete end-to-end analytics workflow using the Databricks Lakehouse Platform. It integrates data engineering, governance, natural language analytics, business intelligence, machine learning, application deployment, and secure data sharing into a single solution.
```
