# PostgreSQL

## Basics Command

### Database

<table style="width:100%;">
<thead>
<tr>
<th>Command/Syntax</th><th>Description</th>
</tr>
</thead>
<tbody>
<tr><td> CREATE DATABASE db_name</td><td> Create new database</td></tr>
<tr><td> DROP DATABASE db_name</td><td> Delete database</td></tr>
<tr><td> \c  db_name</td><td> Connect/Select database</td></tr>
<tr><td> \l </td><td>Print list of database</td></tr>
</tbody>
</table>

### Table

<table style="width:100%;">
<thead>
<tr>
<th>Command/Syntax</th><th>Description</th>
</tr>
</thead>
<tbody>
<tr><td>CREATE TABLE table_name(<br>
    column1 datatype,<br>
    column2 datatype...<br>
);</td><td>Create new table without constraints</td></tr>
<tr><td>CREATE TABLE table_name(<br>
    column1 datatype NOT NULL,<br>
    column2 datatype NOT NULL PRIMARY KEY...<br>
);</td><td>Create new table with constraints</td></tr>
<tr>
<td>DROP TABLE table_name</td><td>Delete Table</td></tr>
<tr>
<td>\d table_name</td><td>Describe Table</td></tr>
<tr>
<td>ALTER TABLE table_name ADD field_n datatype;</td><td>Add New Field in the Table</td></tr>
<tr>
<td>ALTER TABLE table_name DROP field_name;</td><td>Delete field from the Table</td></tr>
<tr>
<td> INSERT INTO table_name (<br>
    column1,column2,column3,column4)<br>
     VALUES (values1,values2,values3,values4);</td><td>Insert Data in table</td></tr>
</tbody>
</table>
