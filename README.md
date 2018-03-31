# PHP database connection script
My simple scripts for connecting to database (script not finished but works fine for me).

Bascially it allows to easily connect to DB, get data via random user query. Allows to read/write data.

DatabaseConnection - returns array containing rows of column names and data in table
databaseTableToJson - takes 2 parameters (required) array of rows names and table of data 3rd. parameter is optional, and even empty string can be given. Returns array containing JSON formated data.
