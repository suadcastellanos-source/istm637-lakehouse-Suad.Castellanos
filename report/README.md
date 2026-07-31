# ISTM 637 – Databricks Lakehouse Project

**Student:** Suad Castellanos

## Project Overview

This project demonstrates the implementation of an end-to-end analytics solution using the Databricks Lakehouse Platform. The project includes data ingestion, data transformation, metadata management, natural language analytics with Genie, interactive dashboards, machine learning, and a Databricks application for visualizing historical and forecasted oil production.

---

# Part 5 – AI Dashboard

An interactive dashboard was created using Databricks AI/BI Dashboards.

The dashboard includes:

- KPI cards for Total Oil Production, Total Gas Production, Total Water Production, and Total Wells.
- A monthly oil production trend visualization.
- Oil production summarized by basin.
- Wells summarized by operator.
- A global **year_month** filter allowing users to interactively filter all visualizations.

The dashboard was successfully published within Databricks.

---

# Part 6 – Prediction Model

The provided predictive modeling notebook was executed to train a machine learning model that forecasts oil production.

Model evaluation results:

- Mean Absolute Error (MAE): **33.5**
- Root Mean Squared Error (RMSE): **70.0**
- R² Score: **0.933**

The trained model was successfully registered in Unity Catalog as:

**oil_rate_predictor**

The model was assigned the **@champion** alias and used to generate a forecast table (`well_forecast`) containing future production predictions.

---

# Part 7 – Databricks Application

A lightweight Streamlit application was generated using Genie and deployed to Databricks Apps.

The application was designed to:

- Display a dropdown containing available wells.
- Query historical production data from Unity Catalog.
- Display forecasted production from the `well_forecast` table.
- Visualize historical production, forecasted production, and a combined comparison chart.

The application deployed successfully in Databricks Apps.

Because this project was completed using Databricks Free Edition, the deployed application encountered a known Unity Catalog permissions limitation affecting Databricks App service principals. This limitation was acknowledged by the instructor in the course announcements and does not prevent successful deployment of the application.

---

# Technologies Used

- Databricks Lakehouse Platform
- Unity Catalog
- Delta Lake
- SQL
- Python
- Streamlit
- Plotly
- MLflow
- Databricks Apps
- Genie Agents
- GitHub

---

# Conclusion

This project demonstrates an end-to-end analytics workflow within Databricks, including data engineering, business intelligence, machine learning, and application deployment. The completed solution integrates data ingestion, dashboard development, predictive analytics, and application development using the Databricks ecosystem.
