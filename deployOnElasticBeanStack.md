As part of this we will setup dns and deploy artifact on elasticbean stack
Steps to create bucket
 1. AWS Dashboard-> S3-> Create Bucket
  Verifying creation of bucket on ec2 instance or other RHEL aws services
  
  To check all the repositories available on s3 box \
  > aws s3 ls
  
  copying content on to s3 box using command
  > aws s3 cp JQFileUpload.war s3://ep16-repo   
 
 
 2. configuring and setting permissions
  3. 
 
 
 
 Elastic Bean stack -- Life cycle
 1. Create App **eg ep16-app**\
    a. Create ENV -- can be Web server environment or Worker environment\
    b. configure it with domain name and othe configuration upload file from local or s3
 2. Create Environment
 
 
 
 PAAS| \
 IAAS|EC2|EBS|VPC|SUBNET|OS
 
 
 #AWS Storage types
 Block storage
 1. File system based
 2. SAN - 
 3. P2P - Point to point storage.
 Divided into 2 types\
 **EBS & Instances store**\
 **EBS** - *persistance on disck for time period* \
 **Instance store** - *Session level storage*\
 File storage
 
 Object storage
 
 
