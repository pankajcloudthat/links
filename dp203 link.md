-------------------------------------------------------
=======================================================
Design and implement data storage (40–45%) 
=======================================================
-------------------------------------------------------

Design a data storage structure 
----------------------------------------------------------

• Overview of Azure Data Lake Storage Gen2 
https://docs.microsoft.com/en-us/learn/modules/introduction-to-azure-data-lake-storage/2-azure-data-lake-gen2
• Access tiers for Azure Blob Storage 
https://docs.microsoft.com/en-us/azure/storage/blobs/access-tiers-overview
• Right storage account for file requirements 
https://docs.microsoft.com/en-us/learn/modules/query-data-lake-using-azure-synapse-serverless-sql-pools/6-storage-considerations
• Query data using Azure Synapse Analytics 
https://docs.microsoft.com/en-us/learn/modules/query-data-lake-using-azure-synapse-serverless-sql-pools/3-query-parquet-file
• Dynamic file pruning (DFP) 
https://docs.microsoft.com/en-us/azure/databricks/delta/optimizations/dynamic-file-pruning


Design a partition strategy 
----------------------------------------------------------

• Create file partitions using Azure Synapse Studio 
https://docs.microsoft.com/en-us/learn/modules/optimize-data-warehouse-query-performance-azure-synapse-analytics/4-understand-table-distribution-design
• Partitioning tables 
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-tables-partition

• Distribution in tabular models 
https://docs.microsoft.com/en-us/learn/modules/optimize-data-warehouse-query-performance-azure-synapse-analytics/4-understand-table-distribution-design

• Optimizing data warehouse query performance in Azure Synapse Analytics 
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql/best-practices-dedicated-sql-pool

• Partitioning tables in Dedicated SQL Pool 
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-tables-partition


Design the serving layer 
----------------------------------------------------------

• Star schema 
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-tables-overview

• Multidimensional schemas and data 
https://docs.microsoft.com/en-us/sql/ado/guide/multidimensional/overview-of-multidimensional-schemas-and-data?view=sql-server-ver15&viewFallbackFrom=sql-server-ver15

• Temporal tables in Azure SQL Database 
https://docs.microsoft.com/en-us/sql/relational-databases/tables/manage-retention-of-historical-data-in-system-versioned-temporal-tables?view=sql-server-ver15&viewFallbackFrom=sql-server-ver15

• Getting started with temporal tables in Azure SQL Database and Azure SQL Managed Instance 
https://docs.microsoft.com/en-us/azure/azure-sql/temporal-tables


• Self-hosted integration runtime 
https://docs.microsoft.com/en-us/azure/data-factory/create-self-hosted-integration-runtime&tabs=data-factory

• Manage the self-hosted integration runtime 
https://docs.microsoft.com/en-us/learn/modules/petabyte-scale-ingestion-azure-data-factory/5-manage-self-hosted-integration-runtime

• Analytical data store in Azure 
https://docs.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/analytical-data-stores

• Usage of Apache Spark pools 
https://docs.microsoft.com/en-us/learn/modules/understand-big-data-engineering-with-apache-spark-azure-synapse-analytics/4-when-do-you-use-apache-spark-pools

• Shared metadata table in Azure Synapse Analytics 
https://docs.microsoft.com/en-us/azure/synapse-analytics/metadata/table




Implement physical data storage structures 
----------------------------------------------------------

• Data compression 
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-memory-optimizations-for-columnstore-compression

• Partitioning tables in Azure Synapse 
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-tables-partition

• Table distribution in Azure Synapse 
https://docs.microsoft.com/en-us/learn/modules/optimize-data-warehouse-query-performance-azure-synapse-analytics/6-exercise-use-table-distribution-indexes-to-improve-performance

• Change how a storage account is replicated 
https://docs.microsoft.com/en-us/azure/storage/common/redundancy-migration?tabs=portal

• Implement lifecycle management
https://docs.microsoft.com/en-us/azure/storage/blobs/lifecycle-management-overview?tabs=azure-portal


Implement logical data structures 
----------------------------------------------------------

• Design Slowly Changing Dimensions 
https://docs.microsoft.com/en-us/sql/integration-services/data-flow/transformations/slowly-changing-dimension-transformation?view=sql-server-ver15&viewFallbackFrom=sql-server-ver15

