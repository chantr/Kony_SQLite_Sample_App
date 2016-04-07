# Kony_SQLite_Sample_App

The application explains usage of phone DB using SQLite in Androif
1)Open a database using the steps mentioned in createDB function
2)Open a transaction using the databaseobject ID which you get on opening of the DB.
3)In the first callback,execute the SQL query using the syntax defined in createTable function.
4)Also write the necessary print statement in the remaining two callbacks i.e one success callback and error callback.