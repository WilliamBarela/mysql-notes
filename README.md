# mysql-notes

Herein you will find my notes on mysql syntax.

# connecting a given user

```bash
mysql -u username -p
```

# show current user:

```SQL
SELECT user();

/*
  mysql> SELECT user();
  +--------------------+
  | user()             |
  +--------------------+
  | username@localhost |
  +--------------------+
  1 row in set (0.00 sec)

  mysql> 
*/
```
