# terraform AWS EC2 module

## inputs:

* ami_id (optional): ami_id is optiona. default value is ami-09c813fb71547fc4f
* security_group_ids (optional): list of security group ids. default value is sg-0f7f3c2d3ce2b40a3
* instance_type (optional): default value is t2.micro
* tags (optional): default value is empty

## outputs:  
* public_ip: public ip of the instnace created 
* private_ip: private ip of the instnace created
* instance_id: instance is created
