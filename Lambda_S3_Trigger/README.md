# AWS Lambda Trigger Using S3

##  Objective
To automatically trigger a Lambda function whenever a file is uploaded to S3.

##  AWS Services Used
- Amazon S3
- AWS Lambda
- IAM

##  Architecture Overview
S3 bucket triggers a Lambda function using event notifications.
The function processes the uploaded object.

##  Steps Performed
1. Created IAM role with permissions
2. Created Lambda function using Python
3. Configured S3 trigger
4. Uploaded file to S3 bucket
5. Verified Lambda execution

##  Outcome
Lambda function triggered automatically on S3 upload.

##  Evidence
Includes Lambda logs, S3 upload screenshots, and IAM role details.
