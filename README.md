# php_crud_mysql

* dev/products.sql – contains the database table structure and sample data used in this project. Once you created your database in PhpMyAdmin, you can import this file.
* config/database.php – used for database connection and configuration.
* create.php – used for creating a new record. It contains an HTML form where the user can enter details for a new record.
* index.php – used for reading records from the database. It uses an HTML table to display the data retrieved from the MySQL database.
* read_one.php – used for reading one or single record from database. It uses an HTML table to display the data retrieved from the MySQL database.
* update.php – used for updating a record. It uses an HTML form which will be filled out with data based on the given “id” parameter.
* delete.php – used for deleting a record. It accepts an “id” parameter and deletes the record with it. Once it execute the delete query, it will redirect the user to the index.php page.
