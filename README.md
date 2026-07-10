AWS Cybersecurity Hands-On Project Roadmap
If You currently have around $171 in AWS credits and about 100 days remaining in the free tier. That is enough time to build several strong cybersecurity-focused cloud projects without overspending if you stay within small instance sizes and clean up resources regularly.
This roadmap is designed for:
•	Beginners to intermediate cloud/security learners
•	Hands-on learning
•	Resume-ready projects
•	Daily industry-used AWS services
•	Low-cost architecture
•	Practical SOC, DevSecOps, and cloud security exposure
The schedule is designed for:
•	3 projects per week
•	Around 2 to 4 hours per project
•	12-week roadmap

________________________________________
Important NOTE:
1.	Take screenshots of every project.
2.	Keep all Terraform/YAML/commands in GitHub.
3.	Focus more on security concepts than just clicking in AWS.
4.	Always explain why a service is used.
5.	Learn troubleshooting while building.
6.	Practice explaining architecture verbally.
7.	Track your AWS billing every day.
8.	Clean resources immediately after practice.
Important AWS Services You Will Use Frequently
These are heavily used in real cybersecurity and cloud environments:
Service	Purpose
EC2	Virtual servers
IAM	Identity and access management
VPC	Networking and isolation
Security Groups	Firewall rules
CloudTrail	Audit logging
CloudWatch	Monitoring and alerts
S3	Secure object storage
GuardDuty	Threat detection
AWS Config	Compliance monitoring
WAF	Web application firewall
Route 53	DNS management
Lambda	Serverless automation
SNS	Alert notifications
Inspector	Vulnerability scanning
Secrets Manager	Secret storage
Systems Manager (SSM)	Secure server management
KMS	Encryption management
ECR	Container registry
ECS/EKS	Container orchestration
________________________________________
Cost Control Rules
Before starting:
1.	Use t2.micro or t3.micro instances whenever possible.
2.	Stop EC2 instances when not in use.
3.	Delete unused EBS volumes and snapshots.
4.	Use only one region.
5.	Avoid NAT Gateway unless required.
6.	Set billing alarms immediately.
7.	Delete load balancers after practice.
8.	Keep GuardDuty enabled only during labs.
9.	Use free-tier eligible databases.
10.	Monitor Billing Dashboard daily.
________________________________________







Week 1: AWS Security Foundations
Project 1: IAM Secure Environment Setup
Goal
Learn IAM users, groups, policies, MFA, and least privilege.
Services Used
•	IAM
•	CloudTrail
Tasks
•	Create admin and read-only users
•	Enable MFA
•	Create custom policies
•	Use IAM roles instead of access keys
•	Enable CloudTrail logging
Concepts Learned
•	RBAC
•	Principle of least privilege
•	Account auditing
•	Identity security
Time Required
2 to 3 hours
Resume Value
Strong beginner AWS security foundation.
________________________________________








