# Executive Summary
The goal of this lab is to give intro on SQl and what it's used for. You will learn about the big Data and the four V's. You will learn to look at the table and figure out the primary key and foreign key.
# Data, Information and Knowledge 
## Relational Data

* What is the difference between data, information and knowledge? 

 Data is fragmented pieces of symbols and characters strung together, information is refined data whereas the knowledge is useful information. Additionally, data can lack context when looked at singularly, whereas information gives context to data and knowledge brings depth in understanding  to such information.
Data cannot independently be a basis for question formation; Information is a text that answers the questions a who, when, what, or where while knowledge is a text that answers the questions of why and how. The final difference we can take into consideration is that data and information are easily transferable while to transfer knowledge one requires learning.

* If you were creating a database for a small company and two tables you identify are customers and orders explain the following:
(be sure to use the example in the chapter as a guide - customers and orders would be like clubs and events) 
a) What would be the primary key in the customers and orders table? 

  The primary key would be customer first middle and last name as a unique key of identifying them. 

b) How would the customers and orders table be related? 

  They are related by the common orders that the customer orders. 

c) What would be the foreign key in the orders table? 

  Foreign key would be an id assigned to the customer. Like an order number. 
 
d) The orders table would likely have a date field.  Explain why it is important to properly define the data type of a field. 

 It is important so you know when order was placed and is needed. 
 
## Big Data

* Briefly describe the four "Vs" of big data 

 IBM data scientists break big data into four dimensions: volume, variety, velocity and veracity.
Volume is scale of data.
Velocity is analysis of streaming data.
Variety is different forms of data.
Veracity is uncertainty of data. 

* What types of technology have driven the increased need for big data? 

 Big data is a specific indication that is used to describe the vast assemblage of data that is huge in size and exponentially increasing with time. It simply specifies the massive amount of data that is hard to stock, investigate, and transform with conventional tools of management.  Lots of companies have driven the need for big data such as AI, No SQL Database, R Programming and many more. 
 
# Structured Query Language (SQL)
* Explain RDBMS and how it relates to SQL and the purpose of SQL 

  A database management system (DBMS) is a system software for creating and managing databases. The DBMS provides users and programmers with a systematic way to create, retrieve, update and manage data.
RDBMS stands for Relational Database Management System. It’s a database management system that is based on the relational model, storing data in relational databases.
RDBMS is a database management system.
And SQL is the language used for communicating with data in an RDBMS.
Or in the plain term, RDBMS is a book and SQL is the language being used in the book. You want to read or write to the book? Use SQL.


* Pick two related tables from the diagram provided in the "module - SQL" and explain the relationship between them
a) which is the primary key?

 Customer ID is the primary key.
 
 b) which is the foreign key?

  Order Id.
  
* Using W3Schools, try out a 
a) select statement 
a) where clause 
and upload screenshots of the results.
* Explain how SQL injections are a security threat and what can be done to reduce the issue. 

  SQL injection attacks pose a serious security threat to organizations. A successful SQL injection attack can result in confidential data being deleted, lost, or stolen; websites being defaced; unauthorized access to systems or accounts and, ultimately, compromise of individual machines or entire networks. Twenty years after its discovery, SQL injection remains a top database security concern.
The only sure way to prevent SQL Injection attacks is input validation and parametrized queries including prepared statements. The application code should never use the input directly. The developer must sanitize all input, not only web form inputs such as login forms.

  
# Conclusion
I learned about SQL and what it is used for. I learned about how SQL works with RDBMS.I learned about the four V's of big data. I didn't know anything about them before this lab.
