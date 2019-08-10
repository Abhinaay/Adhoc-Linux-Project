# Adhoc-Redhat-Tasks

## Linux Project
### Case1 : Create a Single tier Architect enviroment for CMS like Wordpress, Magento App on AWS Insatnce.

Server Configure Details:

AWS Instance Type: t2.micro
AMI or Server OS: CentOS 7 (x86_64) - with Updates HVM

Disk Layout: 
```
     -- Disk1: 8GB for / (for the root volume)
     -- Attach 2 more encrypted Volume with disk accidental termination protection policy at least 4GB Size of volume when you lauched your instance .
```
