# Hi, I'm Nilesh Domah

I build portfolio data pipelines with Python, SQL, PySpark, and Azure. My projects focus on turning raw events into validated datasets, dimensional models, and reporting views.

I'm pursuing an **MS in Computer Science at the University of Colorado Boulder**, with expected completion in Mar 2028.

Based in **Minneapolis, MN** · Open to Chicago relocation and remote opportunities

## Featured project

### [Azure Patient Flow Data Pipeline](https://github.com/ndomah1/patient-flow-analytics-azure)

An end-to-end portfolio project using synthetic hospital events to demonstrate streaming ingestion, data quality checks, batch dimensional modeling, and analytics.

- **Ingestion:** Generates JSON events for 200 synthetic patients across seven departments and sends them to Azure Event Hubs.
- **Streaming:** Uses PySpark Structured Streaming and checkpointed writes to build Bronze and Silver Delta Lake layers.
- **Data quality:** Applies nine validation rules, deduplicates events, and retains rejected records with reasons for investigation.
- **Modeling:** Builds a batch Gold star schema with Type 2 patient history and fact-to-dimension joins using effective dates.
- **Analytics:** Provides Synapse SQL reporting views and a Power BI dashboard for patient volume, length of stay, and bed metrics.

**Stack:** Python · SQL · PySpark · Azure Databricks · Event Hubs · ADLS Gen2 · Delta Lake · Azure Synapse Analytics · Power BI

[View the repository](https://github.com/ndomah1/patient-flow-analytics-azure) · [View the dashboard](https://github.com/ndomah1/patient-flow-analytics-azure/blob/HEAD/power_bi/hospital_dashboard.png)

## Opportunities

I'm seeking **junior or associate data engineering roles** across industries. I'm also open to **data analyst and BI roles** involving SQL, data transformation, and modeling.

## Connect

[LinkedIn](https://www.linkedin.com/in/nileshdomah) · [Email](mailto:ndomah1@gmail.com)
