---

title: "Big Data Pipeline in Predictive Modeling"

excerpt: "Use of Big Data technologies in predictive modeling.<br/><img src='/images/500x300.png'>"

collection: portfolio

---



# \[Big Data Pipeline in Predictive Modeling](https://github.com/Riion8/Data-Science-Portfolio/tree/main/Big%20Data%20Pipeline)

### Requirements

To use the scripts in this repository, the following software must be
installed and running.

* Hadoop
* Hive
* HBase
* Nifi
* Spark

### Contents

Big Data Pipeline in Predictive Modeling.docx -- Overall process
description and results.

Diamonds.csv -- Data set used in this model.

Diamonds Ingestion Nifi Flow.json -- Nifi process flow to load data into
the Hadoop cluster.

Hive-Hbase-Spark CLI Commands.txt -- Listing of all commands used as
part of the process

Spark.py -- SparkPy predictive model.

### Summary

At a high level this process takes the Diamonds file and loads it to
Hadoop using Nifi. The data in Hadoop is then loaded into a Hive table
for future use. SparkPy uses this table to run a simple predictive model
and outputs the results to an HBase table for storage.

