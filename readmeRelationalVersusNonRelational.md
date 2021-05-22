# sql-knowledge-base
A dictionary of basic techniques in SQL.

A few quick basics:

1. SQL = Structured Query Language

2. It's the standard language for Relational Database Management Systems (RDMS's).

3. Originally based on relational algebra and tuple relational calculus.

4. Relational (SQL) databases form relations between tables that store data on specific entities. In non-relational (noSQL) databases, the data on the object isn't limited to the same table. Non-relational databases use columns and rows to identify arbitrary types of data containing an arbitrary number of values, where objects are identified with keys (as in key/value pairs).

## Advantages and Disadvantages of Relational Databases

* PROS: simplicity, data accuracy, easy access to data, data integrity (all entries have their validity checked), flexibility (you can create new relations between tables without changing anything within the data structure) and high security.

* CONS: possible performance issues, set-up can take a long time, no support for complex data types.

## Advantages and Disadvantages of Non-relational Databases

* PROS: handles unstructured data, quick document update, can get all data related to one user by opening just one document with no need of shifting between multiple tables, open-source.

* CONS: dependency on a specific database management system, limited functionality, hiring difficulties.

## Examples of Relational Databases

1. MySQL - used by WordPress, Drupal, Joomla, YouTube, flickr, Twitter... most popular database in the world. 

*GOOD FUNCTIONALITIES*: performance monitoring; support of Linux, Windows, MacOS and others; password encryption, great performance of up to 50 million data rows.

*NOT SO GOOD FUNCTIONALITIES*: slow data transactions, weak debugging algorithms.

2. Microsoft SQL Server - 

*GOOD FUNCTIONALITIES*: in-memory analytics, bi-semantic model, customization capabilities, integration with Oracle Databases, error management and many others.

*NOT SO GOOD FUNCTIONALITIES*: expensive licensing plans, windows-based servers only.

3. OracleDB - hosted in the cloud. Used for transitiong to cloud computing and for running web applications on the cloud.

*GOOD FUNCTIONALITIES*: four levels of data transaction protection, grouped transactions, real application cluster that allows the connection of many servers to the database. 

*NOT SO GOOD FUNCTIONALITIES*: high price, difficult to find developers, not so easy to learn and use.

3. IBM DB2 - one of the oldest database solutions.

*GOOD FUNCTIONALITIES*: powerful SQL modification, efficient memory handling, support of IBM infrastructure.

*NOT SO GOOD FUNCTIONALITIES*: requires many add-ons to unlock its full functionality, limited free support from IBM.

## Examples of Non-Relational Databases

1. MongoDB - 

*GOOD FUNCTIONALITIES*: Support of various data types, ability to distribute data automatically between different servers, fast performance.

*NOT SO GOOD FUNCTIONALITIES*: Ever increasing memory requirement, no control of duplication, lack of documentation.

2. DocumentDB - developed and managed by Amazon. 

*GOOD FUNCTIONALITIES*: Integration with Mongo DB, easy database migration, monitoring capabilities, automatic updates and automatic storage increases.

*NOT SO GOOD FUNCTIONALITIES*: Mostly the same as it happens with MongoDB: no control of duplication, scarce educational resources and poor data organization - as your project scales, data will get messy.

3. Cassandra - created by Facebook.

*GOOD FUNCTIONALITIES*: Scalability; support of unstructured, structured and semi-structured data; support for multiple data centers.

*NOT SO GOOD FUNCTIONALITIES*: No ACID support, no AGGREGATES support, latency problems.

## Four Questions to Aid Database Selection

1. What type of data will you be analyzing ?

*Huge amount of well-tructured, factual and numeric data?* Relational database.

*Messy, poorly structured data?* Non-relational database.

2. How much data will you be analyzing ?

*Huge, "over the moon" amounts of data ?* Non-relational database.

3. Truly ready to invest time and budget in the setup of a database ?

Relational database: harder to set-up, easier to support.
Non-relational database: easier to set-up, harder to support.

4. Do you need real-time data ?

Non-relational database: more flexible. Saves a lot of time at the data input stage.

