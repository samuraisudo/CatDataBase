# CatDataBase
> Open page http://domain/CatDataBase/install.php for install.
> Enter new Login and Password
# To connect, use an array with login and password
> $key = array("login", "password");
# Using
> cat_read(); # For read data<br>Example:<br>echo(cat_read("db_name", "table", "column", $key)); # $key - this is an array with login and password<br>
> cat_db(); # to create a database<br>Example:<br>cat_db("db_name", $key);<br>
> cat_del_db(); # deletes the database<br>Example:<br>cat_del_db("db_name", $key);<br>  
> cat_edit_db(); # rename database<br>Example:<br>cat_edit_db("old_db_name", "new_db_name" $key);<br> 
