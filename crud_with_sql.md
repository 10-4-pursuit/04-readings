# CRUD Operations with SQL

## Overview
CRUD operations (Create, Read, Update, Delete) are fundamental tasks in database management and are used to manipulate data stored in SQL (Structured Query Language) databases. Understanding how to perform CRUD operations with SQL is essential for developers working with relational databases.

## Core Concepts

### 1. Create Operation (INSERT)
The create operation involves adding new records to a database table. In SQL, the INSERT statement is used to perform this operation. Example:
``` sql
INSERT INTO users (name, age) VALUES ('John', 30), ('Jane', 25);
```

### 2. Read Operation (SELECT)
The read operation involves retrieving data from a database table. In SQL, the SELECT statement is used to perform this operation. Example:
``` sql
SELECT * FROM users;
```

### 3. Update Operation (UPDATE)
The update operation involves modifying existing records in a database table. In SQL, the UPDATE statement is used to perform this operation. Example:
``` sql
UPDATE users SET age = 35 WHERE name = 'John';
```

### 4. Delete Operation (DELETE)
The delete operation involves removing records from a database table. In SQL, the DELETE statement is used to perform this operation. Example:
``` sql
DELETE FROM users WHERE name = 'Jane';
```

## Conclusion
CRUD operations are essential for manipulating data stored in SQL databases. By understanding how to perform create, read, update, and delete operations with SQL, developers can efficiently manage and manipulate data in relational databases.
