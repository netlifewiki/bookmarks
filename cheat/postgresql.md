### Disable paging in postgresql

`\pset pager off`

### Connect to a database

`\c database_name`

### Show tables and sequences in current schema

`\d`

### Describe a table

`\d table_name`

### Show only tables with their size (`+`) in current schema

`\dt+`

### Show databases with their privileges and size (`+`) 

`\l+`

### Show available schemas

`\dn`

### Return back to shell 

`\q`

### List users and their access privileges on databases

`\du`

### List default access privileges

`\ddp`

### List tables, views and sequences with their associated access privileges

`\dp`

### List of roles

`SELECT rolname FROM pg_roles;`

### Detail of a role 

`SELECT * FROM pg_roles WHERE rolname = '...'`