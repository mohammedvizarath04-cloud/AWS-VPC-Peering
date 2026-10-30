AWS-VPC-Peering
This project demonstrates how to establish private network connectivity between two Amazon Virtual Private Clouds (VPCs) using AWS VPC Peering

The infrastructure is configured within a single AWS account and region (Mumbai – ap-south-1).

Architecture

- VPC A: 10.10.0.0/16
- VPC B: 10.20.0.0/16
- Public and private subnets
- Internet Gateway for VPC A
- VPC Peering connection between VPC A and VPC B
- Custom route tables
- Security groups
- Three EC2 instances:
  - Bastion Host
  - App-A
  - App-B

AWS Services Used
- Amazon VPC
- VPC Peering
- Amazon EC2
- Internet Gateway
- Route Tables
- Security Groups

 Key Features
- Private communication between two VPCs.
- Secure SSH access through a Bastion Host.
- Custom routing between VPC networks.
- Network access controlled using security groups.

Implementation Status
AWS infrastructure has been created and configured. Full connectivity testing is pending.

 Learning Outcomes
- Understanding AWS networking.
- Creating and configuring VPCs and subnets.
- Establishing VPC Peering.
- Configuring route tables and security groups.
- Deploying EC2 instances in public and private subnets.

Author
mohammed vizarath sultan
