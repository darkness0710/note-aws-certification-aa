# CHAPTER 6.1
- Networking 101

# CHAPTER 6.2
- Conceptual Overview of VPCs

# CHAPTER 6.3
- A Walkthrough of VPC Basics

# CHAPTER 6.4
- Internet Gateways and Route Tables

# CHAPTER 6.5
- VPC Subnets, Security Groups, and NACLs

- Which of the following will create subsections of a VPC?
	- ELB
	- **Subnet**
	- NACL
	- Internet Gateway
	- Security Group

- What is a NACL?
	- A firewall on the instance level
	- A table of rules that directs traffic flow in a network
	- **A firewall on the subnet level**
	- A logically isolated section of AWS

- Which of the following is true about subnets?
	- Subnets are stateless firewalls
	- Subnets are stateful firewalls
	- **Subnets cannot span AZs**
	- Subnets connect a subsection of the internet to another

- What does a route table do?
	- **Directs traffic within a network**
	- Allows or denies inbound/outbound traffic on the subnet level
	- Allows or denies inbound/outbound traffic on the instance level
	- Connects resources within a VPC to the internet

- Which of the following are true statements about public subnets and private subnets? (Choose 2)
	- A public subnet points to a private subnet
	- A private subnet has a route table pointing to an Internet Gateway
	- **A public subnet has a route table pointing to an Internet Gateway**
	- **A private subnet does not have a route table pointed to an Internet Gateway**
	- A public subnet does not have a route table pointed to an Internet Gateway

- A security group is a _ on the _ level.
	- Firewall, AWS
	- Firewall, VPC
	- Firewall, subnet
	- **Firewall, instance**

- How many subnets are created by default in each region when an AWS account is created?
	- 3 subnet per Availability Zone
	- **1 subnet per Availability Zone**
	- 2 subnet per Availability Zone
	- no subnet per Availability Zone

- How many Internet Gateways can be attached to a VPC at a time?
	- Unlimited
	- 2
	- 5
	- **1**

- How many VPCs can an EC2 instance be attached to at a time?
	- 2
	- **1**
	- 3
	- 4

- How many VPCs are created by default in a region?
	- 3
	- 4
	- 2
	- *1*

- Which of these statements is true of subnets? (Choose 3)
	- We can not add more than one subnets in each AZ.
	- Subnets can span AZs.
	- **Subnets cannot span AZs.**
	- **The default VPC already has subnets created for each AZ by default.**
	- **We can add one or more subnets in each AZ.**

- Which of the following is descriptive of an Internet Gateway?
	- A stateful firewall for inbound/outbound traffic
	- A logically isolated section of AWS
	- **A route to and from the internet**
	- A stateless firewall for inbound/outbound traffic

- What does VPC stand for?
	- Virtualization Platform Cloud
	- Virtual Public Cloud
	- **Virtual Private Cloud**
	- Virtualized Private Cloud

- In this scenario, we have a NACL with the following rules.
	Rules	Traffic
	Rule#1	Allow SSH
	Rule#2	Allow HTTP
	Rule#3	Deny All
	Rule#4	Allow All
	Which is true based on the rules within this NACL?

	- **All traffic except SSH and HTTP will be denied**
	- All traffic will be allowed
	- All traffic will be denied
	- SSH traffic will be denied

- Which of the following will connect instances within a VPC to networks outside of the VPC and provides Internet access for the VPC?
	- Subnet
	- NACL
	- Route Table
	- **Internet Gateway**

- VPCs span all of these except for _____.
	- Availability Zones
	- **AWS Regions**
	- Subnets
	- AWS resources

- What is a VPC?
	- A type of AWS account
	- A subsection of a private network
	- **A logically isolated section of the AWS Cloud used as a virtual network**
	- A public cloud

- A subnet is a _____.
	- VPC
	- Firewall
	- Table that directs traffic
	- **Subsection of a network**