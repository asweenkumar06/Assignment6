# Assignment6
Week 6: Azure Data Factory ETL Project
In this task, we build an ETL pipeline using Azure Data Factory (ADF) that extracts data from:

A Blob CSV file (Netflix dataset) uploaded to Azure Storage
The data is then loaded into an Azure SQL Database
We also discuss incremental load logic, and optionally how to schedule the pipeline using triggers.

Thanks to CSI (Celebal Summer Internship)
This task gave me a deep understanding of building ETL pipelines in ADF using its no-code, drag-and-drop interface.
I'm grateful for the opportunity to learn and build!

🪜 Steps Followed
Created Azure SQL Database from portal
Enabled public access and allowed Azure services
Created table manually in SQL using Query Editor or SSMS
Uploaded Netflix CSV dataset to Azure Blob Storage
Opened Azure Data Factory Studio
Created two Linked Services:
One to Blob Storage
One to Azure SQL DB
Created datasets for:
Netflix CSV (source)
SQL Table (sink)
Created Copy Activity pipeline to move data from Blob to SQL
Debugged pipeline to verify correctness
Published pipeline to finalize it
🖼️ Screenshot Gallery
Screenshot	Description
pipeline_overview.png	Overall view of ADF pipeline with Copy Activity
linked_service_blob.png	Linked Service configuration for Blob Storage
linked_service_sql.png	Linked Service configuration for Azure SQL
dataset_blob_csv.png	Dataset config for Netflix CSV file
dataset_sql_sink.png	Dataset config for SQL sink table
copy_activity.png	Copy activity showing Source and Sink
debug_success.png	Successful debug output showing data copied
adf_publish.png	Publish confirmation screenshot in ADF
🧩 ADF Pipeline Overview
ADF Pipeline Overview

🔗 Linked Services
Blob Storage

Blob Storage Linked Service

Azure SQL Database

Azure SQL Linked Service

📊 Datasets
Blob Dataset

SQL Dataset

🔁 Copy Activity
Copy Activity

🧪 Debug Result
Debug Success

🗂️ SQL Table Data Preview
SQL Table Preview

✅ Summary
Task	Status
Blob → SQL Pipeline	✅ Done
Incremental Load Logic	🔄 Optional
Trigger for Automation	🔄 Optional
This was a great exercise in cloud-based data movement using Azure Data Factory! 💙
