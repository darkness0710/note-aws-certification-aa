# CHAPTER 14.1
- Lambda

# CHAPTER 15.1
- AWS Shared Responsibility Model

# CHAPTER 15.2
- Security and Compliance on AWS

# CHAPTER 15.3
- AWS Key Management Service

# CHAPTER 15.4
- Security and Compliance: Just the FAQs and Wrap It Up!

# CHAPTER 16.1
- Additional AWS Services

```
Amazon Polly là dịch vụ chuyển đổi văn bản thành giọng nói chân thực.
Amazon Rekognition giúp dễ dàng thêm phân tích hình ảnh và video vào ứng dụng của bạn bằng công nghệ deep learning.
Amazon EMR là nền tảng dữ liệu lớn trên nền tảng đám mây hàng đầu ngành để xử lý lượng lớn dữ liệu bằng các công cụ nguồn mở như Apache Spark, Apache Hive, Apache HBase, Apache Flink, Apache Hudi và Presto
Amazon Athena là một dịch vụ truy vấn tương tác giúp bạn dễ dàng phân tích dữ liệu trong Amazon S3 bằng cách sử dụng SQL tiêu chuẩn.
```

- In regards to the AWS Shared Responsibility Model, for which of these is AWS Responsible? (Choose 3)
	- **CPU on physical hardware**
	- Security Groups
	- NACLs
	- **Availability Zones**
	- IAM
	- **Host virtualization hardware**

- In this scenario, we want a video/image analysis service for facial recognition purposes. Which of the following services can serve this purpose?
	- Amazon Athena
	- Amazon EMR
	- **AWS Rekognition**
	- Amazon Polly

- What AWS Service can be used to centrally manage policies from a master account for security and compliance purposes?
	- AWS Systems Manager
	- AWS Artifact
	- **AWS Organizations**
	- IAM

- What AWS service will perform serverless computing?
	- VPC
	- EC2
	- Lightsail
	- **AWS Lambda**

- Which of the following languages does AWS Lambda currently support? (Choose 3)
	- **Node.js**
	- **Ruby**
	- Swift
	- R
	- **Java**
	- PHP

- In this scenario, an AWS datacenter was breached by unauthorized personnel. In terms of the AWS Shared Responsibility Model, who is responsible for this?
	- Customer
	- No one is responsible
	- **AWS**
	- AWS and Customer

- Which of the following is not a use case for AWS Lambda?
	- Real-time stream processing
	- **Data warehousing**
	- Real-time file processing
	- Data processing

- Which of these are allowed penetration testing without prior approval from AWS? (Choose 3)
	- **RDS**
	- **CloudFront**
	- **EC2 instances**
	- Route 53
	- Port flooding

- What is Amazon Mechanical Turk used for?
	- Buying and selling unused EC2 reserved instances.
	- Scheduling and running a batch of computing jobs.
	- Getting deploy ready software.
	- **Crowdsourcing marketplace where you can outsource tasks.**

- What is AWS Lightsail?
	- Virtual Private Networking Service
	- **One of AWS's VPS Services**
	- Elastic Container Service
	- Serverless Compute Service

- Which of the following penetration testing activities are prohibited on AWS? (Choose 3)
	- Penetration testing of EC2 instances
	- **Port flooding**
	- Penetration testing AWS CloudFront
	- **DDoS attacks**
	- **DNS Zone walking via Amazon Route 53 hosted zones**

- In regards to the AWS Shared Responsibility Model, AWS maintains responsibility __
	- in the cloud
	- **of the cloud**
	- of the customers
	- for no part of the cloud

- Which of these statements are true in regards to AWS Lambda? (Choose 4)
	- AWS Lambda does not integrate with other AWS services.
	- AWS Lambda is not scalable.
	- AWS Lambda does require server management.
	- **AWS Lambda only charges when code is executed and running.**
	- **AWS Lambda is scalable.**
	- **AWS Lambda does not require server management.**
	- **AWS Lambda integrates with most AWS services**

- Which of the following services is a serverless interactive query service for analytics?
	- AWS Lambda
	- **Amazon Athena**
	- Amazon EMR
	- Amazon Aurora

- What is AWS KMS?
	- A storage service
	- A user management service
	- **A key management service**
	- A firewall

- In regards to penetration testing on AWS, which of these statements is true? Please select the most appropriate response.
	- All penetration testing on AWS requires permission.
	- **Limited penetration testing is allowed, but some require permission from AWS.**
	- No penetration testing is allowed on AWS.
	- All penetration testing is allowed on AWS.

- Which of the following services are considered by AWS to be a serverless platform? (Choose 3)
	- Amazon EC2
	- IAM
	- **Amazon Aurora**
	- **Amazon Athena**
	- **AWS Lambda**
	- AWS Direct Connect

- What service does AWS KMS integrate with for logging of key events?
	- **CloudTrail**
	- S3
	- AWS Storage Gateway
	- SNS

- In regards to security and compliance on AWS, what AWS service is a threat detection service that monitors for threats to AWS accounts and workloads?
	- AWS WAF
	- AWS Shield
	- Amazon Inspector
	- **AWS GuardDuty**

- Which of the following are options for creating Lambda functions? Please select the most appropriate answer.
	- **Author from scratch, using a blueprint, and browsing the serverless app repository**
	- Only Author from scratch and use a blueprint
	- AWS Lambda does not require functions
	- Only Author from scratch

- In this scenario, we want to enable notifications for KMS activity. What AWS service could be used with AWS KMS to send these notifications?
	- **SNS**
	- CloudTrail
	- S3
	- AWS KMS

- What two services in combination, aid in DDoS mitigation?
	- CloudFront and RDS
	- Route 53 and EC2
	- IAM and S3
	- **CloudFront and Route 53**

- What is the AWS Shared Responsibility Model?
	- **The model used to define the responsibilities that AWS has of the cloud and the responsibilities that customers have in the AWS cloud.**
	- The model used to define only the responsibilities that AWS has of the cloud.
	- The model used to define only the responsibilities that customers have in the AWS cloud.
	- None of these answers are correct.

- What is AWS Lambda?
	- Relational database service
	- Storage service
	- Compute service
	- DNS service

- Which of the following services is not allowed penetration testing without prior approval?
	- **Amazon S3**
	- Amazon Lightsail
	- Amazon EC2
	- Amazon RDS

- In regards to AWS KMS, which of these statements are true? (Choose 3)
	- **Keys can be generated in a CloudHSM cluster.**
	- AWS KMS does not integrate with any other AWS services.
	- AWS KMS is integrated with S3 for the purpose of logging AWS KMS keys use.
	- **Keys may be imported from other encryption key services.**
	- **Keys may be generated in KMS.**