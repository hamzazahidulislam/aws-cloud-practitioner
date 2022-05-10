<!-- @format -->

# AWS Cloud Practitioner (_CLF-C01_)

## list of AWS Cloud Resources

- ec2 ami

- ec2 image builder

- ec2 ebs volume snapshot

- ec2 volume termination default enable

- ec2 intance storage

- efs-ai is very cheap add lifecycle

- fsx windos file system

- fsx or lustre for high perfomance HPC

- alb application load balancer with ec2

- ec2 asg with alb

- s3 replication (CRR & SRR)

- s3 intelligent tiering

- s3 object lock

- storage gateway

- rds and elastic cache

- DynamoDB, Redshift, EMR, Athena, QuickSight, DocumentDB, Neptune, QLDB, DMS, GLUE

- Docker, ECR, ECS, Lambda, api gateway, batch, lightsail
- cloudformation,cdk,codedeploy,codecommit,codebuild,codepipeline,codeArtifact,codestar,cloud9,ssm,opswork

- route53={simple routing plicy, weighted routing poilcy, latency routing policy, failover rotuing policy},

- cloudfront, s3 transfer acceleration, aws global acceleratior, aws outputs, aws wavelength
  sqs, sns, kinesis, amazong mq

- cloudwatch, cloudwatchalarm, cloudwatchlog, events, eventsbridge, cloudtrail, cloudtrailinsights, aws xray, code guru

- vpc, subnet, internet gateway, security group , NACL, VPC Flow Logs, direct connnection & site site to VPN(CGW&VGW), transit gateway

- ddos waf and shield, KMS & CloudHSM, ACM, Artifact, GurdDuty, inspector, config, macie, security hub, detective, aws abuse, root user privileges

- rekognition, transcribe, polly, translation, lex and connect, Amazong comprehend NLP, sage maker, forecast, knedra, personalaize

- aws organizations, control tower, priceing model, saving plan, aws cost optimizer, billing and cost tools, TCO, cost allocation tags, cost and usage reports, cost explorer, aws budgets, trusted advisor, support plans pricing

- STS, Cognito, directory service , single sign-on, advance identity

- WorkSpaces(DaaS), AppStream 2.0, Sumerian(VR), (AR), 3D, IOT core, Elastic Transcoder, Device Farm, AWS Backup,
  Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization, aws well-architected Tool

## short list AWS Cloud Resources

- aws shared responsibilty model == aws responsibility for the security of the cloud, your responsible in the cloud
- cloud watch three destination == SNS, AUTO Scaling group, ec2 action

- pilot light warm stadndby\*

- consolidated billing on AWS

- According to AWS, what is the benefit of Elasticity?

- forecast your AWS spending

- aws waf

- APN Consulting Partner

- Weighted routing policy

- Failover routing policy

- Which of the following AWS Support plans provides access to online training with self-paced labs?

- out of public= aws direct connect,public= sitetositevpn, hybride=storagegateway

- aws artifact

### Key Features of AWS Organizations

- You may see use-cases asking you to select one of CloudWatch vs CloudTrail vs Config. **_Just remember_** _this thumb rule_

  - Think resource performance monitoring, events, and alerts and logs; think CloudWatch.

  - Think account-specific activity and audit; think CloudTrail.
  - Think resource-specific change history, audit, and compliance; think Config.

- coludtraillog default encryption enabled and automaticly encryption enable aws storage gateway and s3 glacier

- ### **Elasticity**: _(The ability to acquire resources as you need and release when they are no longer needed is termed as Elasticity of the Cloud. With cloud computing)_

- ### **Reliability** - _Refers to the ability of a system to recover from infrastructure or service disruptions, by dynamically acquiring computing resources to meet demand, and mitigate disruptions._

- ### **Durability** - _Refers to the ability of a system to assure data is stored and data remains consistently on the system as long as it is not changed by legitimate access,_

- ### **Resiliency** - _Describes the ability of a system to recover from a failure induced by the load (data or network), attacks, and failures (hardware, software, or network failures)._

- ### **Agility** - _Agility refers to the ability of the cloud to give you easy access to a broad range of technologies so that you can innovate faster and build nearly anything that you can imagine_

- ### **Cost savings** - _The cloud allows you to trade capital expenses (such as data centers and physical servers) for variable expenses, and only pay for IT as you consume it._

- ### **Ability to deploy globally in minutes** - _With the cloud, you can expand to new geographic regions and deploy globally in minutes_

- SQL injection and cross-site scripting == WAF

