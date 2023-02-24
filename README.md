# Documentation for integrating AWS with Snowflake:
There are 3 steps:
1.Login into Snowflake account
2.Login into AWS account and create s3 bucket, create IAM role.
3.Write a command in snowflake worksheet to link AWS with Snowflake.
                     CREATE STORAGE INTEGRATION name
                     TYPE = EXTERNAL_STAGE
                     STORAGE_PROVIDER = S3
                     ENABLED = TRUE
                     STORAGE_AWS_ROLE_ARN = ’  ‘
                     STORAGE_ALLOWED_LOCATIONS = (' ');
