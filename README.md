Absolutely buddy. Since we're at the **final revision stage**, don't revise AWS randomly. Use this as your **SAA-C03 master checklist**.

I’m keeping it at **SAA level**, not Solutions Architect Professional / deep DevOps level.

# AWS SAA-C03 — Final Revision Checklist

## 1. 🌐 Networking & Content Delivery

### VPC ⭐⭐⭐

* [ ] VPC, CIDR, IPv4
* [ ] Public vs Private subnet
* [ ] Route tables
* [ ] Internet Gateway (IGW)
* [ ] NAT Gateway
* [ ] NAT Gateway vs NAT Instance
* [ ] Security Groups
* [ ] Network ACLs
* [ ] SG vs NACL
* [ ] Elastic IP
* [ ] VPC endpoints

  * [ ] Gateway Endpoint — S3/DynamoDB
  * [ ] Interface Endpoint — PrivateLink
* [ ] VPC Peering
* [ ] Transit Gateway
* [ ] VPC sharing
* [ ] DNS in VPC
* [ ] DHCP options — basic understanding
* [ ] Bastion Host — use case
* [ ] Network connectivity scenarios

### Elastic Load Balancing ⭐⭐⭐

* [ ] ALB
* [ ] NLB
* [ ] Gateway Load Balancer — basic use case
* [ ] Target Groups
* [ ] Health Checks
* [ ] Listener / Listener Rules
* [ ] Path-based routing
* [ ] Host-based routing
* [ ] Cross-zone load balancing
* [ ] ALB vs NLB scenarios

### Route 53 ⭐⭐⭐

* [ ] Hosted Zones
* [ ] Public vs Private Hosted Zone
* [ ] Record types

  * [ ] A
  * [ ] AAAA
  * [ ] CNAME
  * [ ] Alias
* [ ] Routing policies

  * [ ] Simple
  * [ ] Weighted
  * [ ] Latency
  * [ ] Failover
  * [ ] Geolocation
  * [ ] Geoproximity — basic
  * [ ] Multivalue Answer
* [ ] Health Checks
* [ ] DNS failover

### CloudFront ⭐⭐⭐

* [ ] CDN concept
* [ ] Edge Locations
* [ ] Distribution
* [ ] Origin
* [ ] Cache behavior
* [ ] TTL
* [ ] Cache invalidation
* [ ] Origin Access Control (OAC)
* [ ] CloudFront + S3
* [ ] CloudFront + ALB
* [ ] CloudFront vs S3 Transfer Acceleration
* [ ] HTTPS / certificates — basic

### Global Accelerator

* [ ] Anycast IP
* [ ] Static IP
* [ ] AWS global network
* [ ] Health checks
* [ ] Global Accelerator vs CloudFront

---

# 2. 🖥️ Compute

### EC2 ⭐⭐⭐

* [ ] Instance types

  * [ ] General Purpose
  * [ ] Compute Optimized
  * [ ] Memory Optimized
  * [ ] Storage Optimized
  * [ ] Accelerated Computing
* [ ] AMI
* [ ] User Data
* [ ] Metadata
* [ ] Instance lifecycle
* [ ] Reboot vs Stop vs Terminate
* [ ] Placement Groups

  * [ ] Cluster
  * [ ] Spread
  * [ ] Partition
* [ ] Dedicated Host / Dedicated Instance — basic
* [ ] On-Demand
* [ ] Reserved Instances
* [ ] Savings Plans
* [ ] Spot Instances
* [ ] Spot interruption
* [ ] EC2 pricing scenarios
* [ ] Elastic IP

### Auto Scaling ⭐⭐⭐

* [ ] Launch Template
* [ ] Auto Scaling Group
* [ ] Minimum / Desired / Maximum
* [ ] Scaling policies

  * [ ] Target Tracking
  * [ ] Step Scaling
  * [ ] Simple Scaling — basic
