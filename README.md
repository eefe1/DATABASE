# DATABASE
NOTES FROM DATABASE LAB


-To create a DB table with primary and/or foreign keys, the following syntax of
CREATE TABLE is used.
SYNTAX: CREATE TABLE table_name (
col1_name col1_datatype,
colN_name colN_datatype,
PRIMARY KEY (column_nameX),
FOREIGN KEY (column_nameX)
 REFERENCES table_name (column_nameZ)
);
-To insert a row (record) in a DB table, the command INSERT is used.
SYNTAX: INSERT INTO table_name VALUES (value1, value2 … valueN);
 or for providing data to any columns, in any order
SYNTAX: INSERT INTO table_name
(col_name1, col_name2 … col_nameN) VALUES
(value1, value2 … valueN);

- Bear in mind that while integers do not require any quotes, strings should be always
enclosed within single quotes, as in 'string'.
-To display the contents of a DB table the SELECT statement is used. For displaying
all the columns just use the star (*).
SYNTAX: SELECT * FROM table_name;
 Alternatively, the exact columns to be displayed can be specified:
SYNTAX: SELECT col_name1, col_name2 … col_nameN FROM table_name;
-To delete (destroy) a DB table, the command DROP TABLE is used.
SYNTAX: DROP TABLE table_name;

