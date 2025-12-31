\# S3 Event Notification Using SNS



\##  Objective

To send email notifications whenever an object is uploaded to an S3 bucket.



\## 🛠 AWS Services Used

\- Amazon S3

\- Amazon SNS

\- Email Subscription



\##  Architecture Overview

S3 bucket triggers an event notification which sends a message to SNS.

SNS delivers the message to the subscribed email address.



\##  Steps Performed

1\. Created an S3 bucket

2\. Created an SNS topic

3\. Subscribed email to SNS topic

4\. Configured S3 event notification

5\. Uploaded an object to S3



\##  Outcome

Email notification successfully received on object upload.



\##  Evidence

Includes screenshots of S3 bucket, SNS topic, subscription, and email alert.



