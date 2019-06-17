# Snowpipe-for-SQLServer
SQL Server to Snowflake data transfer.

Stream data from SQL Server to Snowflake using pyodbc.

```
1. Connect to SQL Server
    -> loop
        - fetchmany
        - multipart upload to s3
    -> Bulk COPY INTO Snowflake table
```        
