# incident
How to deal with incidents

1. Check number of connections to RDS by below command.
```sql
SHOW PROCESSLIST;
```

2. Kill the specified process.
```sql
CALL mysql.rds_kill({id});
```
