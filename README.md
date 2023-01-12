# Forex Data Pipeline (Airflow)
A data pipeline to extract forex data from github and stored in HDFS and Hive
## Data pipeline
Check availability of forex rates >> Check availability of the file having currencies to watch >> Download forex rates with Python >> Save the forex rates in HDFS >> Create a Hive table to store forex rates from the HDFS >> Process forex rates with Spark(Pyspark) >> Send an Email Notification

## Tools and Technologies
- Python 3
- Pyspark
- Os
- Airflow
- Datetime
- Csv
- Requests
- Json
- Hive
- Hdfs
