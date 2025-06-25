# mysql-queries-task2

# SQL Operations

This extension to the Retail Management System project demonstrates additional SQL operations:

- Adding more sample data
- Handling `NULL` values
- Performing updates
- Executing deletions with proper constraints

## Additional Inserts

Added rows in each table (`CUSTOMER`, `CATEGORY`, `SUPPLIER`, `PRODUCT`, `ORDERS`). These demonstrate real-world data entry and relationship mapping.

Inserted three rows with null values:
1. A customer with a missing phone number
2. A supplier with a missing email address
3. A product with unknown stock

## Update Operations

The following `UPDATE` queries demonstrate how to modify data:

1. Update product price
2. Update customer address
3. Update order quantity and amount

## Delete Operations

`DELETE` queries were used to remove data safely:

1. Delete a specific customer
2. Delete a supplier
3. Delete a product with `NULL` stock 