* [ ] Scheduled Scaling
* [ ] Dynamic Scaling
* [ ] Health Checks
* [ ] Multi-AZ Auto Scaling
* [ ] ASG + ALB

### Lambda ⭐⭐⭐

* [ ] Serverless concept
* [ ] Invocation models
* [ ] Event-driven architecture
* [ ] Execution role
* [ ] Timeout
* [ ] Memory
* [ ] Concurrency
* [ ] Reserved concurrency
* [ ] Versions
* [ ] Aliases
* [ ] Layers — basic
* [ ] Lambda + API Gateway
* [ ] Lambda + S3
* [ ] Lambda + EventBridge
* [ ] Lambda + SQS
* [ ] Lambda pricing/use cases

### Containers

* [ ] ECS
* [ ] ECS Cluster
* [ ] Task Definition
* [ ] ECS Service
* [ ] ECS on EC2
* [ ] ECS Fargate
* [ ] EKS — basic architecture/use cases
* [ ] Fargate vs EC2
* [ ] ECR
* [ ] Containers + Load Balancer

---

# 3. 💾 Storage

## S3 ⭐⭐⭐

* [ ] Bucket / Object
* [ ] Storage classes

  * [ ] Standard
  * [ ] Intelligent-Tiering
  * [ ] Standard-IA
  * [ ] One Zone-IA
  * [ ] Glacier Instant Retrieval
  * [ ] Glacier Flexible Retrieval
  * [ ] Glacier Deep Archive
* [ ] Versioning
* [ ] Lifecycle Rules
* [ ] Replication

  * [ ] SRR
  * [ ] CRR
* [ ] Encryption

  * [ ] SSE-S3
  * [ ] SSE-KMS
  * [ ] SSE-C — basic
* [ ] Bucket Policies
* [ ] IAM policies
* [ ] Block Public Access
* [ ] Object Lock
* [ ] Pre-signed URLs
* [ ] Static website hosting — basic
* [ ] Multipart Upload
* [ ] S3 Transfer Acceleration
* [ ] Event Notifications
* [ ] S3 + CloudFront
* [ ] S3 consistency
* [ ] S3 security scenarios

## EBS ⭐⭐⭐

* [ ] Volume types

  * [ ] gp3
  * [ ] io2
  * [ ] st1
  * [ ] sc1
* [ ] EBS vs Instance Store
* [ ] Snapshots
* [ ] Incremental snapshots
* [ ] Encryption
* [ ] Snapshot copy
* [ ] Delete on termination
* [ ] EBS Multi-Attach — basic
* [ ] EBS AZ limitation

## EFS

* [ ] Shared file system
* [ ] Multi-AZ
* [ ] Linux workloads
* [ ] Performance modes
* [ ] Throughput modes
* [ ] EFS vs EBS
* [ ] EFS vs FSx

## FSx ⭐⭐

* [ ] FSx for Windows File Server
* [ ] FSx for Lustre
* [ ] FSx for NetApp ONTAP — basic
* [ ] FSx for OpenZFS — basic
* [ ] FSx vs EFS vs EBS scenarios

## Storage Gateway ⭐⭐

* [ ] File Gateway
* [ ] Volume Gateway
* [ ] Tape Gateway
* [ ] On-premises ↔ AWS architecture
* [ ] Cache concept
* [ ] Storage Gateway use cases

---

# 4. 🗄️ Databases

## RDS ⭐⭐⭐

* [ ] RDS architecture
* [ ] Supported relational engines — basic
* [ ] Multi-AZ
* [ ] Read Replicas
* [ ] Automated backups
* [ ] Manual snapshots
* [ ] Point-in-time recovery
* [ ] Encryption
* [ ] RDS Proxy — basic
* [ ] Multi-AZ vs Read Replica
* [ ] Scaling scenarios

## Aurora ⭐⭐⭐

