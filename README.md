# Executing SQL in Jupyter
### Introduction
A database is an organized collection of structured data. Databased Management System (DBMS) is a software for storing and retrieving data in a simple organized way. There are four types of DBMS: <br/>
* Hierarchical DBMS (HDBMS)
* Network DBMS (NDBMS)
* Relational DBMS (RDBMS)
* Object-oriented DBMS (OODBMS) <br/>

Of all the above, RDBMS is the most frequently used DBMS. A Structured Query Language (SQL) is a domain-specific language used to manage data stored in a RDBMS. The key functions of SQL include insert, delete, update, modify data, and etc. Myriad of SQL servers (or RDBMS softwares) are available: <br/>

* Microsoft SQL Server
* MySQL
* IBM DB2 Oracle
* Apache Open Office Base
* Sybase ASE
* SQLite
* PostgreSQL <br/>
However, the choice of SQL server largely depends on the company a data scientist is working for. In addition, the syntax may change a little bit based on the DBMS one is using.

### How SQL query is executed?
There are many ways to execute SQL query and the following illustrates the most common approaches:
1. Run SQL query directly in the SQL server.
![Tables in SQLite](/img/sqlite_01.png)<br/>
Tables in the `trackdb.sqlite`.<br/>
![Execute SQL query in SQLite](/img/sqlite_02.png)
Performing SQL directly in the SQLite database.<br/>

### References
[1] https://tec4tric.com/ds/is-sql-needed-for-data-scientist
[2] https://www.guru99.com/what-is-dbms.html#10

