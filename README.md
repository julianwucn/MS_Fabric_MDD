# MS_Fabric_MDD
A declarative metadata-driven ETL framework developed using PySpark and Lakehouse and/or data warehouse architecture on Microsoft Fabric, enabling end-to-end data process automation based on configurations defined in YAML files.

Main Features
- Declarative ETL, data engineers define the desired end state of the transformed data, and the ETL tool automatically generates the code to transform the data into that end state
- Align with medallion architecture with customizable bronze, silver and gold layers
- Support the data ingestion of different sources and flat files of csv, text, json, orc, parquet, table, jdbc, excel, xml and dbf
- Support multiple data refresh strategies: full, incremental and backfill
- Support multiple incremental data refresh options: CDF and timestamp, auto fallback to backfill or full data refresh options if in recent not-synced CDF data is purged
- Support multiple data write options: append, merge, overwrite
- Support multiple transformation code: sql, python and notebook
- Support SCD type 2 dimensions
- Built-in micro-batches support for both data ingestion and data transformation
- Built-in rule engine to support data validation and data correctness
- Built-in data lineage and table dependency tracking

Medallion Architecture
![image](https://github.com/user-attachments/assets/59efce49-118b-4f1f-b7ea-64b284535bf7)

Sample Architecture
![image](https://github.com/user-attachments/assets/6963fe35-e49d-4821-90f1-d92a172e4f67)

Metadata Driven Framework
![image](https://github.com/user-attachments/assets/b0839581-9cd8-438e-9a67-92bb2602e5bb)
![image](https://github.com/user-attachments/assets/0ffafe32-3550-483e-bb8f-25b7065b50b8)


