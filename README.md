# Stored_Procedure_for_Copying_the_table_data_from_One_table_to_another_Table_with_in_the_MySQL_DB
Stored Procedure for Copying the data from One table to another Table with in the MySQL Database.

You can create this Stored Procedure in MySQL Database and copy the source table data to target table data with in the MySQL Database.

Call the Stored procedure :- 

CALL Copy_Data('dbname','source_tablename','target_tablename');

I.e , 

In Test MySQL Database Server  - 

CALL Copy_Data('<schema_name>','<source_table_name>','<target_table_name>');