• Slowly Changing Dimension transformation 
https://docs.microsoft.com/en-us/learn/modules/populate-slowly-changing-dimensions-azure-synapse-analytics-pipelines/

• Create external tables in Azure Synapse serverless SQL pools 
https://docs.microsoft.com/en-us/learn/modules/create-metadata-objects-azure-synapse-serverless-sql-pools/5-create-external-tables

• Create views in Azure Synapse server SQL pools 
https://docs.microsoft.com/en-us/learn/modules/create-metadata-objects-azure-synapse-serverless-sql-pools/6-create-views


Implement the serving layer 
----------------------------------------------------------

• Implement a star schema in Azure SQL and Azure Synapse 
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/load-data-wideworldimportersdw?toc=/azure/synapse-analytics/toc.json&bc=/azure/synapse-analytics/breadcrumb/toc.json#load-the-data-into-sql-pool

• Load Parquet file data in an Azure Spark Notebook in Azure Synapse 
https://docs.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-development-using-notebooks?tabs=classical

• Create a serverless Apache Spark pool in Azure Synapse Analytics using web tools 
https://docs.microsoft.com/en-us/azure/synapse-analytics/quickstart-apache-spark-notebook

• Flatten nested structures and explode arrays with Apache Spark in Azure Synapse 
https://docs.microsoft.com/en-us/learn/modules/transform-data-with-dataframes-apache-spark-pools-azure-synapse-analytics/7-exercise-flatten-nested-structures-explode-arrays

• Preserve metadata and ACLs using copy activity in Azure Data Factory 
https://docs.microsoft.com/en-us/azure/data-factory/copy-activity-preserve-metadata


Design and develop data processing (25–30%) 
-----------------------------------------------------------

Ingest and transform data 
• Ingestion technologies 
https://docs.microsoft.com/en-us/learn/modules/explore-azure-synapse-analytics/

• Extract, transform, and load (ETL) data by using Azure Databricks 
https://docs.microsoft.com/en-us/azure/databricks/scenarios/databricks-extract-load-sql-data-warehouse

• Azure Stream Analytics workflow 
https://docs.microsoft.com/en-us/learn/modules/transform-data-with-azure-stream-analytics/2-stream-analytics-workflow

• Methods to handle missing data 
https://docs.microsoft.com/en-us/azure/databricks/spark/latest/spark-sql/handling-bad-records
• Explore and fix data using Azure Synapse Analytics 
https://docs.microsoft.com/en-us/learn/modules/design-modern-data-warehouse-using-azure-synapse-analytics/7-prepare-transform-data
• Query and transform JSON data with Apache Spark for Azure Synapse 
https://docs.microsoft.com/en-us/azure/synapse-analytics/how-to-analyze-complex-schema
• Column-family databases 
https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/data-store-overview
• Transform data using Scala 
https://docs.microsoft.com/en-us/azure/databricks/spark/latest/dataframes-datasets/introduction-to-dataframes-scala
• Prepare and transform data
https://docs.microsoft.com/en-us/learn/modules/design-modern-data-warehouse-using-azure-synapse-analytics/7-prepare-transform-data



Design and develop a batch processing solution 
----------------------------------------------------------

• Overview of modern data warehouse architecture 
https://docs.microsoft.com/en-us/learn/modules/design-modern-data-warehouse-using-azure-synapse-analytics/3-define-architecture

• Choosing a batch processing technology in Azure 
https://docs.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/batch-processing
• Manage source data files 
https://docs.microsoft.com/en-us/learn/modules/use-data-loading-best-practices-azure-synapse-analytics/4-manage-source-data-files
• Create pipeline with copy activity in Azure Data Factory 
https://docs.microsoft.com/en-us/azure/data-factory/copy-activity-overview
• Azure Synapse Studio notebooks 
https://docs.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-development-using-notebooks?tabs=classical#run-notebooks
• Dedupe rows and find nulls 
https://docs.microsoft.com/en-us/azure/data-factory/how-to-data-flow-dedupe-nulls-snippets
• MERGE (Transact-SQL) 
https://docs.microsoft.com/en-us/sql/t-sql/statements/merge-transact-sql?view=sql-server-ver15&viewFallbackFrom=sql-server-ver15
• Continuous integration and delivery for Azure Synapse workspace 
https://docs.microsoft.com/en-us/azure/synapse-analytics/cicd/continuous-integration-delivery
• Handle SQL truncation error rows 
https://docs.microsoft.com/en-us/azure/data-factory/how-to-data-flow-error-rows
• Backup and restore in Azure Synapse Dedicated SQL Pool 
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/backup-and-restore
• Best practices for loading data in Azure Synapse Analytics 
https://docs.microsoft.com/en-us/learn/modules/use-data-loading-best-practices-azure-synapse-analytics/8-implement-workload-management
• Debugging Apache Spark jobs 
https://docs.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-history-server


