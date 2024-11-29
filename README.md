# AWS-project
This project demonstrates the creation of a Virtual Private Cloud (VPC) on AWS with both public and private subnets, configured route tables, security groups, and EC2 instances. The aim is to showcase a secure and scalable infrastructure for hosting applications and databases.

Project Setup
Step 1: Create the VPC
1. Go to the VPC Console.
2. Create a VPC with the CIDR block 10.0.0.0/16.
3. Add 2 public subnets and 1 private subnet.

Step 2: Configure Route Tables
1. Create a public route table:
2. Associate it with the public subnets.
3. Add a route for 0.0.0.0/0 pointing to the IGW.
4. Create a private route table:
5. Associate it with the private subnet.

Step 3: Create Security Groups
1. Public Security Group:
2. Allow SSH (22) from your IP.
3. Allow HTTP (80) from all.
4. Private Security Group:
5. Allow MySQL (3306) traffic only from the public subnets.

Step 4: Launch EC2 Instances
1. Deploy an EC2 instance in each public subnet for web servers.
2. Deploy a database instance in the private subnet.
3. Attach appropriate security groups.

Screenshots
Include screenshots of:
     - VPC Dashboard.
     - EC2 Instances list.
     - Route Tables.
      Security Groups





