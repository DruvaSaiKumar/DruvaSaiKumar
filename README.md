# Druva Sai Kumar Bobbilla

Senior Data Engineer in Dallas, TX. I've spent 8+ years building and migrating ETL/ELT pipelines and data platforms on AWS, GCP and Hadoop, and most of my recent work is moving legacy Teradata, SAS and Informatica workloads to BigQuery. I care most about being able to show that a pipeline's output is correct.

[LinkedIn](https://www.linkedin.com/in/druva-bobbilla-069412191/)

## Stack

Python, SQL, PySpark, Shell, Java. Airflow, dbt, Dagster. BigQuery, Snowflake, Redshift, Databricks, Hive. AWS (S3, Glue, Athena, Lambda, Kinesis Firehose, SQS, EMR), GCP (BigQuery, Dataflow). Terraform, Git, GitHub Actions.

## Projects

These are personal projects on synthetic data. None of them contain code or data from my employers or clients.

- [warehouse-migration-reconciliation](https://github.com/DruvaSaiKumar/warehouse-migration-reconciliation): compares a legacy table with its migrated copy (row counts, duplicate keys, column profiles, row-level diffs) and writes an audit log. Python, SQL, DuckDB, with a BigQuery adapter.
- [aws-serverless-data-lake](https://github.com/DruvaSaiKumar/aws-serverless-data-lake): Firehose to S3 to Lambda to partitioned Parquet, queried in Athena, all in Terraform. Bad records go to quarantine.
- [lakehouse-kimball-pipeline](https://github.com/DruvaSaiKumar/lakehouse-kimball-pipeline): a PySpark silver layer, a dbt star schema with a Type 2 dimension, and an Airflow DAG. CI checks the Spark output against a separate DuckDB implementation.
- [dq-lineage-toolkit](https://github.com/DruvaSaiKumar/dq-lineage-toolkit): YAML data-quality checks, column-level lineage from SQL, impact analysis and a check-coverage report.
- [kafka-clickstream-pipeline](https://github.com/DruvaSaiKumar/kafka-clickstream-pipeline): a producer and consumer on confluent-kafka that validate, deduplicate and sessionize clickstream events in real time, with a dead-letter topic and a Parquet sink. Runs against a real Kafka broker in CI, not mocked.

Each README says what has and hasn't been run against real cloud services.
