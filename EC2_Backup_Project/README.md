\# EC2 Backup Using AMI and EBS Snapshots



\##  Objective

To create a backup of an Amazon EC2 instance using AMI and EBS snapshots

and restore the instance when required.



\##  AWS Services Used

\- Amazon EC2

\- Amazon Machine Image (AMI)

\- Amazon EBS

\- EBS Snapshots



\##  Architecture Overview

An EC2 instance is backed up by creating an AMI.

The AMI automatically creates EBS snapshots of attached volumes.



\##  Steps Performed

1\. Launched an EC2 instance

2\. Installed sample application

3\. Created an AMI from the instance

4\. Verified snapshot creation

5\. Launched a new EC2 instance from the AMI



\##  Outcome

Successfully backed up and restored an EC2 instance using AMI and snapshots.



\##  Evidence

Screenshots of EC2 instance, AMI creation, and snapshot details are included.



