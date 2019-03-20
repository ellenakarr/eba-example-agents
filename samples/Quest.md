This agent allows the user to query structured data from a relational database using natural language by converting natural language questions to SQL queries (or other structured languages). Aside of relational databases, Quest supports multiple data sources, e.g. HIVE, Salesforce.com and many others. 

A semantic model of the database schema should be created during the training time. The model specifies the tables, the columns, and their relations and is used by QUEST to process the natural language questions and produce SQL queries. 

The Warehouse schema model that is shown here represents a Sales/Warehouse database with 8 tables. This schema is used with a sample Quest agent. To try this example, please load the yaml configuration [yaml configuration](./Quest.yaml)into your own sandbox environment. The sample questions bellow demonstrate what can be asked of this schema.

 ![Warehouse schema](./images/warehouseSchema.png)


Sample Questions:
