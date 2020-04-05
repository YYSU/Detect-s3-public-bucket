# Detect-s3-public-bucket

This template is used to detect whether you have "Public" bucket in S3. It will create a scheduled event (90 mins) to trigger lambda function to inspect s3 buckets. If there is public bucket, sns will send a message to your phone.


## Resource
- CloudWatch
- Lambda Function
- Lambda Permission
- IAM Role
