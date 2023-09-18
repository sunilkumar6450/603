###SUMMARY OF RECENT ARTICLES ON DATABASE MANAGEMENT

###INTRODUCTION

The realm of database management systems (DBMS) is constantly evolving, with new technologies and approaches emerging to address the growing demands of data storage and processing. This summary provides insights into two articles that explore different aspects of modern database management.

Article 1: "A Comparison of NoSQL Database Management Systems and Models"

This article offers a comprehensive comparison of NoSQL database management systems (DBMS) and their associated data models. It dives into the key differences between popular NoSQL databases such as document stores, key-value stores, column-family stores, and graph databases. The article evaluates the strengths and weaknesses of each NoSQL category, helping readers make informed decisions when choosing a DBMS for their specific use cases.

1.Key-value Database: Key-value databases use compact, efficient index structures to quickly and reliably locate a value by its key.
Example: Amazon DynamoDB allocates additional partitions to a table if an existing partition fills to capacity and more storage space is required.

2.Columnar databases :Columnar databases are a type of database used for processing big data analytics and data warehousing.
Example: Amazon red shift,Monet DB, Apache Cassandra, SAP Hana

3.Document-oriented Databases: A document-oriented database is a type of NoSQL database that stores data in the form of documents. These documents can be in a variety of formats, such as JSON, BSON, or XML.
Examples:Apache Solr and TerminusDB

4.Graph Data Base: Graph database (GDB) is a database that uses graph structures to store data. Instead of tables or documents, GDBs use nodes, edges, and properties to represent and store data.
Examples: Neo4j,OrientDB,Arango DB.

Reference:
Author(s): Serdar Yegulalp and Rodrigo Rodriguer
Publication Date: JUN 24, 2023 3:00 AM PDT
Link https://www.infoworld.com/article/3240644/what-is-nosql-databases-for-a-cloud-scale-future.html

Article 2: "Data Lakehouse: Bridging the Gap Between Data Warehouses and Data Lakes"

A data lakehouse is a new, open data management architecture that combines the flexibility, cost-efficiency, and scale of data lakes with the data management and ACID transactions of data warehouses, enabling business intelligence (BI) and machine learning (ML) on all data.
Databricks Lakehouse Platform is offered on the three major clouds: Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP). It is also available on Alibaba.

Reference:
Author: Martin Heller 
Publication Date: APR 27, 2023 3:00 AM PDT
Link https://www.infoworld.com/article/3656799/review-databricks-lakehouse-platform.html
