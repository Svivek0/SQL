# SQL
 * Syntax of Create Table Statement
CREATE TABLE table_name ( column1 datatype, column2 datatype, column3 datatype, .... );


A copy of an existing table can be created using a combination of the CREATE TABLE statement and the SELECT statement.

Syntax:
CREATE TABLE new_table_name AS SELECT column1, column2,...
FROM existing_table_name;

*Alter table statement
A DBA can make changes to the table structure or column definitions after the table has been created in the database.
The DDL command ALTER TABLE is used to perform such actions.
The ALTER TABLE statement is used to add, drop, rename, and modify a column in a table.
Syntax:
ALTER TABLE table_name ADD column_name datatype;

 *To delete a column in an existing table:

Syntax:

ALTER TABLE table_name DROP COLUMN column_name;

*To rename a column in an existing table:
Syntax:
ALTER TABLE table_name RENAME COLUMN existing_column_name
To new_column_name; 