* [ ] Aurora architecture
* [ ] Writer / Reader
* [ ] Aurora Replicas
* [ ] Reader Endpoint
* [ ] Writer Endpoint
* [ ] Failover
* [ ] Aurora Serverless
* [ ] Aurora Global Database
* [ ] Aurora vs RDS

## DynamoDB ⭐⭐⭐

* [ ] NoSQL concept
* [ ] Table / Item / Attribute
* [ ] Partition Key
* [ ] Composite Primary Key
* [ ] Sort Key
* [ ] Query vs Scan
* [ ] GSI
* [ ] LSI — basic
* [ ] DynamoDB Streams
* [ ] On-Demand vs Provisioned
* [ ] Global Tables
* [ ] TTL
* [ ] DAX — basic
* [ ] DynamoDB use-case selection

## ElastiCache ⭐⭐

* [ ] Redis
* [ ] Memcached
* [ ] Caching concept
* [ ] Session storage
* [ ] Redis vs Memcached
* [ ] ElastiCache vs DynamoDB

---

# 5. 🔐 Security, Identity & Access

## IAM ⭐⭐⭐

* [ ] IAM Users
* [ ] Groups
* [ ] Roles
* [ ] Policies
* [ ] Identity-based policies
* [ ] Resource-based policies
* [ ] Explicit Deny
* [ ] Permission boundaries
* [ ] IAM policy evaluation
* [ ] MFA
* [ ] Least privilege
* [ ] Access Keys

## STS ⭐⭐

* [ ] AssumeRole
* [ ] Temporary credentials
* [ ] Cross-account access
* [ ] Role assumption

## KMS ⭐⭐⭐

* [ ] Customer Managed Key
* [ ] AWS Managed Key
* [ ] Encryption / Decryption
* [ ] Envelope encryption — concept
* [ ] Key policies
* [ ] KMS + S3
* [ ] KMS + EBS
* [ ] KMS + RDS
* [ ] KMS permissions

## AWS Organizations

* [ ] Management Account
* [ ] Member Accounts
* [ ] Organizational Units
* [ ] SCPs
* [ ] SCP vs IAM policy
* [ ] Consolidated billing
* [ ] Cross-account architecture

## Other Security Services

* [ ] AWS WAF
* [ ] AWS Shield
* [ ] AWS Firewall Manager — basic
* [ ] GuardDuty
* [ ] Inspector
* [ ] Macie
* [ ] Secrets Manager
* [ ] Systems Manager Parameter Store
* [ ] Cognito — basic use cases
* [ ] Security Hub — basic

---

# 6. 📊 Monitoring & Management ⭐⭐⭐

This is one of your **recently covered areas**, so make sure you revise the service-selection scenarios.

### CloudWatch

* [ ] Metrics
* [ ] Logs
* [ ] Alarms
* [ ] Dashboards
* [ ] Logs Insights — basic
* [ ] CloudWatch Agent
* [ ] Custom Metrics
* [ ] EventBridge relationship
* [ ] CloudWatch Alarm → Auto Scaling
* [ ] CloudWatch Alarm → SNS

### CloudTrail

* [ ] API activity
* [ ] Management Events
* [ ] Data Events — basic
* [ ] Audit / compliance
* [ ] CloudTrail vs CloudWatch

### AWS Config

* [ ] Configuration history
* [ ] Configuration rules
* [ ] Compliance
* [ ] Resource configuration tracking
* [ ] Config vs CloudTrail

### Systems Manager

* [ ] Session Manager
* [ ] Parameter Store
* [ ] Patch Manager — basic
* [ ] Run Command — basic
* [ ] Automation — basic

### Trusted Advisor

* [ ] Cost
* [ ] Performance
* [ ] Security
* [ ] Fault tolerance
* [ ] Service limits

---

# 7. 🔄 Application Integration

## SQS ⭐⭐⭐

* [ ] Queue
* [ ] Standard Queue
* [ ] FIFO Queue
* [ ] Visibility Timeout
* [ ] Long Polling
* [ ] Dead Letter Queue
* [ ] Message retention
* [ ] Delay Queue
* [ ] SQS + Lambda
* [ ] Decoupling

