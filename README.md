##Data Definition Language (DDL)

DDL refers to the CREATE, ALTER and DROP statements.
DDL or Data Definition Language actually consists of the SQL commands that
can be used to define the database schema. DDL allows to add / modify / delete
the logical structures which contain the data or which allow users to
access / maintain the data (databases, tables, keys, views...).

DDL is about "metadata".

##Data Manipulation Language (DML)
DDL refers to the INSERT, UPDATE and DELETE statements
DML allows to add / modify / delete data itself.

##Data Query Language (DQL)
DDL refers to the SELECT, SHOW and HELP statements (queries)
SELECT is the main DQL instruction. It retrieves data you need.
SHOW retrieves infos about the metadata. HELP... is for people who need help.

##Data Control Language (DCL)
DDL refers to the GRANT and REVOKE statements
DCL is used to grant / revoke permissions on databases and their contents.
DCL is simple, but MySQL's permissions are rather complex.
DCL is about security.

##Data Transaction Language (DTL) 
DDL refers to the START TRANSACTION, SAVEPOINT, COMMIT and ROLLBACK
[TO SAVEPOINT] statements
