# aws-setup
## Download AWS CLI from the aws server
## Create secrete key
  *Download accesskey*

Console setup
** To set the configuration for the first time. Run below command**
Change your region as per requirement and cost --> follow this link for knowing price of region and latency 
https://www.concurrencylabs.com/blog/choose-your-aws-region-wisely/

```
Run command: 
aws configure
===========================
AWS Access Key ID [None]: xxxx
AWS Secret Access Key [None]: xxxx
Default region name [None]: ap-south-1
Default output format [None]: table
```
Resources by Region to know vpc's & their subnet
-----------
on aws dashboard --> under *Networking & Content Delivery*--> **Subnet**  


EC2 = Elastic compute cloud.
on aws dashboard --> under allservices--> Compute --> EC2


Before launching EC2 application we need to set security level roles.
*Security groups*
By default security group is assigned to ec2 application which is only accessable between the subnet private range.


Creating a new security group
-> click on new security group button
Fill in details like
```
groupname
description
```
create rule for the security group
inbound 
outbound 

create keypairs
download pem key
launch ec2 instance --> select low cost for training purpose. Even if amazon says free tire its only for limited services.

1. Choose AMI we created
2. Choose Instance
3. configure Instance
4. Add storage
5. Add tags
6. Add security group
7. pair key 
8. launch instance

Once application is launched.
Note if you are on linux/mac we just need pem key as is

Only if on windows
Inorder to open it in windows machine. you have to make an setup to connect password less.  

By creating a ppk key for putty to connect using puttygen tool <-- puttygen tool takes pem file in order to convert to ppk file

Once you have the ppk file. open putty and navigate to ssh section->auth and then load the ppk file which was created.







