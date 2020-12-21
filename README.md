# Ansible playbook to create EC2 instance 

Playbook to create a key pair and create 2 ec2 instances 
- bastion
- webserver

 using 2 roles
- aws_vpc
- aws_sg

Roles:
- aws_vpc : Role to create a VPC with 3 Public subnet & 3 private subnet
- aws_sg: Role to create to create Secrity group for bastion server and weserver
