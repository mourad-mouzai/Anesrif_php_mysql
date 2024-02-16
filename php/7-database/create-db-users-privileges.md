
## MySQL Shell

Login


mysql -u user -p

#### Show Users
```sql
SELECT User, Host FROM mysql.user;
```

#### Create User
```sql
CREATE USER 'someuser'@'localhost' IDENTIFIED BY 'somepassword';
```

#### Grant Permissions
```sql
GRANT ALL PRIVILEGES ON * . * TO 'someuser'@'localhost';
FLUSH PRIVILEGES;
```

#### Show Grants
```sql
SHOW GRANTS FOR 'someuser'@'localhost';
```

#### Remove Grants
```sql
REVOKE ALL PRIVILEGES, GRANT OPTION FROM 'someuser'@'localhost';

```

#### Delete User
```sql
DROP USER 'someuser'@'localhost';
```
