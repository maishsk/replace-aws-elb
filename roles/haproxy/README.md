Role Name
=========

Deploy HAproxy on an EC2 instance in AWS

Variables

`virtual_ip` - virtual IP that will be used - should be external to the CIDR block of the VPC

Dependencies
------------
## ec2 role
`component_name` - name of the component / service   
`region` - AWS region   

## Playbook

`node1_ip` - IP address of the first node (derived from the EC2 role)    
`node2_ip` - IP address of the second node (derived from the EC2 role)    


License
-------

MIT
