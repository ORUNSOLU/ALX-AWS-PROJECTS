# ALX-AWS-PROJECTS
## This repo is my personal documentation and follow through on the ALX AWS Cloud computing course. After completion of these modules, I will take the AWS Solutions Architect Associate exam.
> Two modules per week.

You can also peek my acquired skill badged which I gained practicing various tasks on [Google Cloud Platform](https://www.cloudskillsboost.google/public_profiles/62b94d90-6d1a-4c6e-abfa-42d33d3778f8)


## Modules
- [x] Module 1 (Introduction to Cloud Architecting)
- [x] Module 2 (Introduction to AWS Cloud Architecting)
- [x] Module 3 (Creating a storage layer)
- [x] Module 4 (Creating a compute layer)
- [x] Module 5 (Creating a Database layer)
- [x] Module 6 (Creating a networking layer/environment)
- [x] Module 7 (Connecting networks)
- [x] Module 8 (Securing users and applications access)
- [x] Module 9 (Implementing Elasticity, High Availability and Monitoring)
- [x] Module 10 (Automating your Architecture)
- [x] Module 11 (Caching content)
- [x] Module 12 (Building Decoupled Architectures)
- [ ] Module 13 (Building Microservices and Serverless Architectures)
- [ ] Module 14 (Planning for Disaster)

---
# Summary of Lab Tasks

## Module 2
* Learnt about the AWS Well Architected Framework
* Learnt and understood best practices for building solutions on AWS
* Learnt about AWS Global Infrastructure

## Module 3
* Hosted a Static website using Amazon S3 and enabled access to the bucket
* Implemented a data lifecycle strategy in Amazon S3 & object versioning on the buckets
* Implemented a disaster recovery in Amazon S3

## Module 4
* Created an EFS file system and mounted it to an EC2 instance
* Deployed 2 apps on ec2 in different regions
* Connected to AWS Cloud9 IDE on an existing ec2 instance
* Analyzed the ec2 instance environment and confirmed server accessibility
* Installed web app on ec2 instance that also used AWS Systems Manager Parameter Store
* Tested and confirmed the web app
* created a second AMI and deploy web app to another region
* Examined and monitored the performance of the file system

## Module 5
* Created an RDS Database instance
* Exported data from MariaDB database by using mysqldump
* Connected a SQL client to an RDS database
* Migrated data from a MariaDB database that runs on an EC2 instance to an RDS database instance
* Configure a web application to use the new RDS database instance for data storage

## Module 6
* Created a VPC and an Internet Gateway, attached the IGW to the VPC
* Created a Public & Private Subnet, and an application server to test the VPC
* Created a VPC environment that enables secure connection to private resources
* Enabled private resources to connect to the internet
* Created an additional layer of security in VPC to control traffic to and from private resources

## Module 7
* Created a VPC peering connection
* Configured route tables to use the VPC peering connection

## Module 8
* Created IAM users & IAM groups, and associated IAM policies with the IAM groups
* Observed how limited access rights affect what resources IAM users can access & what actions they can take
* Configured AWS managed IAM policies to modify user access rights and observed the results
* Configured the IAM Policy Simulator to observe the scope of the access that is granted by different policies
* Accessed the IAM Access Advisor to observe what access rights different users are taking advantage of
* Created custom IAM policies by using the visual editor

## Module 9
* Created an Application Load Balancer & an AutoScaling Group
* Tested the an Application for High Availability through the Load Balancer
* Modified a network VPC to work across multiple Availability Zones
* Created a launch template
* Tested an application for load balancing and automatic scaling

## Module 10
* Deployed a VPC networking layer using AWS CloudFormation
* Deployed an Application layer using AWS CloudFormation that references the networking layer
* Explored templates with AWS CloudFormation Designer & deleted a stack with a deletion policy to observe it's behaviour
* Configured Git to invoke AWS CodePipeline, and to create or update stacks from templates that are stored in AWS CodeCommit
* Duplicated network and application resources to another AWS Region by using AWS CloudFormation

## Module 11
* Created multiple bit-rate versions of a given source media file using Amazon Elastic Transcoder
* COnfigured Amazon CloudFront to deliver the dynamic (multi bit-rate) stream created by Amazon Elastic Transcoder
* Learnt about Caching contents using CloudFront, Amazon DynamoDB Accelerator (DaX) and Elastic Cache (MemCached, Redis)

## Module 12
* Learnt about building Amazon SQS for building Microservice architectures (and use cases)
* Learnt about Amazon SNS, and use cases
* Learnt about Amazon Message Queue (MQ),and use cases
* Gained insights on demos and use case for each service type

## Module 13
* Learnt about ECS, Fargate, autoscaling groups, AWS Cloud Map, AWS App Mesh
* Triggered Lambda functions from Amazon S3 and Amazon DynamoDB
* Configure Amazon Simple Notification Service (Amazon SNS) to send notifications
* created a Lambda function within a VPC that connects to an Amazon RDS database with a sales data
* Created a Lambda function that generates and runs a sales report
* Migrated a monolithic Node.js application to run in a Docker container
* Refactored a Node.js application from a monolithic design to a microservices architecture
* Deployed a containerized Node.js microservices application to Amazon ECS