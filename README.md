
## Comands for installing Apache http on AMI2 linux

```
//INSTALLING HTTP 
yum install -y httpd.x86_64
//START HTTP SERVICE
systemctl start httpd.service
//Service remains available across reboots
systemctl enable httpd.service
 //Echo into html page
 echo "HELLO WORLD " > /var/www/html/index.html
  echo "HELLO WORLD from $(hostname -f) " > /var/www/html/index.html

```
## Commands for installing an formating an ebs volume on to an ec2 instance

```
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-using-volumes.html
```
