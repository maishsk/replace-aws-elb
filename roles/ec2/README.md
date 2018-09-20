Role Name
=========

Deploy an EC2 instance in AWS

Role Variables
--------------

The role accepts the following Variables

`vpc_id` - ID of the VPC that you will deploy into
`keypair`- Name of the keypair
`vpc_cidr_block` - CIDR of the VPC
`region` - AWS region
`instance_count` - Number of instances to deploy - should be 2
`instance_type` Instance Flavor
`use_public_ip` - Should the instances have a public IP address?
`source_dest_check_enabled` - Should Disable source/detination check be enabled? should be "no"
`iam_role` - Name of the role you would like to create
`volume_type` - EBS volume type
`root_disk_size` - disk size
`component_name` - Name of the component / service
`image_id` - AMI id (should be AWS linux/CentOS/RHEL)

License
-------

MIT
