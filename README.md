# Detect-s3-public-bucket

This template is used to detect whether you have "Public" bucket in S3. It will create a scheduled event (90 mins) to trigger lambda function to inspect s3 buckets. If there is public bucket, sns will send a message to your phone.


## Resource
- CloudWatch
- Lambda Function
- Lambda Permission
- IAM Role

## Architecture
![image](https://github.com/YYSU/Detect-s3-public-bucket/blob/master/Detect-s3-public-bucket.png)


# How to use this template
1. Download the “detect-s3-public-bucket.yml” from this repository

2. Open AWS CloudFormation Console, and click “Create stack“ -> “With new resources (standard) ”

3. Click “Upload a template file” and upload the “detect-s3-public-bucket.yml”. Click “Next”

4. Fill in the “Stack name“ and “Parameters”. Click “Next”.

5. You can set additional options for your stack or leave it as default. Click “Next”

6. Review the values entered while creating the stack. Remember to check “I acknowledge that AWS CloudFormation might create IAM resources with custom names.”. The final step is to click “Create Stack” and wait for the stack create complete.


For more information, please reference to this document[Creating a Stack on the AWS CloudFormation Console](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cfn-console-create-stack.html). 
