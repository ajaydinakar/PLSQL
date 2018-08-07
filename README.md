### PL/SQL
__The PL/SQL programming language was developed by Oracle Corporation in the late 1980s as procedural extension language for SQL and the Oracle relational database. Following are certain notable facts about PL/SQL:__ 

  1.  PL/SQL is a completely portable, high-performance transaction-processing language. 
  2.  PL/SQL provides a built-in, interpreted and OS independent programming environment. 
  3.  PL/SQL can also directly be called from the command-line SQL*Plus interface. 
  4.  Direct call can also be made from external programming language calls to database. 
  5.  PL/SQL's general syntax is based on that of ADA and Pascal programming language. 
  6.  Apart from Oracle, PL/SQL is available in TimesTen in-memory database and IBM DB2. 


#### Features of PL/SQL

PL/SQL has the following features: 

  1.  PL/SQL is tightly integrated with SQL. 
  2.  It offers extensive error checking. 
  3.  It offers numerous data types. 
  4.  It offers a variety of programming structures. 
  5.  It supports structured programming through functions and procedures. 
  6.  It supports object-oriented programming. 
  7.  It supports the development of web applications and server pages. 


#### Advantages of PL/SQL

PL/SQL has the following advantages:


   1.  SQL is the standard database language and PL/SQL is strongly integrated with SQL. 
   2.  PL/SQL supports both static and dynamic SQL. 
   3.  Static SQL supports DML operations and transaction control from PL/SQL block. 
   4.  In Dynamic SQL, SQL allows embedding DDL statements in PL/SQL blocks. 
   5.  PL/SQL allows sending an entire block of statements to the database at one time. 
   6.  This reduces network traffic and provides high performance for the applications. 
   7.  PL/SQL gives high productivity to programmers as it can query, transform, and update data in a database. 


* Every PL/SQL statement ends with a semicolon (;).
* PL/SQL blocks can be nested within other PL/SQL blocks using BEGIN and END.
* Following is the basic structure of a PL/SQL block:

~~~

DECLARE
message varchar2(20) :='Hello , World!';
BEGIN
dbms_output.put_line(message);
END;
/
~~~