Project 2: Build Secure VPC Architecture
Goal
Create isolated public and private subnets.
Services Used
•	VPC
•	EC2
•	Security Groups
•	NACLs
Tasks
•	Create VPC manually
•	Create public/private subnet
•	Attach internet gateway
•	Configure route tables
•	Restrict SSH access
Concepts Learned
•	Network segmentation
•	Cloud firewalling
•	Secure architecture
Time Required
3 hours
________________________________________
Project 3: Billing Alarm and Security Monitoring
Goal
Avoid accidental AWS charges.
Services Used
•	CloudWatch
•	SNS
•	Billing Dashboard
Tasks
•	Create billing alerts at $5 and $10
•	Send SNS email notifications
•	Create CPU utilization alarms
Concepts Learned
•	Monitoring
•	Alerting
•	Cost governance
Time Required
1.5 hours
________________________________________
Week 2: Logging and Threat Detection
Project 4: Centralized CloudTrail Logging
Goal
Store and analyze API activity logs.
Services Used
•	CloudTrail
•	S3
•	IAM
Tasks
•	Create S3 bucket for logs
•	Enable multi-region trail
•	Analyze login events
•	Detect failed API calls
Concepts Learned
•	Audit trails
•	Security visibility
•	Compliance logging
Time Required
2 hours
________________________________________
Project 5: Enable GuardDuty Threat Detection
Goal
Use AWS-native threat detection.
Services Used
•	GuardDuty
•	CloudTrail
•	VPC Flow Logs
•	DNS logs
Tasks
•	Enable GuardDuty
•	Generate sample findings
•	Investigate suspicious activity
Concepts Learned
•	Managed detection
•	Threat intelligence
•	Incident analysis
Time Required
2 hours
________________________________________
Project 6: CloudWatch Security Dashboard
Goal
Create a monitoring dashboard.
Services Used
•	CloudWatch
•	SNS
•	EC2
Tasks
•	Create custom dashboard
•	Monitor CPU, network traffic
•	Configure anomaly alerts
Concepts Learned
•	SIEM-style monitoring
•	Metrics visualization
•	Alert automation
Time Required
2 hours
________________________________________
Week 3: Secure Linux Server Projects
Project 7: Harden an EC2 Linux Server
Goal
Secure Linux in AWS.
Services Used
•	EC2
•	IAM
•	Security Groups
•	SSM
Tasks
•	Disable password login
•	Use SSH keys
•	Configure fail2ban
•	Restrict ports
•	Use Systems Manager Session Manager
Concepts Learned
•	Linux hardening
•	Secure remote access
•	SSH security
Time Required
3 to 4 hours
________________________________________
Project 8: Deploy a Honeypot Server
Goal
Capture suspicious traffic.
Services Used
•	EC2
•	CloudWatch
•	Security Groups
Tasks
•	Deploy Cowrie SSH honeypot
•	Monitor attacker attempts
•	Analyze logs
Concepts Learned
•	Threat intelligence
•	Attack behavior
•	Log analysis
Time Required
3 hours
________________________________________
Project 9: Vulnerability Scanning with Inspector
Goal
Scan EC2 instances for vulnerabilities.
Services Used
•	Amazon Inspector
•	EC2
Tasks
•	Enable Inspector
•	Scan instance packages
•	Review CVE findings
Concepts Learned
•	Vulnerability management
•	CVE analysis
•	Patch management
Time Required
2 hours
________________________________________
Week 4: S3 and Data Security
Project 10: Secure S3 Bucket Architecture
Goal
Prevent public bucket exposure.
Services Used
•	S3
•	IAM
•	Bucket Policies
•	KMS
Tasks
•	Create private bucket
•	Enable encryption
•	Enable versioning
•	Configure lifecycle policies
Concepts Learned
•	Data protection
•	Encryption
•	Secure storage
Time Required
2 hours
________________________________________
Project 11: Detect Public S3 Exposure
Goal
Automatically identify insecure buckets.
Services Used
•	Lambda
•	S3
•	SNS
•	IAM
Tasks
•	Create Lambda function
•	Detect public buckets
•	Send SNS alert
Concepts Learned
•	Security automation
•	Serverless detection
•	Event-driven security
Time Required
3 hours
________________________________________
Project 12: Encrypt Everything with KMS
Goal
Use encryption across AWS services.
Services Used
•	KMS
•	S3
•	EBS
Tasks
•	Create KMS keys
•	Encrypt EBS volume
•	Encrypt S3 bucket
Concepts Learned
•	Encryption at rest
•	Key management
•	Secure storage design
Time Required
2 hours
________________________________________
Week 5: Web Security Projects
Project 13: Deploy Secure Web App
Goal
Host a basic secure application.
Services Used
•	EC2
•	Security Groups
•	Route 53
Tasks
•	Install Nginx
•	Configure HTTPS
•	Restrict inbound traffic
Concepts Learned
•	Secure hosting
•	TLS basics
•	Reverse proxy setup
Time Required
3 hours
________________________________________
Project 14: AWS WAF Protection Lab
Goal
Protect applications from attacks.
Services Used
•	WAF
•	CloudFront
•	EC2
Tasks
•	Create WAF rules
•	Block SQL injection patterns
•	Block IP ranges
•	Monitor requests
Concepts Learned
•	Web application firewall
•	Layer 7 security
•	Traffic filtering
Time Required
3 hours
________________________________________
Project 15: Simulate Brute Force Detection
Goal
Detect repeated login attempts.
Services Used
•	CloudWatch
•	SNS
•	Lambda
Tasks
•	Generate failed login logs
•	Trigger alarms
•	Send notifications
Concepts Learned
•	Detection engineering
•	Event analysis
•	Alert pipelines
Time Required
2 hours
________________________________________
Week 6: DevSecOps and Containers
Project 16: Secure Docker on EC2
Goal
Run secure containers.
Services Used
•	EC2
•	Docker
•	IAM
Tasks
•	Install Docker
•	Restrict Docker permissions
•	Scan images
•	Run minimal containers
Concepts Learned
•	Container security
•	Linux isolation
•	Docker hardening
Time Required
3 hours
________________________________________
Project 17: Push Images to ECR
Goal
Use AWS container registry securely.
Services Used
•	ECR
•	IAM
Tasks
•	Build Docker image
•	Push image to ECR
•	Configure authentication
Concepts Learned
•	Image management
•	Secure registries
•	CI/CD basics
Time Required
2 hours
________________________________________
Project 18: ECS Secure Deployment
Goal
Deploy containers in AWS.
Services Used
•	ECS
•	ECR
•	IAM
Tasks
•	Create ECS cluster
•	Deploy container
•	Configure IAM task roles
Concepts Learned
•	Container orchestration
•	Role-based security
•	Cloud-native deployment
Time Required
3 to 4 hours
________________________________________
Week 7: Automation and Incident Response
Project 19: Auto-Isolate Suspicious EC2 Instance
Goal
Automate incident response.
Services Used
•	Lambda
•	CloudWatch
•	EC2
•	SNS
Tasks
•	Detect high-risk activity
•	Automatically change security groups
•	Notify via SNS
Concepts Learned
•	SOAR basics
•	Automated response
•	Cloud incident handling
Time Required
4 hours
________________________________________
Project 20: Auto Backup Critical Logs
Goal
Protect important logs.
Services Used
•	S3
•	Lambda
•	CloudWatch Events
Tasks
•	Schedule log backups
•	Archive logs to S3
Concepts Learned
•	Backup automation
•	Log retention
•	Disaster recovery basics
Time Required
2 hours
________________________________________
Project 21: Security Compliance Checker
Goal
Automatically verify AWS security settings.
Services Used
•	AWS Config
•	Lambda
•	SNS
Tasks
•	Detect public buckets
•	Detect unrestricted SSH
•	Send compliance alerts
Concepts Learned
•	Compliance automation
•	Governance
•	Security posture management
Time Required
3 hours
________________________________________
Week 8: Kubernetes and Cloud Security
Project 22: Deploy EKS Cluster
Goal
Learn Kubernetes in AWS.
Services Used
•	EKS
•	IAM
•	VPC
Tasks
•	Create small EKS cluster
•	Deploy nginx pod
•	Configure RBAC
Concepts Learned
•	Kubernetes basics
•	IAM integration
•	Cluster security
Time Required
4 hours
Important
Delete EKS cluster immediately after practice because EKS can become expensive.
________________________________________
Project 23: Kubernetes Network Policies
Goal
Restrict pod communication.
Services Used
•	EKS
•	Kubernetes Network Policies
Tasks
•	Create frontend/backend pods
•	Block unauthorized communication
Concepts Learned
•	Microsegmentation
•	Pod security
•	East-west traffic control
Time Required
2 hours
________________________________________
Project 24: Kubernetes Secrets Management
Goal
Secure secrets in Kubernetes.
Services Used
•	EKS
•	Secrets Manager
Tasks
•	Store DB password securely
•	Mount secrets into pod
Concepts Learned
•	Secret rotation
•	Kubernetes secrets
•	Secure workloads
Time Required
2 hours
________________________________________
Week 9: SOC and SIEM Style Labs
Project 25: Build Mini SOC Dashboard
Goal
Centralize security visibility.
Services Used
•	CloudWatch
•	SNS
•	GuardDuty
•	CloudTrail
Tasks
•	Combine logs and alerts
•	Create monitoring dashboard
•	Trigger alerts
Concepts Learned
•	SOC workflow
•	Alert triage
•	Security operations
Time Required
4 hours
________________________________________
Project 26: Failed Login Detection System
Goal
Detect suspicious SSH activity.
Services Used
•	CloudWatch Logs
•	Lambda
•	SNS
Tasks
•	Parse authentication logs
•	Count failures
•	Trigger notifications
Concepts Learned
•	Detection rules
•	Security analytics
•	Event correlation
Time Required
3 hours
________________________________________
Project 27: Threat Hunting with Athena
Goal
Query CloudTrail logs.
Services Used
•	Athena
•	S3
•	CloudTrail
Tasks
•	Store logs in S3
•	Query suspicious actions
•	Identify IAM anomalies
Concepts Learned
•	Threat hunting
•	Log querying
•	Cloud investigations
Time Required
3 hours
________________________________________
Week 10: Advanced Security Projects
Project 28: Multi-Account Security Setup
Goal
Understand enterprise AWS structure.
Services Used
•	AWS Organizations
•	IAM
•	SCPs
Tasks
•	Create sandbox account
•	Apply service control policies
Concepts Learned
•	Enterprise governance
•	Account isolation
•	Organizational security
Time Required
3 hours
________________________________________
Project 29: Secrets Manager Automation
Goal
Store and rotate secrets.
Services Used
•	Secrets Manager
•	Lambda
Tasks
•	Create secrets
•	Configure rotation logic
Concepts Learned
•	Credential protection
•	Secret lifecycle management
Time Required
2 hours
________________________________________
Project 30: Ransomware Recovery Simulation
Goal
Practice recovery procedures.
Services Used
•	EBS Snapshots
•	S3 Versioning
Tasks
•	Create backups
•	Simulate file deletion
•	Restore data
Concepts Learned
•	Backup strategy
•	Recovery workflows
•	Business continuity
Time Required
3 hours
________________________________________
Week 11: Resume-Level Capstone Projects
Project 31: Secure 3-Tier AWS Architecture
Goal
Build production-style infrastructure.
Services Used
•	VPC
•	EC2
•	ALB
•	RDS
•	IAM
Tasks
•	Public frontend
•	Private backend
•	Private database
•	Secure SG rules
Concepts Learned
•	Enterprise cloud architecture
•	Network isolation
•	Production security
Time Required
5 hours
________________________________________
Project 32: Cloud SIEM Pipeline
Goal
Build centralized logging pipeline.
Services Used
•	CloudTrail
•	S3
•	Lambda
•	Athena
Tasks
•	Collect logs
•	Process events
•	Query suspicious behavior
Concepts Learned
•	SIEM pipelines
•	Event ingestion
•	Security analytics
Time Required
4 hours
________________________________________
Project 33: DevSecOps CI/CD Pipeline
Goal
Secure deployment pipeline.
Services Used
•	CodePipeline
•	ECR
•	ECS
Tasks
•	Build container image
•	Scan image
•	Deploy automatically
Concepts Learned
•	DevSecOps
•	Automated deployment
•	CI/CD security
Time Required
4 hours
________________________________________
Week 12: Final Portfolio and Revision Week
Tasks for This Week
1. Create GitHub Documentation
Document:
•	Architecture diagrams
•	Screenshots
•	Security concepts
•	Commands used
•	Problems faced
•	Cost optimization
2. Create Resume Project Descriptions
Add:
•	AWS services used
•	Security outcomes
•	Automation achieved
•	Monitoring implemented
3. Record Demo Videos
Short demos:
•	GuardDuty findings
•	CloudWatch alerts
•	IAM setup
•	Kubernetes security
4. Cleanup AWS Resources
Delete:
•	Load balancers
•	EKS clusters
•	Snapshots
•	Unused EBS volumes
•	Lambda test resources
________________________________________
Recommended Project Order by Importance
If you cannot complete all projects, prioritize these:
1.	IAM Secure Environment
2.	Secure VPC Architecture
3.	CloudTrail Logging
4.	GuardDuty Threat Detection
5.	EC2 Hardening
6.	S3 Security
7.	AWS WAF
8.	Incident Response Automation
9.	EKS Security Basics
10.	Mini SOC Dashboard
11.	Threat Hunting with Athena
12.	Secure 3-Tier Architecture
________________________________________
Best Resume Projects from This Roadmap
These projects are highly valuable for cybersecurity and cloud interviews:
•	Automated Incident Response using Lambda
•	AWS Threat Hunting with Athena
•	Mini SOC Dashboard with CloudWatch
•	Secure Kubernetes Deployment on EKS
•	AWS WAF Security Lab
•	Cloud SIEM Pipeline
•	DevSecOps CI/CD Security Pipeline
•	Secure 3-Tier AWS Architecture
________________________________________
Skills You Will Gain
By the end of this roadmap you will understand:
•	AWS cloud fundamentals
•	Cloud security architecture
•	IAM and least privilege
•	Threat detection
•	SOC monitoring
•	SIEM-style analysis
•	Kubernetes security
•	Incident response automation
•	DevSecOps security
•	Vulnerability management
•	Logging and auditing
•	Container security
•	Security compliance
________________________________________
Suggested Daily Routine
Activity	Duration
Theory and reading	30 mins
AWS implementation	1.5 to 2 hours
Documentation	20 mins
Cleanup and billing check	10 mins
________________________________________
Final Advice
1.	Take screenshots of every project.
2.	Keep all Terraform/YAML/commands in GitHub.
3.	Focus more on security concepts than just clicking in AWS.
4.	Always explain why a service is used.
5.	Learn troubleshooting while building.
6.	Practice explaining architecture verbally.
7.	Track your AWS billing every day.
8.	Clean resources immediately after practice.
This roadmap is enough to build strong practical AWS cybersecurity experience within your remaining free-tier period while keeping costs manageable.

