# Snow-pusher-for-SQLServer
SQL Server to Snowflake data transfer.

Stream data from SQL Server to Snowflake using pyodbc.

![Snow pusher](https://raw.githubusercontent.com/pydemo/Snow-pusher-for-SQLServer/master/snow-pusher.jpg "Snowflake data load.")

```
1. Connect to SQL Server
    -> loop
        - fetchmany
        - multipart upload to s3
    -> Bulk COPY INTO Snowflake table
```        


## Other scripts
https://github.com/pydemo/snowcli - Snowflake cli.


https://github.com/pydemo/large-file-split-compress-parallel-upload-to-S3 - Chunked large file upload to S3.
