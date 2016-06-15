#Simple way to UP a Mysql Container!

#Helper
./install -h

```python
Options:

  -h, --help            show this help message and exit
  -d DBNAME, --database-name=DBNAME
                        Set the database name
  -q SQL_FILE, --sql-file=SQL_FILE
                        Sql file to execute once the instance is running
  -n INSTANCE_NAME, --instance-name=INSTANCE_NAME
                        (Optional) The name of the instance
```

#How to use
./install -d mydatabase -q /user/sql/mysql.sql -n mycontainerName