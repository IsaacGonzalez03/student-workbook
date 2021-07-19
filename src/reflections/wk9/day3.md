# Day 3
In a SQL table, what is the difference between information in a row and information in a column?
columns are the attributes while the rows represent the data

Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

  CREATE TABLE IF NOT EXISTS artists(
  id int NOT NULL primary key AUTO_INCREMENT comment 'primary key',
  name varchar(255) comment 'Name',
  age int NOT NULL COMMENT 'Age',
  description varchar(255) COMMENT 'Description'
) default charset utf8 comment '';

What is the difference between the following statements: