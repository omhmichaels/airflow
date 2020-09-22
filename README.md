# Airflow

## What is Airflow
* Programmatically author schedule and monitor workflows or datapipelines

**What is a Workflow**
* Sequence of Tasks
* Triggered by event
* Handle big data processing

**Workflow Example***
* Download Data
* Process Data
* Monitor for completion/errors
* Generate Report
* Send out Report

**Traditional ETL**
* Database
* CRON Scripts: Pull Data Dsend to HFS
* HDFS: Processing
    - *Problems*: 
        * Failures: 
            - Retry
            - How often
            - how many times
        * Monitoring: Success or Failed, How long
        * Dependencies:
            - Data Dependencies
            - Execution Dependencies
        * Scalability
            - No Centralized Scheduler
        * Deployment
            - Deploy new changes constantly
        * Process Historic Data:
        
