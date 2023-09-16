### vpc 

This module is going to create 
    * vpc
    * Internet gateway 
    * 2 public subnets 
    * 2 private subnets 
    * 2 databse subnets 

### inputs 
* cidr_block(required) - user has to provide cidr blocks 
* enable_dns_hostnames(optional) - user can provide enable_dns_hostnames, ***default is true*** 
* enable_dns_support(optional) - user can provide enable_dns_support, ***default is true*** 
* common_tags(optional) - user can provide common_tags for all resources , default is empty 
* vpc_tags(optional) - user can provide vpc_tags for vpc resources , default is empty 
* igw_tags(optional) - user can provide internet gatway tags(igw_tags) for intenet gateway resources , default is empty
* public_subnet_cidr(required) - user must provide a list of public subnet CIDR 
* public_subnet_names(required) - user must provide a list of public subnet names
* azs(required) - user must provide 2 avaialability zones (azs)
* private_subnet_cidr(required) - user must provide a list of private subnet CIDR
* private_subnet_names(required) - user must provide a list of private subnet names
* database_subnet_cidr(required) - user must provide a list of database subnet CIDR
* database_subnet_names(required) - user must provide a list of database subnet names