- ### **Recovery time objective (RTO)**: _The maximum acceptable delay between the interruption of service and restoration of service. This determines an acceptable length of time for service downtime._

- ### **Recovery point objective (RPO)**: _The maximum acceptable amount of time since the last data recovery point._

- #### **_GuardDuty is a threat detection service that monitors malicious activity and unauthorized behavior to protect your AWS account. GuardDuty analyzes billions of events across your AWS accounts from AWS CloudTrail (AWS user and API activity in your accounts)_**

- #### **_AWS Global Accelerator and Amazon CloudFront are separate services that use the AWS global network and its edge locations around the world. CloudFront improves performance for both cacheable content (such as images and videos) and dynamic content (such as API acceleration and dynamic site delivery). Global Accelerator improves performance for a wide range of applications over TCP or UDP by proxying packets at the edge to applications running in one or more AWS Regions_**

- Hadoop=EMR

# Exam Alerts

- #### _Exam Alert_: **AWS Step Functions VS AWS Batch**

  You can use AWS Batch to plan, schedule and execute your batch computing workloads across the full range of AWS compute services. AWS Batch dynamically provisions the optimal quantity and type of compute resources (e.g., CPU or memory optimized instances) based on the volume and specific resource requirements of the batch jobs submitted.
  You cannot use Step Functions to plan, schedule and execute your batch computing workloads by provisioning underlying resources.
  step funtion handle microservices

- #### Exam Alert:

  **Amazon S3 is a unique service in the sense that it follows a global namespace but the buckets are regional.
  AWS Acceptable Use Policy**

- #### Exam Alert:

  **Watch out for questions on AWS Cost Explorer vs AWS Budgets. AWS Budgets can alert you when your costs exceed your budgeted amount. Cost Explorer helps you visualize and manage your AWS costs and usage over time.**

- Amazon Comprehend language processing

- cloudfont and iam global services

- AWS Outposts

- AWS Wavelength == 5G
- Amazon GuardDuty is a threat detection service that continuously monitors your AWS accounts and workloads. While AWS Resource Access Manager is used to securely share your resources across your AWS accounts.

- AWS OpsWorks == aoutumate server configuration

- Amazon FSx for Lustre == linux

- Amazon FSx for Windows File Server

- Tape Gateway, File Gateway and Volume Gateway

- Hybrid deployment

- Amazon Athena

- The services that are part of foundations are: Amazon VPC, AWS Trusted Advisor, AWS Service Quotas (earlier known as AWS Service Limits).
- Amazon Kendra

- Amazon Comprehend

- #### Exam Alert:

  **You may see a question around this concept in the exam. Just remember that only S3 and DynamoDB support VPC Endpoint Gateway. All other services that support VPC Endpoints use a VPC Endpoint Interface.**

- AWS Transit Gateway

- Amazon Macie == s3

- Amazon GuardDuty

- Use CloudWatch Logs for both the EC2 instance and the on-premises servers

- large volumes== snowball

- AWS Cost and Usage Reports == export bill and break down

- wellarchitecture and pain support review

- Storing files in an accessible location to satisfy audit requirements - The Standard–IA storage class reduces storage costs for files that are not accessed every day.

- JSON == Effect,action

- Rekognition == Identify objects in a photo

- #### Exam Alert:

  **Please review the differences between:** "**AWS Cost and Usage Reports" and "AWS Cost Explorer**". Think of "AWS Cost and Usage Reports" as a cost management tool providing the most detailed cost and usage data for your AWS account. It can provide reports that break down your costs by the hour into your S3 bucket. On the other hand, "AWS Cost Explorer" is more of a high-level cost management tool that helps you visualize the costs and usage associated with your AWS account.
  Read Replica improves database scalability

- #### Exam Alert:

  **Please review the differences between Multi-AZ, Multi-Region and Read Replica deployments for RDS:
  High Availability by default? == EFS,DynamoDB
  Site-to-Site VPN == Virtual Private Gateway, Customer Gateway, transit gateway, customer gateway device
  Use Cross-Region replication (CRR) to replicate data between distant AWS Regions**

- #### Exam Alert:

  **Please review the differences between SRR and CRR.**

- AWS Budgets - Cost budget, Usage budget, Reservation budget and Savings Plans budget.

- Which AWS service can help you forecast your next AWS bill for the services you use? == AWS Cost Explorer

- s3 archival = s3 galicer

- centraly manage server = system manager

- on-premis and cloud monitor server = cloudwatch

- billing alaram = cloudwatch

