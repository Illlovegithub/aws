# aws
stuff

## Short notes
Root account: Admin account. Should only be used for admin purposes e.g. creating new accounts/groups, billing etc.

IAM account: These are the actual user accounts. 
- Alias: KetelsenKent
- Username: ketelsen
- Password: IS IT A QUEEN ? 

ec2 url: ec2-3-126-51-67.eu-central-1.compute.amazonaws.com
username: ubuntu
Note: See desktop ssh config file for full setup

EC2 Instance details:
- Security Group, firewall - currently only my desktop IP allowed

- Volume Storage (EFS vs EBS)
-- EBS is a storage system allocated for a single instance. Essentially just a hard drive
--- /dev/sda1
-- EFS 
--- Is a simple file storage system on the harddrive. Requires a subnet as it's available for multiple (and different) EC2 instances. Think multiple DBs writing to the same storage volume
