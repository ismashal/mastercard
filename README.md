

Install terraform 12 version and configure AWS Cli 

export AWS_ACCESS_KEY_ID=""
export AWS_SECRET_ACCESS_KEY=""
export AWS_DEFAULT_REGION="us-west-2"

terraform plan
terraform apply 

Note : It will create the following resoucres

VPC, private/public subnets, RouteTables, IG,NAT gateway, ASG, ELB, httpd webserver 

Chanlleges:

Autoscalling add/remove nodes using the load
Mounting the EBS to var/log and  manage the storage / growth of logs