- #### Exam Alert:

  **While the Service Health Dashboard displays the general status of AWS services, Personal Health Dashboard gives you a personalized view of the performance and availability of the AWS services underlying your AWS resources.**

- container service = faragte

- S3 is a key value based object storage service

- S3 stores data in a flat non-hierarchical structure

- trusted advisor = s3 buckets, colud trail user activity logs

- Which AWS Support plan provides general architectural guidance on how services can be used for various use-cases, workloads, or applications? developer = enterprise

- AWS Shield Standard = perview shared responsibility

- **\*You pay for all bandwidth into and out of Amazon S3**, except for the following: (1) Data transferred in from the internet, (2) Data transferred out to an Amazon Elastic Compute Cloud (Amazon EC2) instance, when the instance is in the same AWS Region as the S3 bucket, (3) Data transferred out to Amazon CloudFront (CloudFront).
  AWS Shield Advanced provides expanded DDoS attack protection for web applications running on the following resources: Amazon Elastic Compute Cloud, Elastic Load Balancing (ELB), Amazon CloudFront, Amazon Route 53, AWS Global Accelerator.\*

- VPC Interface Endpoint == SNS

- S3 Standard has no constraint of a minimum storage duration for objects.

- Infrastructure Event Management = enterprice

- AWS charges you for data transferred between two different Regions.

- #### 1. Agility

  **The cloud allows you to innovate faster because you can focus your valuable IT resources on developing applications that differentiate your business and transform customer
  elesticity
  Before cloud computing, you had to overprovision infrastructure to ensure you had enough capacity to handle your business operations at the peak level of activity.**

- #### The Well-Architected Framework has been developed to help cloud architects build secure, high-performing, resilient, and efficient infrastructure for their applications. This is based on six pillars namely:

  - 1. Operational Excellence

  - 2. Security

  - 3. Reliability

  - 4. Performance Efficiency

  - 5. Cost Optimization

  - 6. Sustainability

- Elasticity is the ability to acquire resources as you need them and release resources when you no longer need them. In the cloud, you want to do this automatically.
- Durability is incorrect since this characteristic concerns data durability than handling server load.

- Permitted Services – You're welcome to conduct security assessments against AWS resources that you own if they make use of the services listed below. Take note that AWS is constantly updating this list:

  - Amazon EC2 instances, NAT Gateways, and Elastic Load Balancers

  - Amazon RDS

  - Amazon CloudFront

  - Amazon Aurora

  - Amazon API Gateways

  - AWS Lambda and Lambda Edge functions

  - Amazon Lightsail resources

  - Amazon Elastic Beanstalk environments

- Prohibited Activities – The following activities are prohibited at this time:

  - DNS zone walking via Amazon Route 53 Hosted Zones

  - Denial of Service (DoS), Distributed Denial of Service (DDoS), Simulated DoS, Simulated DDoS

  - Port flooding

  - Protocol flooding

  - Request flooding (login request flooding, API request flooding)

- #### **Application Load Balancer** - This is best suited for load balancing of HTTP and HTTPS traffic and provides advanced request routing targeted at the delivery of modern application architectures, including microservices and containers. Operating at the individual request level (Layer 7), Application Load Balancer routes traffic to targets within Amazon Virtual Private Cloud (Amazon VPC) based on the content of the request.

- #### **Network Load Balancer** - This is best suited for load balancing of Transmission Control Protocol (TCP), User Datagram Protocol (UDP) and Transport Layer Security (TLS) traffic where extreme performance is required. Operating at the connection level (Layer 4), Network Load Balancer routes traffic to targets within Amazon Virtual Private Cloud (Amazon VPC) and is capable of handling millions of requests per second while maintaining ultra-low latencies. Network Load Balancer is also optimized to handle sudden and volatile traffic patterns.

- #### **Classic Load Balancer** - This provides basic load balancing across multiple Amazon EC2 instances and operates at both the request level and connection level. Classic Load Balancer is intended for applications that were built within the EC2-Classic network.

- #### **Gateway Load Balancer** - This provides both Layer 3 gateway and Layer 4 load balancing capabilities. It is a transparent bump-in-the-wire device that does not change any part of the packet. It is architected to handle millions of requests/second, volatile traffic patterns, and introduces extremely low latency.

- AWS Snowmobile is incorrect because this is primarily used to migrate tens of petabytes to exabytes of data in batches to the cloud.

- AWS Snowcone is incorrect. Although it is a data transport solution like Snowball Edge, it is not suitable for moving terabytes to petabytes of data. Take note that the usable storage for Snowcone is only 8 TB.
- AWS Snowball Edge = moving terabytes to petabytes of data

