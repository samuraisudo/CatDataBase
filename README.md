# CatDataBase
> Open page http://domain/CatDataBase/install.php for install.
> Enter new Login and Password
# To connect, use an array with login and password
> $key = array("login", "password");
# Using
> cat_db(); # to create a database<br>Example:<br>cat_db("db_name", $key); # $key - this is an array with login and password<hr>
> cat_del_db(); # deletes the database<br>Example:<br>cat_del_db("db_name", $key);<hr>  
> cat_edit_db(); # rename database<br>Example:<br>cat_edit_db("old_db_name", "new_db_name" $key);<hr> 
> <hr>
> cat_table(); # to create a table<br>Example:<br>cat_table("db_name", "new_table", $key);<hr>
> cat_del_table(); # deletes the table<br>Example:<br>cat_del_table("db_name", "table_name", $key);<hr>  
> cat_edit_table(); # rename table<br>Example:<br>cat_edit_table("db_name", "old_table", "new_table", $key);<hr> 
> <hr>
> cat_column(); # to create column and edit data in column<br>Example:<br>cat_column("db_name", "table_name", "column_name", $key);<hr>
> cat_del_column(); # deletes the column<br>Example:<br>cat_del_column("db_name", "table_name", "column_name", $key);<hr>  
> cat_edit_column(); # rename column<br>Example:<br>cat_edit_column("db_name". "table_name", "column_old_name", "column_new_name", $key);<hr> 
> cat_read(); # For read data<br>Example:<br>echo(cat_read("db_name", "table", "column", $key)); 
