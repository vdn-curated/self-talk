## HC:
### Part 1: Hybrid data platform: operational data stored on prem, data used for analytics will be processed on Keboola platform
	- Scope:
		+ Construct data pipeline to move data from on-prem to Cloud. Techstack: Nifi, Airflow, AWS Lambda
		+ Build monitoring system to monitor data quality in term of technical (row count, column change, oracle resource) and business metrics (depending on specific use case)
			Techstack: grafana, postgres, prometheus, 
		+ Deliver training to end ủe
		
### Part 2: Hadoop on-prem data platform: in-house solution with target to provide a self-services for business users. Techstack: Hive, Impala, HUE, NIFI, Jupyter Lab, Kafka, Sqoop, Spark, PowerBI
	- Scope:
		+ Develop data pipeline for each request datasource from users. (web services, backend logs, message queue) [Infrastructure operation (gitops, ansible) develop/monitor by central IT team in Chzech]
		+ Develop Spark application to scale the machine learning model deployment by Data Science Team.
	
### Current scope:
	+ Build data pipeline to ingest into datalake, develop ETL job in Spark for reporting
	+ Scale machine learning model build by DS team
	+ Integrate new datasource to Risk platform for better predictor engine
	
