# Book-servlet-Example-in-H2

H2 Server Properties - INFORMATION

#H2 Server Properties
#Fri Jun 22 19:02:35 IST 2018


0=Generic JNDI Data Source|javax.naming.InitialContext|java\:comp/env/jdbc/Test|sa

1=Generic Teradata|com.teradata.jdbc.TeraDriver|jdbc\:teradata\://whomooz/|

10=Generic DB2|com.ibm.db2.jcc.DB2Driver|jdbc\:db2\://localhost/test|

11=Generic Oracle|oracle.jdbc.driver.OracleDriver|jdbc\:oracle\:thin\:@localhost\:1521\:XE|sa

12=Generic MS SQL Server 

2000|com.microsoft.jdbc.sqlserver.SQLServerDriver|jdbc\:microsoft\:sqlserver\://localhost\:1433;DatabaseName\=sqlexpress|sa

13=Generic MS SQL Server 2005|com.microsoft.sqlserver.jdbc.SQLServerDriver|jdbc\:sqlserver\://localhost;DatabaseName\=test|sa

14=Generic PostgreSQL|org.postgresql.Driver|jdbc\:postgresql\:test|

15=Generic MySQL|com.mysql.jdbc.Driver|jdbc\:mysql\://localhost\:3306/test|

16=Generic HSQLDB|org.hsqldb.jdbcDriver|jdbc\:hsqldb\:test;hsqldb.default_table_type\=cached|sa

17=Generic Derby (Server)|org.apache.derby.jdbc.ClientDriver|jdbc\:derby\://localhost\:1527/test;create\=true|sa

18=Generic Derby (Embedded)|org.apache.derby.jdbc.EmbeddedDriver|jdbc\:derby\:test;create\=true|sa

19=Generic H2 (Server)|org.h2.Driver|jdbc\:h2\:tcp\://localhost/~/test|sa

2=Generic Snowflake|com.snowflake.client.jdbc.SnowflakeDriver|jdbc\:snowflake\://accountName.snowflakecomputing.com|

20=Generic H2 (Embedded)|org.h2.Driver|jdbc\:h2\:~/test|sa        

3=Generic Redshift|com.amazon.redshift.jdbc42.Driver|jdbc\:redshift\://endpoint\:5439/database|

4=Generic Impala|org.cloudera.impala.jdbc41.Driver|jdbc\:impala\://clustername\:21050/default|

5=Generic Hive 2|org.apache.hive.jdbc.HiveDriver|jdbc\:hive2\://clustername\:10000/default|

6=Generic Hive|org.apache.hadoop.hive.jdbc.HiveDriver|jdbc\:hive\://clustername\:10000/default|

7=Generic Azure SQL|com.microsoft.sqlserver.jdbc.SQLServerDriver|jdbc\:sqlserver\://name.database.windows.net\:1433|

8=Generic Firebird Server|org.firebirdsql.jdbc.FBDriver|jdbc\:firebirdsql\:localhost\:c\:/temp/firebird/test|sysdba

9=Generic SQLite|org.sqlite.JDBC|jdbc\:sqlite\:test|sa

webAllowOthers=false

webPort=8082

webSSL=false



With the above properties, h2 server runs... you will find a dropdown in h2 database, in that all the above are there actually..

20=Generic H2 (Embedded)|org.h2.Driver|jdbc\:h2\:~/test|sa   
----------------------------------------------------------------------------------------------------------------------------------------

To Run: 

1.Check users have test.mv and test.printtrace files... if not, then  Add test.mv and test.printtrace files...  (if is this same github-->respository)

 eg :- C://users//username(kaviyasri.b)//test.mv and test.printtrace
 

2. C:\Users\dhineshraja.m\.m2\repository\com\h2database\h2\1.4.197\h2-1.4.197(executable jar file) --->double click on it, it opens a file give the username and password.... open the db and then close the tab.... then in  system tray(right corner of task bar) 
there will open a h2 box like something.. if you right click it, you will h2 console,status,exit.Give exit and close it.

H2 CONSOLE : opens default(the dialogue box of h2 ,un and pw)
STATUS : shows on which url and port h2 console is going to run.
EXIT : To exit


Now,finally run the servlet program as usual, http://localhost:9090/list

--------------------------------------------------------------------------------------------------------------------------------------

    ==>22/6/18



