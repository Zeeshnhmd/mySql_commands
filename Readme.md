<details open>
<summary><h3> CREATE USE DELETE ENABLE/DISABLE DATABASE</h3></summary>
<br/>
Create a Database

```sql
CREATE DATABASE myDB;
```

To see the changes are reflected navigate to **Schemas** tab and refresh that tab.

Use the create Database

```sql
USE myDB;
```

Delete the database

```sql
DROP DATABASE myDB;
```

Make the database READ ONLY

```sql
ALTER DATABASE myDB READ ONLY = 1;
```

Disable database READ ONLY

```sql
ALTER DATABASE myDB READ ONLY = 0;
```

</details>

<details open>
<summary><h3> Creating table and columns</h3></summary>
<br/>

Creating a table

```sql
CREATE TABLE employees (
  employee_id INT,
  first_name VARCHAR(50),
  last_name VARCHAR(50),
  hourly_pay DECIMAL(5,2),
  hire_date DATE
);
```

- employees is table name.
- INT, VARCHAR, DECIMAL, DATA this are DATATYPES.
- VARCHAR(50) means only 50 characters are allowed.
- DECIMAL (5,2) first value 5 means amount digits and 2 means two decimal places.
</details>
