# Fast-AWS
This repo covers AWS Hands-on Labs for different AWS services.

## Why was this repo created?
- Shows/maps AWS services in short with reference AWS developer documentation  
- Shows AWS Hands-on LABs with clean demos. In-time, different AWS Hands-on LABs will be added.
- Contributes to AWS open source community.
  
# Quick Look (How-To): AWS Hands-on Labs
These hands-on labs focus on how to create and use AWS components:
- [HANDS-ON-01: Provisioning EC2s on VPC, Creating Key-Pair, Connecting EC2](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE01-EC2-VPC-Ubuntu-Win-SSH-RDP.md)
- [HANDS-ON-02: Provisioning Lambda, API Gateway and Reaching HTML Page in Python Code From Browser](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE02-Lambda-API-Gateway-Python.md)
- [HANDS-ON-03: EBS and EFS Configuration with EC2s](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE03-EC2-EBS-EFS.md)
- [HANDS-ON-04: Provisioning ECR, Pushing Image to ECR, Provisioning ECS, VPC, ELB, ECS Tasks, Service on Fargate Cluster](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE04-ECR-ECS-ELB-VPC-ECS-Service.md)
- [HANDS-ON-05: Provisioning ECR, Lambda and API Gateway to run Flask App Container on Lambda](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE05-Lambda-Container-ApiGateway-FlaskApp.md)
- [HANDS-ON-06: Provisioning EKS with Managed Nodes using Blueprint and Modules](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE06-EKS-ManagedNodes-Blueprint.md)
- [HANDS-ON-07: Provisioning CodeCommit, CodePipeline and Triggering CodeBuild and CodeDeploy Container in Lambda](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE07-CodeCommit-Pipeline-Build-Deploy-Lambda.md)
- [HANDS-ON-08: Provisioning S3, CloudFront to serve Static Web Site](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE08-S3-CloudFront-Static-WebSite.md)
- [HANDS-ON-09: Provisioned Gitlab Runner on EC2, connection to Gitlab Server using Docker on-premise](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE09-GitlabServer-on-Premise-GitlabRunner-on-EC2.md)
- [HANDS-ON-10: Implementing MLOps Pipeline using GitHub, CodePipeline, CodeBuild, CodeDeploy, Sagemaker Endpoint](https://github.com/omerbsezer/Fast-Terraform/blob/main/SAMPLE10-MLOps-SageMaker-GitHub-Codepipeline-CodeBuild-CodeDeploy.md)

# Table of Contents
- [Motivation](#motivation)
- [Common AWS Services In-Short](#servicesshort)
  - [1. Compute Services](#compute)
  - [2. Container Services](#container)
  - [3. Storage Services](#storage)
  - [4. Database Services](#database)
  - [5. Data Analytics Services](#dataanalytics)
  - [6. Integration Services ](#integration)
  - [7. Cloud Financial Management Services](#cloudfinancial)
  - [8. Management & Governance Services](#managementgovernance)
  - [9. Security, Identity, & Compliance Services](#securityidentity)
  - [10. Networking Services](#networking)
  - [11. Migration Services](#migration)
  - [12. Internet of Things Services](#internetofthings)
  - [13. Artificial Intelligence Services](#artificialintelligence)
- [AWS Hands-on Labs](#samples)
  - [HANDS-ON-01: EC2s (Windows 2019 Server, Ubuntu 20.04), VPC, Key-Pairs for SSH, RDP connections](#ec2_vpc_key_pair_ssh_rdp)
  - [HANDS-ON-02: Provisioning Lambda Function, API Gateway and Reaching HTML Page in Python Code From Browsers](#lambda_apigateway_python)
  - [HANDS-ON-03: EBS (Elastic Block Storage: HDD, SDD) and EFS (Elastic File System: NFS) Configuration with EC2s (Ubuntu and Windows Instances)](#ebs_efs_ec2)
  - [HANDS-ON-04: Provisioning ECR (Elastic Container Repository), Pushing Image to ECR, Provisioning ECS (Elastic Container Service), VPC (Virtual Private Cloud), ELB (Elastic Load Balancer), ECS Tasks and Service on Fargate Cluster](#ecr_ecs_elb_vpc_ecs_service_fargate)
  - [HANDS-ON-05: Provisioning ECR, Lambda Function and API Gateway to run Flask App Container on Lambda](#ecr_lambda_apigateway_container)
  - [HANDS-ON-06: Provisioning EKS (Elastic Kubernetes Service) with Managed Nodes using Blueprint and Modules](#eks_managednodes_blueprint)
  - [HANDS-ON-07: CI/CD on AWS => Provisioning CodeCommit and CodePipeline, Triggering CodeBuild and CodeDeploy, Running on Lambda Container](#ci_cd)
  - [HANDS-ON-08: Provisioning S3 and CloudFront to serve Static Web Site](#s3_cloudfront)
  - [HANDS-ON-09: Running Gitlab Server using Docker on Local Machine and Making Connection to Provisioned Gitlab Runner on EC2 in Home Internet without Using VPN](#gitlabrunner)
  - [HANDS-ON-10: Implementing MLOps Pipeline using GitHub, AWS CodePipeline, AWS CodeBuild, AWS CodeDeploy, and AWS Sagemaker (Endpoint)](#sagemaker)
- [References](#references)

## Motivation <a name="motivation"></a>
Why should we use / learn cloud?
- cloud

Why should we use / learn AWS?
- aws

## AWS Services In-Short <a name="servicesshort"></a>
There are more than 200 AWS services. Popular services are listed in short.

### 1. Compute Services <a name="compute"></a>
#### Amazon EC2 
- Virtual servers in the cloud
- **Document**: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html

  ![image](https://github.com/user-attachments/assets/cd0f3f0f-b5eb-4ce6-8355-0fab607c1a20)

#### Amazon EC2 Auto Scaling 
- Scale compute capacity to meet demand
- **Document**: https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html

  ![image](https://github.com/user-attachments/assets/16603fd1-fd4c-457b-8f36-e6a8e8ae5ff2)

#### Amazon Lightsail 
- Launch and manage virtual private servers
- **Document**: https://docs.aws.amazon.com/lightsail/latest/userguide/what-is-amazon-lightsail.html

  ![image](https://github.com/user-attachments/assets/60008da9-9416-4627-9aee-9f6736fc7511)

#### AWS App Runner
- Build and run containerized web apps at scale
- **Document**: https://docs.aws.amazon.com/apprunner/latest/dg/what-is-apprunner.html

  ![image](https://github.com/user-attachments/assets/3a22fb4c-0488-4d9d-88ee-b6081cfde4d9)

#### AWS Batch
- Run batch jobs at any scale
- **Document**: https://docs.aws.amazon.com/batch/latest/userguide/what-is-batch.html

  ![image](https://github.com/user-attachments/assets/6f53153d-eb3f-4f9f-99a4-69aea599ed4a)

#### AWS Elastic Beanstalk
- Run and manage web apps
- **Document**: https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/Welcome.html

  ![image](https://github.com/user-attachments/assets/5cdd1b43-af04-4e3d-b2d4-15e92ac55c11)

#### AWS Amplify
- Build, deploy, and host scalable web and mobile apps
- **Document**: https://docs.aws.amazon.com/amplify/latest/userguide/welcome.html

  ![image](https://github.com/user-attachments/assets/0b5d3e6e-2d7c-46a4-9243-9ded17074b8e)

#### AWS Lambda
- Run code without thinking about servers
- **Document**: https://docs.aws.amazon.com/lambda/latest/dg/welcome.html

  ![image](https://github.com/user-attachments/assets/84cd58a9-6a2e-49ff-84e5-b8ca68bab969)
  
#### AWS Outposts
- Run AWS infrastructure on-premises
- **Document**: https://docs.aws.amazon.com/outposts/latest/userguide/what-is-outposts.html 

  ![image](https://github.com/user-attachments/assets/5ca3081a-4fd6-4a3c-8f60-2350a1ae7eff)

#### AWS Parallel Computing Service
- Easily run HPC workloads at virtually any scale
- **Document**: https://docs.aws.amazon.com/pcs/latest/userguide/what-is-service.html

  ![image](https://github.com/user-attachments/assets/4a2146a7-b0a2-4708-9990-d66ea26dafb3)

#### AWS Serverless Application Repository
- Discover, deploy, and publish serverless applications
- **Document**: https://docs.aws.amazon.com/serverlessrepo/latest/devguide/what-is-serverlessrepo.html

  ![image](https://github.com/user-attachments/assets/05ddbc6f-d00a-4426-be4f-824d2fbd2c39)

#### AWS Wavelength
- Deliver ultra-low latency applications for 5G devices
- **Document**: https://docs.aws.amazon.com/wavelength/latest/developerguide/how-wavelengths-work.html

  ![image](https://github.com/user-attachments/assets/dfa8b4b9-4be0-455f-b882-9e90be774d35)
  
### 2. Container Services  <a name="container"></a>
#### Amazon Elastic Container Registry
- Easily store, manage, and deploy container images
- **Document**: https://docs.aws.amazon.com/AmazonECR/latest/userguide/what-is-ecr.html

  ![image](https://github.com/user-attachments/assets/970aab11-7b16-4666-b991-a0245ccc5ff6)

#### Amazon Elastic Container Service (ECS)
- Highly secure, reliable, and scalable way to run containers
- **Document**: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html

  ![image](https://github.com/user-attachments/assets/b84868c1-357e-46e9-90b0-cb69adf5c142)

#### Amazon Elastic Kubernetes Service (EKS)
- The most trusted way to run Kubernetes
- Amazon EKS Anywhere: Kubernetes on your infrastructure
- Amazon EKS Distro: Run consistent Kubernetes clusters
- **Document**: https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html

  ![image](https://github.com/user-attachments/assets/269b7c36-cdcb-45e6-b971-44bd3d3a040f)

#### AWS App2Container
- Containerize and migrate existing applications
- **Document**: https://docs.aws.amazon.com/app2container/latest/UserGuide/what-is-a2c.html
  
#### AWS App Runner 
- Build and run containerized web apps at scale
- **Document**: https://docs.aws.amazon.com/apprunner/latest/dg/what-is-apprunner.html

  ![image](https://github.com/user-attachments/assets/bd40d558-4d05-4d1e-a811-f4b252765fca)

#### AWS Fargate
- Serverless compute for containers
- **ECS Fargate Document**: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Fargate.html
- **EKS Fargate Document**: https://docs.aws.amazon.com/eks/latest/userguide/fargate-getting-started.html

  ![image](https://github.com/user-attachments/assets/6f2b8ad4-ceaf-4062-9f8c-70dac3f0ef8a)
  
### 3. Storage Services <a name="storage"></a>
#### Amazon Simple Storage Service (S3)
- Scalable storage in the cloud
- **Document**: https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html

  ![image](https://github.com/user-attachments/assets/7da8eaa2-9ef3-4ad5-abc9-db39b5319471)

#### Amazon S3 Glacier storage classes
- Low-cost archive storage in the cloud
- **Document**: https://docs.aws.amazon.com/amazonglacier/latest/dev/introduction.html

  ![image](https://github.com/user-attachments/assets/bfb0e51b-3865-4d4e-a51e-dd0b436f957d)

#### Amazon Elastic Block Store (EBS)
- EC2 block storage volumes
- **Document**: https://docs.aws.amazon.com/ebs/latest/userguide/what-is-ebs.html

  ![image](https://github.com/user-attachments/assets/72a7f9af-3701-4fef-b34c-4388ff3cffa4)

#### Amazon Elastic File System (EFS)
- Fully managed file system for EC2
- **Document**: https://docs.aws.amazon.com/efs/latest/ug/whatisefs.html

  ![image](https://github.com/user-attachments/assets/d1edfac2-7327-4e69-9506-062bd1fd2781)

#### Amazon FSx for Lustre
- High-performance file system integrated with S3
- **Document**: https://docs.aws.amazon.com/fsx/latest/LustreGuide/what-is.html

  ![image](https://github.com/user-attachments/assets/23f90755-e706-4a18-8fcf-93562a7d6095)

#### Amazon FSx for NetApp ONTAP
- Fully managed storage built on NetApp’s popular ONTAP file system
- **Document**: https://docs.aws.amazon.com/fsx/latest/ONTAPGuide/what-is-fsx-ontap.html

  ![image](https://github.com/user-attachments/assets/0a7cbfb1-5cce-4e9a-8f9e-856423eb871e)

#### Amazon FSx for OpenZFS
- Fully managed storage built on the popular OpenZFS file system
- **Document**: https://docs.aws.amazon.com/fsx/latest/OpenZFSGuide/what-is-fsx.html

  ![image](https://github.com/user-attachments/assets/ad74c091-1847-4430-97db-41e183fda6c3)

#### Amazon FSx for Windows File Server
- Fully managed Windows native file system
- **Document**: https://docs.aws.amazon.com/fsx/latest/WindowsGuide/what-is.html

  ![image](https://github.com/user-attachments/assets/b6f01955-e0e7-46e7-8944-f42b6f7769a6)

#### Amazon File Cache
- High-speed cache for datasets stored anywhere
- **Document**: https://docs.aws.amazon.com/fsx/latest/FileCacheGuide/what-is.html

#### AWS Backup
- Centralized backup across AWS services
- **Document**: https://docs.aws.amazon.com/aws-backup/latest/devguide/whatisbackup.html

#### AWS Elastic Disaster Recovery (DRS)
- Scalable, cost-effective application recovery
- **Document**: https://docs.aws.amazon.com/drs/latest/userguide/what-is-drs.html

#### AWS Snowball
- Accelerate moving offline data or remote storage to the cloud
- **Document**: https://docs.aws.amazon.com/snowball/latest/developer-guide/whatisedge.html

  ![image](https://github.com/user-attachments/assets/b3952505-33d2-4f85-bc45-5be4bf808a0a)

#### AWS Storage Gateway
- Hybrid storage integration
- **S3 File Gateway Document**: https://docs.aws.amazon.com/filegateway/latest/files3/what-is-file-s3.html
- **Volume Gateway Document**: https://docs.aws.amazon.com/storagegateway/latest/vgw/WhatIsStorageGateway.html
- **Tape Gateway Document**: https://docs.aws.amazon.com/storagegateway/latest/tgw/WhatIsStorageGateway.html
- **FSx File Gateway Document**: https://docs.aws.amazon.com/filegateway/latest/filefsxw/what-is-file-fsxw.html

  ![image](https://github.com/user-attachments/assets/a0d4624f-25e4-4ebb-88b7-fa201de2017c)

### 4. Database Services <a name="database"></a>
#### Amazon Aurora
- High performance managed relational database with full MySQL and PostgreSQL compatibility
- **Document**: https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html

  ![image](https://github.com/user-attachments/assets/ff0f99bf-72a8-46b7-b1ef-7cc3b16b9e34)

#### Amazon Aurora DSQL
- Fastest serverless distributed SQL database with active-active high availability
- **Document**: https://docs.aws.amazon.com/aurora-dsql/latest/userguide/getting-started.html

#### Amazon Aurora Serverless V2
- Instantly scale to >100,000 transactions per second
- **Document**: https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/aurora-serverless-v2.html

#### Amazon DocumentDB (with MongoDB compatibility)
- Fully managed **Document** database
- **Document**: https://docs.aws.amazon.com/documentdb/latest/developerguide/what-is.html

  ![image](https://github.com/user-attachments/assets/d688eafd-68d3-432a-b53b-6f4b8c62c449)

#### Amazon DynamoDB
- Managed NoSQL database
- **Document**: https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html

  ![image](https://github.com/user-attachments/assets/de1a9525-7f85-4534-b837-8f011940b07b)

#### Amazon ElastiCache
- In-memory caching service for Valkey, Memcached, and Redis OSS
- **Document**: https://docs.aws.amazon.com/AmazonElastiCache/latest/dg/WhatIs.html

  ![image](https://github.com/user-attachments/assets/09293da6-3743-4c4e-81d9-f5e1c8e52f54)

#### Amazon Keyspaces (for Apache Cassandra)
- Managed Cassandra-compatible database
- **Document**: https://docs.aws.amazon.com/keyspaces/latest/devguide/what-is-keyspaces.html

  ![image](https://github.com/user-attachments/assets/d269501a-1ecd-4421-937c-8410d6aca37e)

#### Amazon MemoryDB
- Valkey- and Redis OSS-compatible, durable, in-memory database with ultra-fast performance
- **Document**: https://docs.aws.amazon.com/memorydb/latest/devguide/what-is-memorydb.html

  ![image](https://github.com/user-attachments/assets/43a87fad-de4b-47e8-ae66-d1b30d8650fc)

#### Amazon Neptune
- Fully managed graph database service
- **Document**: https://docs.aws.amazon.com/neptune/latest/userguide/intro.html

  ![image](https://github.com/user-attachments/assets/d76168fb-cfd7-4274-bf2d-9c879d90b95b)

#### Amazon RDS
- Managed relational database service for PostgreSQL, MySQL, MariaDB, SQL Server, Oracle, and Db2
- **Document**: https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html

  ![image](https://github.com/user-attachments/assets/fdc8224e-991f-4673-bd30-8158158e0c6c)

#### Amazon Timestream
- Fully managed time series database
- **Document**: https://docs.aws.amazon.com/timestream/latest/developerguide/what-is-timestream.html

  ![image](https://github.com/user-attachments/assets/d8ce9ecd-fbf7-4e97-a2e2-8491b5a36703)

#### Amazon Redshift
- Fast, simple, cost-effective data warehousing
- **Document**: https://docs.aws.amazon.com/redshift/latest/gsg/new-user-serverless.html

  ![image](https://github.com/user-attachments/assets/ef4b1c88-42f8-4163-b16a-e65531df1ea6)  

### 5. Data Analytics Services <a name="dataanalytics"></a>
#### Amazon Athena
- Query data in S3 using SQL
- **Document**: https://docs.aws.amazon.com/athena/latest/ug/what-is.html

#### Amazon OpenSearch Service
- Search, visualize, and analyze up to petabytes of text and unstructured data
- **Document**: https://docs.aws.amazon.com/opensearch-service/latest/developerguide/what-is.html

#### Amazon EMR
- Easily run big data frameworks
- **Document**: https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-what-is-emr.html

#### Amazon FinSpace
- Analytics for the financial services industry
- **Document**: https://docs.aws.amazon.com/finspace/latest/userguide/finspace-what-is.html

#### Amazon Kinesis Analytics
- Analyze real-time video and data streams
- **Document**: https://docs.aws.amazon.com/kinesisanalytics/latest/sqlref/analytics-sql-reference-dg.html

#### Amazon Neptune Analytics
- With Neptune Analytics, you can get insights and find trends by processing large amounts of graph data in seconds.
- **Document**: https://docs.aws.amazon.com/neptune-analytics/latest/userguide/what-is-neptune-analytics.html
  
#### Amazon Data Firehose
- Real-time streaming delivery for any data, at any scale, at low-cost
- **Document**: https://docs.aws.amazon.com/firehose/latest/dev/what-is-this-service.html

#### Amazon Managed Service for Apache Flink
- Fully managed Apache Flink service
- **Document**: https://docs.aws.amazon.com/managed-flink/latest/java/how-it-works.html

#### Amazon Managed Streaming for Apache Kafka
- Fully managed Apache Kafka service
- **Document**: https://docs.aws.amazon.com/msk/latest/developerguide/what-is-msk.html



#### Amazon QuickSight
- Fast business analytics service
- **Document**: https://docs.aws.amazon.com/quicksight/latest/user/welcome.html

#### AWS Data Exchange
- Find, subscribe to, and use third-party data in the cloud
- **Document**: https://docs.aws.amazon.com/data-exchange/latest/userguide/what-is.html

#### AWS Glue
- Simple, scalable, and serverless data integration
- **Document**: https://docs.aws.amazon.com/glue/latest/dg/what-is-glue.html

#### AWS Lake Formation
- Build, manage, and secure your data lake
- **Document**: https://docs.aws.amazon.com/lake-formation/latest/dg/what-is-lake-formation.html

### 6. Integration Services <a name="integration"></a>
#### AWS Step Functions
- Coordination for distributed applications
- **Document**: https://docs.aws.amazon.com/step-functions/latest/dg/welcome.html

#### Amazon API Gateway
- Build, deploy, and manage APIs
- **Document**: https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html

#### Amazon AppFlow
- No-code integration for SaaS apps & AWS services
- **Document**: https://docs.aws.amazon.com/appflow/latest/userguide/what-is-appflow.html

#### Amazon EventBridge
- Serverless event bus for SaaS apps & AWS services
- **Document**: https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-what-is.html

#### Amazon Managed Workflows for Apache Airflow
- Highly available, secure, and managed workflow orchestration
- **Document**: https://docs.aws.amazon.com/mwaa/latest/userguide/what-is-mwaa.html

#### Amazon MQ
- Managed message broker service
- **Document**: https://docs.aws.amazon.com/amazon-mq/latest/developer-guide/welcome.html

#### Amazon Simple Notification Service (SNS)
- Pub/sub, SMS, email, and mobile push notifications
- **Document**: https://docs.aws.amazon.com/sns/latest/dg/welcome.html

#### Amazon Simple Queue Service (SQS)
- Managed message queues
- **Document**: https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html

#### AWS AppSync
- Fully-managed, scalable GraphQL APIs
- **Document**: https://docs.aws.amazon.com/appsync/latest/devguide/what-is-appsync.html

### 7. Cloud Financial Management Services <a name="cloudfinancial"></a>
#### AWS Cost Explorer
- Analyze your AWS cost and usage
- **Document**: https://docs.aws.amazon.com/solutions/latest/amazon-marketing-cloud-insights-on-aws/aws-cost-explorer.html

#### AWS Billing Conductor
- Simplify billing and reporting with customizable pricing and cost visibility
- **Document**: https://docs.aws.amazon.com/billingconductor/latest/userguide/what-is-billingconductor.html

#### AWS Billing and Cost Management
- Billing and payments
- Cost analysis
- Cost organization
- Budgeting and planning
- Savings and commitments
- Set custom cost and usage budgets
- **Document**: https://docs.aws.amazon.com/cost-management/latest/userguide/what-is-costmanagement.html

### 8. Management & Governance Services <a name="managementgovernance"></a>
#### Amazon CloudWatch
- Monitor resources and applications
- **Document**: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html

#### Amazon Managed Grafana
- Powerful interactive data visualizations
- **Document**: https://docs.aws.amazon.com/grafana/latest/userguide/what-is-Amazon-Managed-Service-Grafana.html

#### Amazon Managed Service for Prometheus
- Highly available, secure monitoring for containers
- **Document**: https://docs.aws.amazon.com/prometheus/latest/userguide/what-is-Amazon-Managed-Service-Prometheus.html

#### AWS CloudFormation
- Create and manage resources with templates
- **Document**: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html

#### AWS CloudTrail
- Track user activity and API usage
- **Document**: https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-user-guide.html

#### AWS Command Line Interface
- Unified tool to manage AWS services
- **Document**: https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html

#### AWS Compute Optimizer
- Identify optimal AWS Compute resources
- **Document**: https://docs.aws.amazon.com/compute-optimizer/latest/ug/what-is-compute-optimizer.html

  ![image](https://github.com/user-attachments/assets/fdb2c41f-c867-4894-88c9-6e11c031236b)

#### AWS Config
- Track resources inventory and changes
- **Document**: https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html

#### AWS Control Tower
- Set up and govern a secure, compliant multi-account environment
- **Document**: https://docs.aws.amazon.com/controltower/latest/userguide/what-is-control-tower.html

#### AWS Health Dashboard
- View important events and changes affecting your AWS environment
- **Document**: https://docs.aws.amazon.com/health/latest/ug/aws-health-dashboard-status.html

#### AWS License Manager
- Track, manage, and control licenses
- **Document**: https://docs.aws.amazon.com/license-manager/latest/userguide/license-manager.html

#### AWS Management Console
- Web-based user interface
- **Document**: https://docs.aws.amazon.com/awsconsolehelpdocs/latest/gsg/what-is.html

#### AWS Managed Services (MS)
- Infrastructure operations management for AWS
- **AMS Document**: https://docs.aws.amazon.com/managedservices/latest/userguide/what-is-ams.html
- **AMS Accelerate Document**: https://docs.aws.amazon.com/managedservices/latest/accelerate-guide/what-is-acc.html
- **AMS Advanced Application Document**: https://docs.aws.amazon.com/managedservices/latest/appguide/intro-aog.html

#### AWS Organizations
- Central governance and management across AWS accounts
- **Document**: https://docs.aws.amazon.com/organizations/latest/userguide/orgs_introduction.html

#### AWS Proton
- Automated management for container and serverless deployment
- **Document**: https://docs.aws.amazon.com/proton/latest/userguide/Welcome.html

#### AWS Service Catalog
- Create and use standardized products
- **Document**: https://docs.aws.amazon.com/servicecatalog/latest/adminguide/introduction.html

#### AWS Systems Manager
- Gain operational insights and take action
- **Document**: https://docs.aws.amazon.com/systems-manager/latest/userguide/what-is-systems-manager.html

#### AWS Trusted Advisor
- Optimize performance and security
- **Document**: https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor.html

#### AWS User Notifications
- Configure and view notifications from AWS services
- **Document**: https://docs.aws.amazon.com/notifications/latest/userguide/what-is-service.html

#### AWS Well-Architected Tool
- Review and improve your workloads
- **Document**: https://docs.aws.amazon.com/wellarchitected/latest/userguide/intro.html

### 9. Security, Identity, & Compliance Services <a name="securityidentity"></a>
#### AWS Identity and Access Management (IAM)
- Securely manage access to services and resources
- **Document**: https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html

#### Amazon Cognito
- Identity management for your apps. It handles user authentication and authorization for your web and mobile apps.
- With user pools, you can easily and securely add sign-up and sign-in functionality to your apps.
- With identity pools (federated identities), your apps can get temporary credentials that grant users access to specific AWS resources, whether the users are anonymous or are signed in.
- **User Pools Document**: https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-user-pools.html
- **Identity Pools Document**: https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-identity.html
- **Cognito Sync Document**: https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-sync.html

#### Amazon Detective
- Investigate potential security issues
- **Document**: https://docs.aws.amazon.com/detective/latest/userguide/what-is-detective.html

#### Amazon GuardDuty
- Managed threat detection service
- **Document**: https://docs.aws.amazon.com/guardduty/latest/ug/what-is-guardduty.html

#### Amazon Inspector
- Automate vulnerability management
- **Document**: https://docs.aws.amazon.com/inspector/latest/user/what-is-inspector.html

#### Amazon Macie
- Discover and protect your sensitive data at scale
- **Document**: https://docs.aws.amazon.com/macie/latest/user/what-is-macie.html

#### Amazon Security Lake
- Automatically centralize your security data with a few clicks
- **Document**: https://docs.aws.amazon.com/security-lake/latest/userguide/what-is-security-lake.html

#### Amazon Verified Permissions
- Fine-grained permissions and authorization for your applications
- **Document**: https://docs.aws.amazon.com/verifiedpermissions/latest/userguide/what-is-avp.html

#### AWS Artifact
- On-demand access to AWS’ compliance reports
- **Document**: https://docs.aws.amazon.com/artifact/latest/ug/what-is-aws-artifact.html

#### AWS Audit Manager
- Continuously audit your AWS usage
- **Document**: https://docs.aws.amazon.com/audit-manager/latest/userguide/what-is.html

#### AWS Certificate Manager
- Provision, manage, and deploy SSL/TLS certificates
- **Document**: https://docs.aws.amazon.com/acm/latest/userguide/acm-overview.html

#### AWS CloudHSM
- Hardware-based key storage for regulatory compliance
- **Document**: https://docs.aws.amazon.com/cloudhsm/latest/userguide/introduction.html

#### AWS Directory Service
- Host and manage active directory
- **Document**: https://docs.aws.amazon.com/directoryservice/latest/admin-guide/what_is.html

#### AWS Firewall Manager
- Central management of firewall rules
- **Document**: https://docs.aws.amazon.com/waf/latest/developerguide/fms-chapter.html

#### AWS Key Management Service
- Managed creation and control of encryption keys
- **Document**: https://docs.aws.amazon.com/kms/latest/developerguide/overview.html

#### AWS Network Firewall
- Network security to protect your VPCs
- **Document**: https://docs.aws.amazon.com/network-firewall/latest/developerguide/what-is-aws-network-firewall.html

#### AWS Resource Access Manager
- Simple, secure service to share AWS resources
- **Document**: https://docs.aws.amazon.com/resource-explorer/latest/userguide/welcome.html

#### AWS Secrets Manager
- Rotate, manage, and retrieve secrets
- **Document**: https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html

#### AWS Security Hub
- Unified security and compliance center
- **Document**: https://docs.aws.amazon.com/securityhub/latest/userguide/what-is-securityhub.html

#### AWS Shield
- DDoS protection
- **Document**: https://docs.aws.amazon.com/waf/latest/developerguide/shield-chapter.html

#### AWS IAM Identity Center
- Manage single sign-on access to AWS accounts and apps
- **Document**: https://docs.aws.amazon.com/singlesignon/latest/userguide/what-is.html

#### AWS WAF
- Filter malicious web traffic
- **Document**: https://docs.aws.amazon.com/waf/latest/developerguide/waf-chapter.html

### 10. Networking Services <a name="networking"></a>
#### Amazon VPC
- Isolated cloud resources
- **Document**: https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html

#### Amazon VPC Lattice
- Simplify service-to-service connectivity, security, and monitoring
- **Document**: https://docs.aws.amazon.com/vpc-lattice/latest/ug/what-is-vpc-lattice.html

#### Amazon API Gateway
- Build, deploy, and manage APIs
- **Document**: https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html

#### Amazon CloudFront
- Global content delivery network
- **Document**: https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html

#### Amazon Route 53
- Scalable domain name system (DNS)
- **Document**: https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html

#### AWS App Mesh
- Monitor and control microservices
- **Document**: https://docs.aws.amazon.com/app-mesh/latest/userguide/what-is-app-mesh.html

#### AWS Cloud Map
- Service discovery for cloud resources
- **Document**: https://docs.aws.amazon.com/cloud-map/latest/dg/what-is-cloud-map.html

#### AWS Cloud WAN
- Easily build, manage, and monitor global wide area networks
- **Document**: https://docs.aws.amazon.com/whitepapers/latest/aws-vpc-connectivity-options/aws-cloud-wan.html

#### AWS Direct Connect
- Dedicated network connection to AWS
- **Document**: https://docs.aws.amazon.com/directconnect/latest/UserGuide/Welcome.html

#### AWS Global Accelerator
- Improve application availability and performance
- **Document**: https://docs.aws.amazon.com/global-accelerator/latest/dg/what-is-global-accelerator.html

#### AWS Private 5G
- Easily deploy, manage, and scale a private cellular network
- **Document**: https://docs.aws.amazon.com/private-networks/latest/userguide/what-is-private-5g.html

#### AWS PrivateLink
- Securely access services hosted on AWS
- Connect another VPC and VPC resources with interface endpoint
- **Document**: https://docs.aws.amazon.com/vpc/latest/privatelink/what-is-privatelink.html

#### AWS Transit Gateway
- Easily scale VPC and account connections
- **Document**: https://docs.aws.amazon.com/vpc/latest/tgw/what-is-transit-gateway.html

#### AWS Verified Access
- Provide secure access to corporate applications without a VPN
- **Document**: https://docs.aws.amazon.com/verified-access/latest/ug/what-is-verified-access.html

#### AWS Client VPN
- Securely access your network resources
- **Document**: https://docs.aws.amazon.com/vpn/latest/clientvpn-user/client-vpn-user-what-is.html

#### AWS Site-to-Site VPN
-  Enable access to your remote network from your VPC by creating an AWS Site-to-Site VPN connection, and configuring routing to pass traffic through the connection.
- **Document**: https://docs.aws.amazon.com/vpn/latest/s2svpn/VPC_VPN.html

#### Elastic Load Balancing (ELB)
- Distribute incoming traffic across multiple targets
- **Elastic Load Balancing Document**: https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/what-is-load-balancing.html
- **Application Load Balancer Document**: https://docs.aws.amazon.com/elasticloadbalancing/latest/application/introduction.html
- **Network Load Balancer Document**: https://docs.aws.amazon.com/elasticloadbalancing/latest/network/introduction.html
- **Gateway Load Balancer Document**: https://docs.aws.amazon.com/elasticloadbalancing/latest/gateway/introduction.html
- **Classic Load Balancer Document**: https://docs.aws.amazon.com/elasticloadbalancing/latest/classic/introduction.html

  ![image](https://github.com/user-attachments/assets/42f0550d-4413-4000-ba7a-c133d9129bfe)

### 11. Migration Services <a name="migration"></a>
#### AWS Migration Hub
- Track migrations from a single place
- **Document**: https://docs.aws.amazon.com/migrationhub/latest/ug/whatishub.html

#### AWS Application Discovery Service
- Discover on-premises applications to streamline migration
- **Document**: https://docs.aws.amazon.com/application-discovery/latest/userguide/what-is-appdiscovery.html

#### AWS Application Migration Service (MGN)
- Move and improve your on-premises and cloud-based applications
- **Document**: https://docs.aws.amazon.com/mgn/latest/ug/what-is-application-migration-service.html

#### AWS Database Migration Service
- Migrate databases with minimal downtime
- **Document**: https://docs.aws.amazon.com/dms/latest/userguide/Welcome.html

#### AWS DataSync
- Simple, fast, online data transfer
- **Document**: https://docs.aws.amazon.com/datasync/latest/userguide/what-is-datasync.html

#### AWS Migration Acceleration Program
- Comprehensive and proven cloud migration program
- **Document**: https://docs.aws.amazon.com/migrationhub/latest/launchguide/map.html

#### AWS Optimization and Licensing Assessment
- Optimize your license and compute costs before and after migration
- **Document**: https://docs.aws.amazon.com/prescriptive-guidance/latest/optimize-costs-microsoft-workloads/aws-ola.html

#### AWS Transfer Family
- Fully managed SFTP, FTPS, FTP, and AS2 service
- **Document**: https://docs.aws.amazon.com/transfer/latest/userguide/what-is-aws-transfer-family.html

### 12. Internet of Things Services <a name="internetofthings"></a>
#### AWS IoT Core
- Connect devices to the cloud
- **Document**: https://docs.aws.amazon.com/iot/latest/developerguide/what-is-aws-iot.html

#### AWS IoT Device Defender
- Security management for IoT devices
- **Document**: https://docs.aws.amazon.com/iot-device-defender/latest/devguide/what-is-device-defender.html

#### AWS IoT Fleet Hub for AWS IoT Device Management
- Monitor device fleets in near-real time.
- Set alerts to notify your technicians about unusual behavior.
- Running jobs.
- **Document**: https://docs.aws.amazon.com/iot/latest/fleethubuserguide/what-is-aws-iot-monitor.html

#### AWS IoT Events
- IoT event detection and response
- **Document**: https://docs.aws.amazon.com/iotevents/latest/developerguide/what-is-iotevents.html

#### AWS IoT FleetWise
- Easily collect, transform, and transfer vehicle data to the cloud in near-real time
- **Document**: https://docs.aws.amazon.com/iot-fleetwise/latest/developerguide/what-is-iotfleetwise.html

#### AWS IoT Greengrass
- Local compute, messaging, and sync for devices
- **Document**: https://docs.aws.amazon.com/greengrass/v2/developerguide/what-is-iot-greengrass.html

#### Amazon Kinesis Video Streams
- Capture, process, and analyze real-time video streams
- **Document**: https://docs.aws.amazon.com/kinesisvideostreams/latest/dg/what-is-kinesis-video.html

#### FreeRTOS
- Real-time operating system for microcontrollers
- **Document**: https://docs.aws.amazon.com/freertos/latest/userguide/what-is-freertos.html

#### Amazon Location Service
- Securely and easily add location data to applications
- **Document**: https://docs.aws.amazon.com/location/

#### AWS Device Farm
- Test Android, iOS, and web apps on real devices in the AWS cloud
- **Document**: https://docs.aws.amazon.com/devicefarm/latest/developerguide/welcome.html

### 13. Artificial Intelligence Services <a name="artificialintelligence"></a>
#### Amazon Q
- Generative AI-powered assistant for work
- **Amazon Q Business Document**: https://docs.aws.amazon.com/amazonq/latest/qbusiness-ug/what-is.html
- **Amazon Q Developer Document**: https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/what-is.html

#### Amazon Bedrock
- Build with foundation models
- **Document**: https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html

#### Amazon SageMaker AI
- Build, train, and deploy machine learning models at scale
- **Document**: https://docs.aws.amazon.com/sagemaker/latest/dg/whatis.html

#### Amazon SageMaker Unified Studio
- It is a unified development experience that brings together AWS data, analytics, artificial intelligence (AI), and machine learning (ML) services.
- It provides a place to build, deploy, execute, and monitor end-to-end workflows from a single interface. 
- **Document**: https://docs.aws.amazon.com/sagemaker-unified-studio/latest/userguide/what-is-sagemaker-unified-studio.html

#### AWS App Studio 
- Fastest and easiest way to build enterprise-grade applications
- **Document**: https://docs.aws.amazon.com/appstudio/latest/userguide/welcome.html

#### Amazon Augmented AI
- Easily implement human review of ML predictions
- **Document**: https://docs.aws.amazon.com/sagemaker/latest/dg/a2i-use-augmented-ai-a2i-human-review-loops.html?icmpid=docs_a2i_lp

#### Amazon CodeGuru
- Find your most expensive lines of code
- **CodeGuru Security Document**: https://docs.aws.amazon.com/codeguru/latest/security-ug/what-is-codeguru-security.html
- **CodeGuru Profiler Document**: https://docs.aws.amazon.com/codeguru/latest/profiler-ug/what-is-codeguru-profiler.html
- **CodeGuru Reviewer Document**: https://docs.aws.amazon.com/codeguru/latest/reviewer-ug/welcome.html
- **Bugbust Document**: https://docs.aws.amazon.com/codeguru/latest/bugbust-ug/what-is-aws-bugbust.html

#### Amazon Comprehend
- Discover insights and relationships in text
- **Document**: https://docs.aws.amazon.com/comprehend/latest/dg/what-is.html

#### Amazon Comprehend Medical
- Extract health data
- **Document**: https://docs.aws.amazon.com/comprehend-medical/latest/dev/comprehendmedical-welcome.html

#### Amazon Fraud Detector
- Detect more online fraud faster
- **Document**: https://docs.aws.amazon.com/frauddetector/latest/ug/what-is-frauddetector.html

#### Amazon Kendra
- Reinvent enterprise search with ML
- It is a managed information retrieval and intelligent search service that uses natural language processing and advanced deep learning model.
- Unlike traditional keyword-based search, Amazon Kendra uses semantic and contextual similarity—and ranking capabilities—to decide whether a text chunk or document is relevant to a retrieval query.
- **Document**: https://docs.aws.amazon.com/kendra/latest/dg/what-is-kendra.html

#### Amazon Lex
- Build voice and text chatbots
- **Document**: https://docs.aws.amazon.com/lexv2/latest/dg/what-is.html

#### AWS HealthLake
- Make sense of health data
- **Document**: https://docs.aws.amazon.com/healthlake/latest/devguide/what-is.html

#### Amazon Personalize
- Build real-time recommendations into your applications
- **Document**: https://docs.aws.amazon.com/personalize/latest/dg/what-is-personalize.html

#### Amazon Polly
- Turn text into life-like speech
- **Document**: https://docs.aws.amazon.com/polly/latest/dg/what-is.html

#### Amazon Rekognition
- Analyze image and video
- **Document**: https://docs.aws.amazon.com/rekognition/latest/dg/what-is.html

#### Amazon Textract
- Extract text and data from **Document**s
- **Document**: https://docs.aws.amazon.com/textract/latest/dg/what-is.html

#### Amazon Translate
- Natural and fluent language translation
- **Document**: https://docs.aws.amazon.com/translate/latest/dg/what-is.html

#### Amazon Transcribe
- Automatic speech recognition
- **Document**: https://docs.aws.amazon.com/transcribe/latest/dg/what-is.html