- APN Consulting Partners are professional services firms that help customers of all sizes design, architect, migrate, or build new applications on AWS. Consulting Partners include System Integrators (SIs), Strategic Consultancies, Resellers, Digital Agencies, Managed Service Providers (MSPs), and Value-Added Resellers (VARs).

- APN Technology Partners provide software solutions that are either hosted on, or integrated with, the AWS platform. Technology Partners include Independent Software Vendors (ISVs), SaaS, PaaS, developer tools, management and security vendors.

- Amazon Chime == google meet or zoom

- Amazon Connect == slak or discord

- serlverless = step function

- not serverless = aws batch

- Reserved Instance usage = AWS Billing Console

- lowest support plan that allows an unlimited number of technical support cases 1 primary contact = developer

- General Purpose SSD - Recommended for most workloads;

- Provisioned IOPS SSD - Meant for critical business applications that require sustained IOPS performance;

- Throughput Optimized HDD - Meant for streaming workloads requiring consistent,

- Cold HDD - Meant for throughput-oriented storage for large volumes of data that is infrequently accessed,

- consolited billing = such as Amazon EC2 and Amazon S3

- SOA = Decouple your components.

- host operating system of an Amazon EC2 instance? = aws

- serverless = lamda@edge, api gateway

- add more ec2 resource pool is a = horizontal scaling

- add more cpu is a = vertical scaling

- fully inherit from AWS = Physical and Environmental Controls

- ci+cd = AWS CodeStar

- WAF protection layer 7

- AWS shield 🛡️ layer 3/4

- Amazon Macie for secure you data or protect PII.

- AWS glue

- AWS service catalog

- AWS APN partner

- Latency routing policy

- Failover routing policy - This routing policy is used when you want to configure active-passive failover.

- Weighted routing policy - This routing policy is used to route traffic to multiple resources in proportions that you specify.

- Simple routing policy - With simple routing, you typically route traffic to a single resource, for example, to a web server for your website.

- #### Artifact :

  **AWS Artifact is your central resource for compliance-related information on AWS Cloud. It provides on-demand access to AWS’ security and compliance reports and select online agreements.**

- AWS rekognition (SaaS)

- Well-Architected Framework:

- operational excellence, security, reliability, performance efficiency, and cost optimization

- S3 standard

- S3 Intelligent- Tiering\*

- S3 Standard-IA

- S3 One Zone-IAt : (S3 One Zone-IA stores data in a single AZ and costs 20% less than S3 Standard-IA)

- S3 Glacier

- S3 Glacier Deep Archive

- Amazon MQ

- Kines data stream service

- **Important**: Multi-AZ deployments are not a read scaling solution, you cannot use a standby replica to serve read traffic. The standby is only there for failover.

- Amazon RDS Multi-AZ deployments provide enhanced availability and durability for RDS database (DB) instances.
- Amazon RDS Multi-AZ deployments provide enhanced availability for database instances within a single AWS Region. With Multi-AZ, your data is synchronously replicated to a standby instance in a different AZ.

- You need to use RDS in Multi-Region deployment configuration to protect from a regional failure. Multi-AZ cannot protect from a regional failure.
- AWS Developer Support plan allows one primary contact to open unlimited cases.
- A VPC spans all of the Availability Zones in the Region whereas a subnet spans only one Availability Zone in the Region

- Compute optimizer

- Ec2 instance,ec2 auto scaling group

- EBS volume, AWS lambda function

- CloudHSM hardware security

- AWS inspector for application assesses, vulnerable and deviations

- **S3 Transfer Acceleration** : Amazon S3 Transfer Acceleration (S3TA) enables fast, easy, and secure transfers of files over long distances between your client and your Amazon S3 bucket

**Route 53 key features are:**

- Resolver - get recursive DNS for your Amazon VPC and on-premises networks.

- Traffic flow - route end users to the best endpoint for your application based on geoproximity, latency, health, and other considerations.

- Latency-based routing - route end users to the AWS region that provides the lowest possible latency.

- Geo DNS - route end users to a particular endpoint that you specify based on the end user’s geographic location.

- Private DNS for Amazon VPC - Manage custom domain names for your internal AWS resources without exposing DNS data to the public Internet.

- DNS Failover - automatically route your website visitors to an alternate location to avoid site outages.

- Health Checks and Monitoring - monitor your application's health and performance, as well as your web servers and other resources.

- Domain Registration - search for and register available domain names or transfer in existing domain names.

**_Hence, the correct answers are:_**

- DNS Resolution

- Domain Registration
