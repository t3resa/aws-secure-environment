I have created a CloudFormation Script that configures a secure client environment.

Architecture:
 - A VPC with a Public and Private Subnet on ONE availabilty zone. The Internet Gateway is attached to the VPC and the NAT Gateway is attached to the Public Subnet to allow the Private Subnet internet access. There is a jumpbox security group created for your bastion instance. This architecture works with OpenVPN.
 - SFTP Server is used for data transfer


***There are no intstances being created