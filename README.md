### vpc module
this module is going to create the following resources
* vpc
* internet gateway
* 2 public subnets
* 1 public route vtable
* 2 private subnets
* 1 public route table
* association b/w public subnet anmd public route table
* association b/w private subnet anmd private route table

### arguments

** vpc_cidr ** (optional)- default value is 10.0.0.0/16 <br/>
** vpc_tags ** (optional)- user can provide tags, otherwise empty <br/>
** public_subnet_cidr ** (required)- user must provide 2 valid subets cidr <br/>
** public_subnet_names ** (required)- user must provide 2 valid subets names <br/>
** private_subnet_cidr ** (required)- user must provide 2 valid subets cidr <br/>
** private_subnet_names ** (required)- user must provide 2 valid subnet names <br/>
** public_route_table_tags ** (optional)- user can provide tags, otherwise empty <br/>
