# Snowpipe-for-SQLServer
SQL Server to Snowflake data transfer.

Stream data from SQL Server to Snowflake using pyodbc.

```
1. Connect to SQL Server
    -> fetchmany
        -> multipart upload to s3
            -> COPY INTO Snowflake table
```        
