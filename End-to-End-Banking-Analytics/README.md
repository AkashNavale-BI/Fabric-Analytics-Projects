# End-to-End Banking Analytics using Microsoft Fabric & Power BI

## Project Overview
This project demonstrates an end-to-end banking analytics solution built using SQL Server, Microsoft Fabric, and Power BI. It covers data ingestion, transformation, data engineering, semantic modeling, automated pipeline execution, and interactive dashboard development.

## Technology Stack
- **SQL Server (SSMS):** Flat-file import, relational database storage, and SQL queries.
- **Microsoft Fabric Lakehouse:** Centralized analytical data storage.
- **Dataflow Gen2:** Data connectivity and data transformation using Power Query.
- **Fabric Data Pipeline:** Orchestration of dataflow execution and semantic model refresh.
- **Power BI Semantic Model:** Structured analytical model for reporting.
- **Power BI Desktop:** Interactive dashboard development and visualization.

## Project Workflow
1. **Data Source:** Five CSV files representing banking dimensions and transaction facts.
2. **SQL Server:** Imported CSV files into the `Banking_Domain` database and validated the data.
3. **Lakehouse:** Connected the data environment to Microsoft Fabric for analytical processing.
4. **Dataflow Gen2:** Connected to SQL Server, reviewed column data types, and applied transformations.
5. **Pipeline Orchestration:** Configured a pipeline to execute the dataflow followed by semantic model refresh.
6. **Semantic Modeling:** Prepared the model for analytical reporting.
7. **Dashboard:** Developed the Banking Insights report in Power BI Desktop.

## Dataset Tables
- `DimAccount`
- `DimBranch`
- `DimCustomer`
- `DimDate`
- `FactTransaction`

## Automation
A scheduled pipeline execution has been configured in Microsoft Fabric. It runs the dataflow and, upon successful completion, triggers the semantic model refresh.

## Repository Structure

```text
End-to-End-Banking-Analytics/
├── README.md
├── .gitignore
├── DimAccount.csv
├── DimBranch.csv
├── DimCustomer.csv
├── DimDate.csv
├── FactTransaction.csv
├── Banking_Insights.pbix
└── Banking_Insights.pdf
```

## Dashboard Preview

### Executive Overview
<img width="3075" height="1763" alt="executive-overview" src="https://github.com/user-attachments/assets/ec0a787e-bc47-4f05-861c-4b86e1116606" />

### Customer Insights
<img width="3075" height="1763" alt="customer-insights" src="https://github.com/user-attachments/assets/bf34a310-feba-43bd-8a53-c0852b770a75" />


## Key Learning Outcomes
- Importing and validating flat files in SQL Server.
- Connecting SQL Server data to Microsoft Fabric.
- Applying Power Query transformations and managing data types.
- Understanding Lakehouse-based analytics workflows.
- Configuring pipeline dependencies and scheduled execution.
- Preparing semantic models and building Power BI dashboards.

## Data Privacy
The project uses non-customer-specific sample data. No real customer records or confidential banking information are intentionally included.

## Disclaimer
This project is created for learning and portfolio demonstration purposes. Microsoft Fabric features and capabilities may vary depending on workspace configuration, licensing, and trial availability.
