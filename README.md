# Module 10: Laravel Practice Assignment

__Task 1:__  
Create a new Laravel project named "MigrationAssignment" using the Laravel command-line interface.

__Task 2:__  
Within the project, create a new migration file named "create_products_table" that will be responsible for creating a 
table called "products" in the database. The "products" table should have the following columns:

- `id` an auto-incrementing integer and primary key.
- `name` a string column to store the product name.
- `price` a decimal column to store the product price.
- `description` a text column to store the product description.
- `created_at` a timestamp column to store the creation date and time.
- `updated_at` a timestamp column to store the last update date and time.

__Task 3:__  
After creating the migration file, run the migration to create the "products" table in the database.

__Task 4:__  
Modify the existing migration file "create_products_table" to add a new column called "quantity" to the "products" 
table. The "quantity" column should be an integer column and allow null values.


__Task 5:__  
Create a new migration file named "add_category_to_products_table" that will be responsible for adding a new column 
called "category" to the "products" table. The "category" column should be a string column with a maximum length of 50 characters.

__Task 6:__
After creating the new migration file, run the migration to add the "category" column to the "products" table.

__Task 7:__  
Create a new migration file named "create_orders_table" that will be responsible for creating a table called "orders" 
in the database. The "orders" table should have the following columns:

- `id` an auto-incrementing integer and primary key.
- `product_id` an unsigned integer column to establish a foreign key relationship with the "id" column of the "products" table.
- `quantity` an integer column to store the quantity of products ordered.
- `created_at` a timestamp column to store the creation date and time.
- `updated_at` a timestamp column to store the last update date and time.

__Task 8:__  
After creating the migration file for the "orders" table, run the migration to create the "orders" table in the database


### Submission:
1. Create a new fresh Laravel Project
2. Do your assignment
3. Push the project in github
4. Submit public GitHub URL

### Project Setup
Open the terminal and run the following commands:
```text
git clone https://github.com/net-chanchal/MigrationAssignment.git
cd MigrationAssignment
composer update
```