Design and develop a stream processingsolution
----------------------------------------------------------

•Modern data warehouse architecture
https://docs.microsoft.com/en-us/azure/architecture/solution-ideas/articles/enterprise-data-warehouse
•Stream processing: Azure Databricksand Azure Event Hubs
https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/data/stream-processing-databricks
•Apache Spark structured streaming
https://docs.microsoft.com/en-us/azure/databricks/data/data-sources/azure/synapse-analytics
•Monitor for performance efficiency
https://docs.microsoft.com/en-us/azure/architecture/framework/scalability/monitor
•How to work with windowingfunctions
https://docs.microsoft.com/en-us/learn/modules/understand-data-warehouse-developer-features-of-azure-synapse-analytics/5-exercise-work-windowing-functions
•Schema drift
https://docs.microsoft.com/en-us/azure/data-factory/concepts-data-flow-schema-drift
•Time handling considerations
https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-time-handling
•Checkpoints in Azure Stream Analyticsjobs
https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-concepts-checkpoint-replay
•Late arriving data
https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-time-handling#late-arriving-events
•Watermarks inAzure Stream Analyticsjobs
https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-time-handling
•Tune a Stream Analytics query toincrease throughput for StreamAnalytics jobs
https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-scale-jobs
•Repartitioning and parallelization
https://docs.microsoft.com/en-us/azure/stream-analytics/repartition
•Output error policy in Azure StreamAnalytics
https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-output-error-policy
•Stream Analytics upsert
https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-documentdb-output#:%7E:text=Stream%20Analytics%20integration%20with%20Azure,with%20a%20document%20ID%20conflict
•Time progression
https://docs.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-development-using-notebooks?tabs=classical
•Stream processing with Azure StreamAnalytics
https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/data/stream-processing-stream-analytics


Manage batches and pipelines
----------------------------------------------------------

• Data loading best practices
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql/data-loading-best-practices

• Design and create tests for analytics in Azure Synapse
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-integrate-azure-stream-analytics

• Trigger batches using Azure Synapse
https://docs.microsoft.com/en-us/azure/synapse-analytics/get-started

• Monitor your Azure Synapse workspace
https://docs.microsoft.com/en-us/azure/synapse-analytics/get-started-monitor




Design and implement data security (10–15%)

==============================================================

Design security for data policies and standards
----------------------------------------------------------

• Encryption at rest and in transit
https://docs.microsoft.com/en-us/learn/modules/secure-data-warehouse-azure-synapse-analytics/8-implement-encryption
• Data ingestion security considerations
https://docs.microsoft.com/en-us/learn/modules/petabyte-scale-ingestion-azure-data-factory/7-understand-data-ingestion-security-considerations
• Configure authentication using Azure Key Vault
https://docs.microsoft.com/en-us/learn/modules/secure-data-warehouse-azure-synapse-analytics/4-configure-authentication
• Configure data lake security with access control lists (ACLs)
https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-access-control
• Securing access to data
https://docs.microsoft.com/en-us/azure/synapse-analytics/security/synapse-workspace-access-control-overview
• Column-level security in SQL Data Warehouse
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/column-level-security


Implement data security
-----------------------------------------------------

