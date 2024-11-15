# GCP-TO-HIVE-TABLE-LOAD-PIPELINE-DAILY

## Introduction
Data Pipeline Description:
Designed and implemented a data pipeline to streamline data processing and loading from Google Cloud Storage (GCS) to Hive tables using Apache Airflow.

### Key Features:
Data Loading:Source data is ingested from a GCS landing bucket.
Data is loaded into a Hive external table for staging.
After process completed the source file will be moved to the archiev folder.

### Partitioning: Data is transformed and inserted into a partitioned Hive table for optimized querying and management.
Workflow Automation: Airflow DAGs orchestrate the entire process, ensuring reliability and monitoring.

### Tools and Technologies:
Google Cloud Storage (GCS): For data storage and retrieval.
Apache Hive: For external and partitioned table management.
Apache Airflow: For pipeline orchestration and scheduling.
This pipeline ensures seamless data flow, efficient partitioning, and query optimization, making it suitable for high-volume data processing scenarios.

## PIPELINE FLOW SCREENSHOT -
![PIPELINE FLOW](https://github.com/SandipJadhav7843/GCP-TO-HIVE-TABLE-LOAD-PIPELINE-DAILY/blob/main/Pipeline_Flow.png)


## PIPELINE EXECUTION VIDEO -
![PIPELINE EXECUTION VIDEO](https://github.com/SandipJadhav7843/GCP-TO-HIVE-TABLE-LOAD-PIPELINE-DAILY/blob/main/Pipeline_Execution_Video.rar)

## After loading Partition -

![Partition](https://github.com/SandipJadhav7843/GCP-TO-HIVE-TABLE-LOAD-PIPELINE-DAILY/blob/main/hive_warehouse_partition.png)


## After source data moved to the Archieval Folder -

![Source](https://github.com/SandipJadhav7843/GCP-TO-HIVE-TABLE-LOAD-PIPELINE-DAILY/blob/main/Source_file_moved_to_archieve_folder.png)
![Archieve](https://github.com/SandipJadhav7843/GCP-TO-HIVE-TABLE-LOAD-PIPELINE-DAILY/blob/main/Archive%20Folder.png)

