Chinook GitHub repo: https://github.com/lerocha/chinook-database/blob/master/ChinookDatabase/DataSources/Chinook_PostgreSql.sql

Download Chinook sql file using:     
<code>wget https://raw.githubusercontent.com/lerocha/chinook-database/master/ChinookDatabase/DataSources/Chinook_PostgreSql.sql</code>


*********************************************************
## Important!
Error fix due to Gitpod change
If you get the following error after typing `psql` in the terminal:

> psql: error: could not connect to server: No such file or directory

Please use the following command in the terminal to set an environment variable needed for it to work:

`set_pg`

And then try the `psql` command again

You will need to do this each time you return to your Gitpod workspace for the Database Management Systems videos.
*********************************************************