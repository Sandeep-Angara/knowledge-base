#### Data
	- Structured
	- Semi structured
	- Unstructured

Delimited text is a good choice for structured data that needs to be accessed by a wide range of applications and services in a human-readable format.

JSON a flexible format that's good for both structured and semi-structured data.

Some file formats however, particularly for unstructured data, store the data as raw binary that must be interpreted by applications and rendered.

Transactional databases: DB's that include transactions. Eg: Banking, Retail payments etc.,
OLTP: Online Transactional Processing - Optimized for both read and write operations

Analytical Data Processing

Data warehouse: A relational database optimized for read operations

#### OLTP vs OLAP
	- Transactional vs Analytical
	- OLTP for faster transactions which includes read and write
	- OLAP is for multidimensional analysis of data which mostly includes read

#### Data services in Azure
	- Azure SQL
	- Managed services for open-source DB's: Mysql, MariaDB, PostgreSQL.
	- Azure Cosmos DB: Enterprise NoSQL 

#### Azure Storge
	- Blob containers
	- File shares
	- Tables

#### Azure Synapse Analytics
A unified analytics solution that provides services for:
	- Pipelines
	- SQL
	- Apache Spark
	- Synapse data explorer

#### Azure Data bricks
Azure integrated version of popular Databricks platform used for large-scale data analytics

#### Azure HDInsight
Bigdata service including technologies:
	- Apache Spark
	- Apache Hadoop
	- Hbase
	- Kafka

#### Data Warehouse: 
Database specially designed around reporting, and able to shed some burdens of day-to-day databases. Avoid burdens when data is ingested from different sources

#### Apache Spark
Most popular open source big data engine used for data prep, data engineering and ETL, ML

#### Descriptive Analytics: 
P: What is happening in my business?
S: Data Warehouse- Creating data warehouse from historical data in relational tables for multi-dimensional analysis. 

#### Diagnostic Analytics
P: Why is it happening?
S: Analyzing data ware house

#### Predictive Analytics
What is likely to happen in future

#### Prescriptive Analytics
Autonomous decision making based on real time analysis

#### Azure Synapse
When transporting data from different sources to a data lake and perform analytics on it, there requires many tools like SQL, Spark/Hive, integration engines etc., These barriers are removed by Azure Synapse, by providing a consolidated unified interface and providing centrally managed service for organizations or users.

#### Data Analytics Workloads

1. Azure Data Factory: Data integration service that create, schedule and orchestrate your ETL/ELT workflows
Data moves from outside of azure to inside of azure

2. Where it is stored?
Azure Blob storage: massively scalable for any time of unstructured data 
Azure Data Lake: handle even more larger amounts of data
Unprocessed data stored here

3. Azure Data bricks Apache-spark based analytics
Here you can manipulate data by linking to one of the data source like a data factory, and modify and store it in another data source like Synapse Analytics

4. Synapse Analytics
The cloud data warehouse that lets us scale, compute.
Optimized for read only queries

5. Azure Analysis Service
Data is optimized for complex queries with cubes and dimensions

	

#### Activities in Azure Data Factory: define actions to perform
	- Data movement activities
	- Data transformation activities
	- Control activities

Pipeline: grouping of activities to perform some task. Pipelines can perform tasks sequentially or parallelly 

Pipeline run - an instance of pipeline execution

Pipeline triggers: an event that causes a pipeline to run
	- Scheduled trigger
	- Tumbling window
	- Event-based


#### Data Viz:
How you view the data
3 kinds of reports:
	- Paginated Reports: Designed to be printed and shared: PowerBI Report Builder 
	- Interactive: viewed on screen. Click for more details, drill down the data: Part of PowerBI Premium
	- Dashboards: mixture of chart types on a single page. Data at a glance. Click to go to individual report

#### Power BI Content workflow
	- Connect to data source
	- Pull what you need into the in-memory data model
	- Edit, transform the data as needed
	- Build reports using Power BI Desktop
	- Share

	
#### Data File Formats
	- JSON: Object notation
	- Avro
		○ Row-based
		○ Each record with header that specifies structure
		○ Data stored in binary format
		○ Ideal for compressing data
	- Parquet 
		○ Columnar data
		○ Data is stored in row-groups
		○ Ideal for compression and encoding

#### Data Lake: 
	- Store large amounts of data
	- Data can come from different sources and formats
	- Enabling hierarchical namespace while configuring azure storage account makes it a Data Lake

#### Analytics
Descriptive, to answer the question: What's happening?
Diagnostic, to answer the question: Why's happening?
Predictive, to answer the question: What will happen?
Prescriptive, to answer the question: What actions should we take?

#### Storage Explorer
An interface to manage data lake and storage accounts on windows or mac device

#### Data Virtualization
	- Virtually integrate data from multiple sources without actually moving data to a centralized storage

SQL Dedicated pools are used if we need data warehouse features like predictable performance 
The serverless model is ideal for adhoc workloads 

#### Spark 
The primary use case for Apache Spark for Azure Synapse Analytics is to process big data workloads that cannot be handled by Azure Synapse SQL, 