• Manage authorization: Column and row level
https://docs.microsoft.com/en-us/learn/modules/secure-data-warehouse-azure-synapse-analytics/5-manage-authorization-through-column-row-level-security
• Manage user permissions in Azure Synapse
https://docs.microsoft.com/en-us/learn/modules/secure-data-manage-users-azure-synapse-serverless-sql-pools/4-manage-user-permissions
• Retention policy on storage account
https://docs.microsoft.com/en-us/azure/storage/blobs/lifecycle-management-overview?tabs=azure-portal
• Auditing for Azure SQL Database and Azure Synapse Analytics
https://docs.microsoft.com/en-us/azure/azure-sql/database/auditing-overview#setup-auditing
• Network security options for Azure Synapse Analytics
https://docs.microsoft.com/en-us/learn/modules/secure-data-warehouse-azure-synapse-analytics/2-understand-network-security-options
• Generate resource token in Azure Databricks
https://docs.microsoft.com/en-us/azure/databricks/dev-tools/api/latest/authentication
• Dynamic data masking
https://docs.microsoft.com/en-us/learn/modules/secure-data-warehouse-azure-synapse-analytics/7-manage-sensitive-data
• Data masking in Azure Synapse
https://docs.microsoft.com/en-us/learn/modules/secure-data-warehouse-azure-synapse-analytics/7-manage-sensitive-data
• Security controls: Data protection
https://docs.microsoft.com/en-us/security/benchmark/azure/security-control-data-protection
• Secure a Dedicated SQL Pool
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-overview-manage-security


Monitor and optimize data storage and data processing (10–15%)
================================================================================

Monitor data storage and data processing
----------------------------------------------------------

• Monitor and alert Data Factory by using Azure Monitor
https://docs.microsoft.com/en-us/azure/data-factory/monitor-using-azure-monitor
• Improving performance with workload management and materialized views
https://docs.microsoft.com/en-us/learn/modules/use-data-loading-best-practices-azure-synapse-analytics/9-exercise-implement-workload-management
• Creating statistics to improve performance
https://docs.microsoft.com/en-us/learn/modules/optimize-data-warehouse-query-performance-azure-synapse-analytics/7-create-statistics-to-improve
• Cluster performance in Dedicated SQL Pools
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-manage-monitor
• Collect custom logs with Log Analytics agent
https://docs.microsoft.com/en-us/azure/azure-monitor/agents/data-sources-custom-logs
• Monitor workspace pipeline runs using Azure Synapse Studio
https://docs.microsoft.com/en-us/azure/synapse-analytics/monitoring/how-to-monitor-pipeline-runs
• Deploying Apache Airflow in Azure to build and run data pipelines
https://azure.microsoft.com/en-us/blog/deploying-apache-airflow-in-azure-to-build-and-run-data-pipelines/

Optimize and troubleshoot data storage and data processing
----------------------------------------------------------

• Auto Optimize in Azure Databricks
https://docs.microsoft.com/en-us/azure/databricks/delta/optimizations/auto-optimize
• Modify user-defined functions
https://docs.microsoft.com/en-us/sql/relational-databases/server-management-objects-smo/tasks/creating-altering-and-removing-user-defined-functions?view=sql-server-ver15&viewFallbackFrom=sql-server-ver15
• Choosing a distributed column
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-tables-distribute
• Handle data spillage
https://docs.microsoft.com/en-us/microsoft-365/compliance/data-spillage-scenariosearch-and-purge?view=o365-worldwide#:%7E:text=Data%20spillage%20is%20when%20a,spilled%20data%20from%20the%20system
• Troubleshoot performance bottlenecks in Azure Databricks
https://docs.microsoft.com/en-us/azure/architecture/databricks-monitoring/performance-troubleshooting
• Azure Synapse Dedicated SQL Pool shuffle speed
https://azure.microsoft.com/en-us/blog/lightning-fast-query-performance-with-azure-sql-data-warehouse/
• Create an Azure Synapse workspace using an Azure Resource Manager template (ARM template)
https://docs.microsoft.com/en-us/azure/synapse-analytics/quickstart-deployment-template-workspaces
• Indexing Dedicated SQL Pool tables in Azure Synapse Analytics
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-tables-index
• Performance tuning with result set caching
https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/performance-tuning-result-set-caching
• Optimize Apache Spark jobs in Azure Synapse Analytics
https://docs.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-performance
• Troubleshoot library installation errors
https://docs.microsoft.com/en-us/azure/synapse-analytics/spark/apache-spark-troubleshoot-library-errors
• Debug pipelines using Azure Synapse Pipelines
https://docs.microsoft.com/en-us/learn/modules/orchestrate-data-movement-transformation-azure-data-factory/4-debug-pipelines

