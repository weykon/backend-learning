[some practices of database management](https://www.lucidchart.com/blog/database-management-best-practices)

# [Some posts for entry level](https://www.liaoxuefeng.com/wiki/1177760294764384/1179613436834240)

## Confuse on Data struct for Real World relationship.

 
 + struct classic : 
   +  layout model    (like trees) 
   +  net             (like grash) 
   +  table           (like excel)

> here I get a little thing, the SQL keep the fixed relationship, then we only record the big assert as a uuid on the SQL.  
> And The real assert locating is on the NoSQL which the database high performance within Cache derive.

I got this point because the post say, as now, more SQL in the internet, good for read and use. there are all in table form.

## Who are using Database

> this is a question as identity for user.

* DDL：Data Definition Language  
     > DDL allows users to define data, that is, create tables, delete tables, and modify table structures. Typically, DDL is performed by the database administrator.

* DML：Data Manipulation Language  
     > DML provides users with the ability to add, delete, and update data, which is the application's daily operation on the database.

* DQL：Data Query Language
     > DQL allows users to query data, which is usually the most frequent database operation.

So I think, writing code should keep these abstract level saving, such as Authorization.
