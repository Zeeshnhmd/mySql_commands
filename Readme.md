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
