"# Database-schema" 
The database shema above models a resuturant management database where in the database you have tables for the customer, the staff and the customer orders.
The schema above shows the relationship between the tables. customer_table represents the customer information. The primary key there is the customer_id. 
The Order_table shows the customer's order information. The primary key there is the order_id. It has two foreign keys which are the customer_id an staff_id.
The staff_table shows staff information and the primary key is the staff_Id.


queries for the database
-select First_name,Last_name from customer_table. ===it return all firstnames and last names for customer_table.
-select telephone_number from customer_table === returns all customer telephone numbers
-select adress from customer_table === returns adress for all customers
-slect dinstict items from Orders_table === returns all dinstict items
-select staff_id from staff_table ==== returns all staff id from staff_table
