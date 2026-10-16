**Fabric Analytics Projects**
A hands-on portfolio of projects built with Microsoft Fabric and related analytics tools. This repository brings together practical experiments and end-to-end solutions across data engineering, data integration, Lakehouse architecture, data transformation, semantic modelling, and business intelligence.
Each project lives in its own folder and includes project-specific documentation, implementation details, and supporting assets where applicable.

**What You'll Find Here**
Depending on the project, you may find examples of:
- **Data engineering**: ingesting, organising, and preparing data from different sources.
- **Data integration and transformation**: Data Factory pipelines, Dataflow Gen2, Power Query, and reusable transformation logic.
- **Lakehouse architecture:** using OneLake and Lakehouses to organise analytical data.
- **Data modelling**: building semantic models, defining relationships, and preparing data for analysis.
- **Business intelligence**: Power BI reports, interactive dashboards, DAX measures, and KPI analysis.
- **Workflow orchestration**: sequencing activities and configuring pipeline execution or refresh workflows.
- **Data quality and validation**: checking schemas, data types, consistency, and transformation results.
Not every project uses every technology. Each project's README describes its actual architecture and tools.

**Project Index**
Projects are documented independently. Open a project's folder and read its README.md for its objective, architecture, data sources, setup instructions, implementation notes, and results. As the portfolio grows, this section can be expanded into a linked index of projects.
**Typical Project Structure**
The structure varies by project, but a project folder may contain:
Fabric-Analytics-Projects/
├── README.md
└── Project-Name/
    ├── README.md          # Project-specific overview and setup
    ├── data/              # Sample data, when suitable for publication
    ├── reports/           # Power BI or other report files
    ├── notebooks/         # Notebooks, if used
    ├── pipelines/          # Pipeline definitions or screenshots, if available
    └── docs/               # Architecture diagrams, screenshots, and notes

Only include folders and artefacts that are relevant to each project. Tenant-bound Fabric assets, credentials, and machine-specific configuration may need to be recreated in the target environment rather than committed to GitHub.

**Tools and Technologies**
The toolset varies by project and may include:
- Microsoft Fabric
- Microsoft Power BI
- SQL Server and SQL Server Management Studio (SSMS)
- Data Factory pipelines and Dataflow Gen2
- OneLake and Fabric Lakehouse
- Power Query and DAX
- Git and GitHub for version control and documentation
Refer to each project README for the exact tools used.

**How to Explore a Project**
1. Open the project folder that interests you.
2. Read its README.md for the problem statement, architecture, prerequisites, and setup steps.
3. Review the included datasets and implementation assets.
4. Recreate or adapt the workflow in your own environment, following any project-specific requirements.

**Data, Credentials, and Responsible Sharing**
- Publish only datasets you own, are permitted to share, or that are explicitly intended for public/demo use.
- Check CSVs, workbooks, notebooks, screenshots, and report files for personal, confidential, or regulated information before publishing.
- Never commit passwords, access tokens, connection strings containing secrets, gateway recovery keys, or other credentials. Use placeholders in documentation and keep secrets in an appropriate secure store.
- Fabric workspaces, gateways, connections, schedules, and capacity assignments can be tenant- or machine-specific. A project may require these to be configured again when reproduced elsewhere.

**Goals of This Portfolio**
- Build practical, end-to-end skills with Microsoft Fabric and the broader analytics ecosystem.
- Document implementation decisions, issues encountered, and lessons learned.
- Create reusable examples that can be adapted for learning, demonstrations, and portfolio review.
- Continuously add new projects and improve existing ones.

**Author**
**Akash Navale**
Focus areas: Microsoft Fabric · Data Engineering · Power BI · Analytics
