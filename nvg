* Is the cloud strategy in our team clear now (she remembers you said the team would make decision in Mar)? if yes, what is it? (Liam told me something about hybrid direction)
  * The cloud strategy is not yet defined for Scout24, post-poned by CIO to summer 2021, our DataUnit is independently already evaluating options, eg. Azure Services (Azure Synapse Analytics), ML workload scaling in cloud

* What is your expectation for the Data Engineer team?
  * Our current Data Engineering Tasks are currently heavily revolving around ETL for DWH and providing infrastructure / operations for ML services.
  * The Data Warehouse is heavily based on Tabular Models to expose data to customers - we want to enable more self-servicing for stakeholders
  * Current Team's knowledge is heavily based on Microsoft Ecosystem, but we are also in the process of opening our toolset to opensource solutions and integrating those technolies 
    eg. via cloud services

* What is the daily scope of work of Data Engineer team?
  * We use SRUM, work with 2 week sprints: Data Engineers work closely together with Data Product Owners (part of our Data Unit), Data Analysts & Stakeholders (eg. Marketplaces) 
  * Evaluation of technical requirements and feasibilty for data aggregation, processing and servicing (currently mostly via DWH)
  * Mostly ETL for DWH ingestion, maintaining data marts and tabular models (with our BI Architect)
  * Data extraction from 3'rd party systems and ingestion into DWH 
  * Data preparation for ML Team (eg. DWH based data & images)
  * Monitoring & Maintainance of data pipelines (DWH Infrastructure Operations by IT, some operations (eg. devops on Kubernetes) by our team)

* What is the stack used in the team?

  Currently:

  On-Prem:
  * MSSQLServer (Data Warehouse) Marketplaces: MSSqlServer, Postgres, Cassandra, Solr
  * PowerBI (on-prem)
  * SharePoint (historically)
  * Kubernetes (via Rancher, Helm)
  * Jenkins (CI/CD - planning to use Github Actions in future)
  * Monitoring: Prometheus (Grafana)
  * Logging: Fluentd, ElasticSearch / Kibana
  * Version Control: Github Enterprise
  * Jira
  * Confluence
  * Slack
  * C# / Python

  Azure:
  * Data Factory
  * Azure Data Lake Storage

  Google:
  * Google BigQuery
  
  AWS:
  * DataRobot (3'rd party service)

  Planned:
    Cloud
    * PowerBI (Azure)
    * Azure Synapse Analytics (potentially, in evaluation)
    * Spark (DataBricks) ((potentially, in evaluation))

    In general:
    * We're looking at improving and prepare for Scale on ML subjects (data lakes, data processing, data exploration)
      and may consider using tools like AirFlow / MLFlow
    * We'll need to leverage cloud computing capabilites for heavy ML model training - we'll start to investigate these options this year (eg. in context of Azure Synapse Analytics)
    * We're in the process of accessing our current data and analyzing sercurity/legal aspects of hosting data in the cloud (PII, anonymization, Governance)
    * We're not totally focused on Azure: AWS or GCP are still options if they best fit our needs 