## SNS ⭐⭐⭐

* [ ] Topic
* [ ] Publishers
* [ ] Subscribers
* [ ] Fan-out
* [ ] SNS → SQS
* [ ] SNS → Lambda
* [ ] SNS → Email
* [ ] SNS vs SQS

## EventBridge ⭐⭐⭐

* [ ] Event bus
* [ ] Rules
* [ ] Event patterns
* [ ] Targets
* [ ] Scheduled events
* [ ] AWS service events
* [ ] EventBridge vs SNS
* [ ] EventBridge vs SQS

## Step Functions

* [ ] Workflow orchestration
* [ ] State machine
* [ ] Sequential workflows
* [ ] Retry / Catch
* [ ] Lambda orchestration
* [ ] Step Functions vs SQS/EventBridge

---

# 8. 🚚 Migration & Transfer

This is **important for your final revision** because we just started it.

### Migration Services

* [ ] AWS Migration Hub
* [ ] Application Migration Service (MGN)
* [ ] Database Migration Service (DMS)
* [ ] Schema Conversion Tool (SCT)
* [ ] Migration Evaluator — basic

### Transfer Services

* [ ] AWS DataSync
* [ ] AWS Transfer Family

  * [ ] SFTP
  * [ ] FTPS
  * [ ] FTP
* [ ] Snow Family

  * [ ] Snowcone
  * [ ] Snowball Edge
  * [ ] Snowmobile — concept

### Connectivity

* [ ] Storage Gateway
* [ ] Direct Connect
* [ ] VPN
* [ ] Site-to-Site VPN
* [ ] Direct Connect vs VPN
* [ ] Hybrid cloud scenarios

### Migration scenario selection ⭐⭐⭐

* [ ] Online vs offline migration
* [ ] Large dataset
* [ ] Limited network bandwidth
* [ ] Database migration
* [ ] Server migration
* [ ] File transfer
* [ ] Continuous replication

---

# 9. 🚀 Deployment & Infrastructure

### CloudFormation

* [ ] Template
* [ ] Stack
* [ ] Parameters
* [ ] Outputs
* [ ] Resources
* [ ] Nested stacks — basic
* [ ] Infrastructure as Code concept

### Elastic Beanstalk

* [ ] Application
* [ ] Environment
* [ ] Managed deployment
* [ ] Scaling
* [ ] Beanstalk vs EC2

### Code Services — SAA Level

* [ ] CodeCommit — basic awareness
* [ ] CodeBuild
* [ ] CodeDeploy
* [ ] CodePipeline
* [ ] CI/CD concept
* [ ] Blue/Green deployment
* [ ] Rolling deployment
* [ ] Canary deployment — basic

---

# 10. 🏗️ Architecture & Reliability ⭐⭐⭐

This is where SAA questions really combine multiple services.

* [ ] High Availability
* [ ] Fault Tolerance
* [ ] Scalability
* [ ] Elasticity
* [ ] Multi-AZ
* [ ] Multi-Region
* [ ] Stateless architecture
* [ ] Decoupled architecture
* [ ] Horizontal vs Vertical scaling
* [ ] Disaster Recovery

  * [ ] Backup & Restore
  * [ ] Pilot Light
  * [ ] Warm Standby
  * [ ] Multi-Site / Active-Active
* [ ] RTO
* [ ] RPO
* [ ] AWS Well-Architected Framework

  * [ ] Operational Excellence
  * [ ] Security
  * [ ] Reliability
  * [ ] Performance Efficiency
  * [ ] Cost Optimization
  * [ ] Sustainability

---

# 11. 💰 Cost Optimization ⭐⭐

