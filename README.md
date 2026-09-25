# Druva Sai Kumar Bobbilla

Senior Data Engineer with 8+ years building and modernizing enterprise ETL/ELT pipelines and data platforms across AWS, GCP, Hadoop and on-premises environments. I care about pipelines that can prove they are correct: reconciliation, data quality, audit trails and lineage.

[LinkedIn](https://www.linkedin.com/in/druva-bobbilla-069412191/)

## Stack

**Languages:** Python, SQL, PySpark, Spark SQL, Shell, Java
**Orchestration and transformation:** Airflow, dbt, Dagster, Oozie
**Warehouses and lakehouse:** BigQuery, Snowflake, Amazon Redshift, Databricks, Hive
**AWS:** S3, Glue, Athena, Lambda, Kinesis Firehose, SQS, EMR
**GCP:** BigQuery, Dataflow
**Infrastructure and CI/CD:** Terraform, Git, GitHub Actions

## Portfolio projects

All four use synthetic data, and none contain employer or client code or data. Each has CI and tests that assert exact, injected defect counts, and each README states what was and was not run against real cloud services.

| Project | What it shows |
|---|---|
| [warehouse-migration-reconciliation](https://github.com/DruvaSaiKumar/warehouse-migration-reconciliation) | Validating a legacy-to-cloud migration: row counts, duplicate keys, column profiles with tolerances, row-level diffs, audit log. Python, SQL, DuckDB, BigQuery adapter |
| [aws-serverless-data-lake](https://github.com/DruvaSaiKumar/aws-serverless-data-lake) | Firehose to S3 to Lambda to partitioned Parquet to Glue/Athena in Terraform. Quarantine of bad records, idempotent processing, partition projection |
| [lakehouse-kimball-pipeline](https://github.com/DruvaSaiKumar/lakehouse-kimball-pipeline) | PySpark silver layer, dbt Kimball star schema with a Type 2 dimension, Airflow DAG. The Spark output is checked row for row against an independent DuckDB implementation in CI |
| [dq-lineage-toolkit](https://github.com/DruvaSaiKumar/dq-lineage-toolkit) | Declarative data-quality checks, column-level SQL lineage, impact analysis, PII tag propagation, check-coverage report |
