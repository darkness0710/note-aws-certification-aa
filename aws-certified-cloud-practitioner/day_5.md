# CHAPTER 3.1
- Access and Tour the AWS Console

# CHAPTER 3.2
- AWS Free Tier

# CHAPTER 4.1
- Your Piece of the AWS Cloud

# CHAPTER 5.1
- Overview of Identity and Access Management: Part 1

# CHAPTER 5.2
- Overview of Identity and Access Management: Part 2

# CHAPTER 5.3
- IAM Users, Groups, Roles, and Policies

# CHAPTER 5.4
- IAM: Just the FAQs

# CHAPTER 5.5
- Introduction to AWS Identity and Access Management (IAM)

[Được thực hành và sử dụng tài khoản test của academy linux set up role for groups]

CHAPTER 5.6
- IAM: Managing Users, Groups, and Role (Summary quiz)

- What does IAM stand for?
	- Internal Access Management
	- Identity Authentication Manager
	- Identity Alias Management
	- **Identity and Access Management**

- In this scenario, we want to grant an IAM User access to certain AWS services. What could we attach directly to an IAM User that will allow only that user access to that specific AWS service?
	- MFA
	- IAM Group
	- IAM Role
	- **IAM Policy**

- Which of the following is not an IAM best practice under "Security Status" in the IAM Dashboard?
	- Delete root access keys
	- Activate MFA on your root account
	- Use groups to assign permissions
	- **Store root access keys**
	- Apply an IAM password policy
	- Create individual IAM users

- Which of the following is not a method of getting or using MFA codes?
	- **Single sign-on**
	- API keys
	- Virtual MFA Device
	- Hardware key fob

- Any new IAM Users created are granted _____.
	- access to all AWS services.
	- Administrative access
	- **No access to AWS services.**
	- limited access to AWS services.

- Which of the following is not a rule that can be managed within the password policy management of IAM?
	- Case requirements
	- Password expiration
	- Number requirements
	- **Username length**
	- Password reuse
	- Length requirements

- An EC2 instance needs to access S3. What is the most appropriate way to provide the EC2 instance access to S3?
	- IAM Group
	- IAM User
	- IAM Policy
	- **IAM Role**

- Which of the following will grant permissions when directly attached to an IAM User?
	- IAM Role
	- IAM Group
	- MFA
	- **IAM Policy**

- Which AWS managed policy could be attached to an IAM User to grant all access permissions?
	- Billing
	- AdminAccess
	- PowerUserAccess
	- AdministratorAccess

- Which of the following is IAM commonly used to manage? (choose 4)
	- VPCs
	- **Users & Groups**
	- **Access Policies**
	- **Password Policies**
	- **API Access keys**

- Three developers need access to S3. What is the most appropriate and efficient way to give all the developers (IAM users) access to S3 out of the available answers? By efficient we mean consisting of the least amount of administration overhead.
	- **Add the developers to an IAM Group and attach an IAM policy to that group.**
	- Give each developer S3 credentials.
	- Assign a policy to each developer.
	- Assign an IAM to each developer.

- In this scenario, we have an IAM User with an AWSDenyAll policy, but this user is also in an IAM Group with access to various AWS services. These services include S3, EC2, VPC, and IAM. Which of the following resources can this user access?
	- VPC and EC2
	- S3 and VPC
	- **The IAM user cannot access any of the AWS services**
	- EC2
	- IAM, S3, EC2, and VPC

- What access privileges does a new IAM user have by default?
	- root
	- **AWS Console login access**
	- AdministratorAccess
	- PowerUserAccess

- What does MFA stand for?
	- Museum of Fine Arts
	- Multi-Factor Authenticator
	- Managed-Factor Authentication
	- **Multi-Factor Authentication**