## JP02-usingSQLDatabase

- Database (included)
  Into the folder "`data/blog-db`" there are the files to import the database I'm using in this project.

- data/database.js
  I'm using a SQL Database, be sure you are using the database name, user and password.

  ```
  const pool = mysql.createPool({
  	host: "localhost",
  	database: "blog", <-- Check the database name
  	user: "root", <-- Check the username
  	password: "useYourPassword", <-- Check the password
  });
  ```

- Check that you installed the mysql2, you can install it with `npm install --save mysql2`