* [ ] AWS Pricing Calculator
* [ ] Cost Explorer
* [ ] AWS Budgets
* [ ] Cost Allocation Tags
* [ ] Reserved Instances
* [ ] Savings Plans
* [ ] Spot Instances
* [ ] S3 storage classes
* [ ] Lifecycle policies
* [ ] Right-sizing
* [ ] Serverless cost benefits
* [ ] NAT Gateway cost awareness
* [ ] Data transfer costs — basic

---

# 12. ⚡ Important "Comparison Pairs"

**These are extremely worth revising before the exam.**

* [ ] ALB vs NLB
* [ ] Security Group vs NACL
* [ ] NAT Gateway vs VPC Endpoint
* [ ] VPC Peering vs Transit Gateway
* [ ] CloudFront vs Global Accelerator
* [ ] CloudFront vs S3 Transfer Acceleration
* [ ] EBS vs EFS vs FSx
* [ ] EBS vs Instance Store
* [ ] S3 vs EBS
* [ ] RDS Multi-AZ vs Read Replica
* [ ] RDS vs Aurora
* [ ] Aurora vs DynamoDB
* [ ] Redis vs Memcached
* [ ] SQS vs SNS
* [ ] SNS vs EventBridge
* [ ] EventBridge vs CloudWatch Events
* [ ] Lambda vs ECS/Fargate
* [ ] ECS vs EKS
* [ ] EC2 vs Lambda
* [ ] VPN vs Direct Connect
* [ ] DataSync vs Storage Gateway
* [ ] DMS vs DataSync
* [ ] MGN vs DMS
* [ ] IAM Role vs IAM User
* [ ] IAM Policy vs SCP
* [ ] Secrets Manager vs Parameter Store
* [ ] CloudWatch vs CloudTrail vs Config
* [ ] WAF vs Shield vs GuardDuty
* [ ] Backup & Restore vs Pilot Light vs Warm Standby

---

# 🎯 Final SAA Revision Priority

If you're short on time, revise in this order:

### 🔴 Tier 1 — MUST KNOW

1. VPC
2. IAM
3. EC2
4. S3
5. RDS/Aurora
6. ELB + ASG
7. Route 53
8. CloudFront
9. Lambda
10. SQS/SNS/EventBridge
11. Security
12. HA / DR / Reliability

### 🟠 Tier 2 — VERY IMPORTANT

13. DynamoDB
14. EBS/EFS/FSx
15. ElastiCache
16. CloudWatch/CloudTrail/Config
17. VPC Endpoints / Peering / Transit Gateway
18. KMS
19. Organizations/SCP
20. Migration & Transfer
21. Storage Gateway
22. Direct Connect/VPN

### 🟡 Tier 3 — KNOW THE USE CASE

23. ECS/Fargate/EKS
24. Step Functions
25. Systems Manager
26. WAF/Shield/GuardDuty/Inspector/Macie
27. CloudFormation
28. Elastic Beanstalk
29. CodePipeline/CodeBuild/CodeDeploy
30. Trusted Advisor
31. Cost Optimization services

---

## 🧠 The final exam skill

Don't revise these as **"What is X?"**

Revise as:

> **"Given this requirement, WHY would I choose X instead of Y?"**

For example:

**Private EC2 needs S3 without traversing the internet**

→ VPC **Gateway Endpoint**

**Global users need lower-latency static content**

→ **CloudFront**

**Global TCP application needs static IPs and fast failover**

→ **Global Accelerator**

**On-prem database → AWS with continuous replication**

→ **DMS**

**On-prem files → AWS over network**

→ **DataSync**

**On-prem application wants cloud-backed file storage**

→ **Storage Gateway**

**Relational DB needs HA**

→ **RDS Multi-AZ**

**Relational DB needs read scaling**

→ **Read Replica**

**Decouple producer and consumer**

→ **SQS**

**One event → many consumers**

→ **SNS/EventBridge**

That **service-selection mindset** is what I want you to focus on in the final revision.

And based on our journey, you've already covered a large portion of this list. The remaining work should be **gap-filling + comparison revision + mixed SAA scenario questions**, rather than learning everything again from scratch.
