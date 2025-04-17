# MS_Fabric_MDD
A Metadata Driven Framework (MDD) built on top of Pyspark and Lakehouse, which could drive the data from end to end with configurations in YAML files.

The framework could 
- onboard the data files of multiple formats: csv, parquet, text, json, orc, excel, xml and dbf
- backfill the data files in the past
- incrementally transform the data from bronze tables to silver tables
- incrementally load the dta from silver tables to gold tables
- create the SCD dimension tables
- support the data tranformation with Spark SQL and PySpark(python)
- verify the data quality of the tables on brozne, silver and gold layer with a rule engine and generate data quality report
- auto-track the tables dependencies and generate data lineage report
- ingest the files and process the data accrossing different layers in micro-batch mode

Medallion Architecture
![image](https://github.com/user-attachments/assets/59efce49-118b-4f1f-b7ea-64b284535bf7)

Sample Architecture
![image](https://github.com/user-attachments/assets/6963fe35-e49d-4821-90f1-d92a172e4f67)

Metadata Driven Framework
![image](https://github.com/user-attachments/assets/b0839581-9cd8-438e-9a67-92bb2602e5bb)
![image](https://github.com/user-attachments/assets/0ffafe32-3550-483e-bb8f-25b7065b50b8)

Sample metadata YAML files
- onboarding.yml
- transform.yml
- load.yml
- workflow.yml
- task.yml
