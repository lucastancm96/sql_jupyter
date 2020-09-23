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
1. Run SQL query directly in the SQL software.
![Tables in SQLite](/img/sqlite_01.png)<br/>
Tables in the `trackdb.sqlite`.<br/>

![Execute SQL query in SQLite](/img/sqlite_02.png)
Performing SQL directly in the SQLite database.<br/>

2. Run SQL query in `command` or `terminal`. Normally this is performed for database stored in MySQL server. To do this, one has to connect to the server before through the command or terminal before executing SQL query. Two examples of running SQL query in command and terminal can be found as follows:
* https://www.tutorialspoint.com/run-sql-file-in-mysql-database-from-terminal (command)
* https://www.quackit.com/sql_server/mac/install_sql-cli_on_a_mac.cfm (terminal)

3. Run SQL query using Python script (for SQLite). To do this, we need to use three existing function in Python:
* conn = sqlite3.connect(`path`)
* cur = conn.cursor() 
* cur.executescript(`SQL queries`)<br/>
The Python script can then be executed in IDE like `PyCharm`, `Spyder`, or `VSCode`. Example of Python script can be found in *pending link*

4. Run SQL query using Jupyter. This will be demonstrated in this repo.

### References
[1] https://tec4tric.com/ds/is-sql-needed-for-data-scientist
[2] https://www.guru99.com/what-is-dbms.html#10

