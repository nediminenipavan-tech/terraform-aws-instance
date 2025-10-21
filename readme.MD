# AWS EC2 Instance 

This module creates EC2 instance.

### Inputs

* ami_id - (optional) Defaults to ami-09c813fb71547fc4f
* instance_type - (required) User must supply instance type either t3.micro or t3.small or t3.medium
* sg_ids - (required) user must supply a list of security group IDS to attach Ec2 instance
* tags - (optional) user can supply the tags attach to ec2 instance

### Outputs

* public_ip - Public IP of the instance created 
* private_ip -private IP of the instance created