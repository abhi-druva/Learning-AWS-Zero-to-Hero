# Learning-AWS
Documentation of learning AWS from scratch.

## Day 1: Introduction to AWS

We learn what is private and public cloud. Why companies are moving to public cloud, what are the advantages of moving to cloud.

Also, we will be introduced to the basics of AWS, including the core services and their significance in DevOps practices. Finally learn how to set up an AWS account and navigate the AWS Management Console.

## Day 2: IAM (Identity and Access Management)

We will explore IAM, which is used for managing access to AWS resources. We will learn how to create IAM users, groups, and roles, and how to apply permissions and security best practices to ensure proper access control.

## Day 3: EC2 Instances

We will dive into EC2, which provides virtual servers in the cloud. We will learn how to launch EC2 instances, connect to them using SSH, and understand key concepts such as instance types, security groups, and key pairs.

**First AWS Project**: Deploy a simple web application(such as jenkins) on the ec2 instance and access the application from outside AWS.

## Day 4: AWS Networking (VPC)

We will explore AWS networking concepts, with a specific focus on VPC (Virtual Private Cloud). We will learn how to create and configure VPCs, subnets, and route tables, enabling us to design and manage the network infrastructure for our applications.

## Day 5: AWS Security

This day emphasizes security best practices in AWS. We will learn how to implement security measures such as security groups, network ACLs (Access Control Lists), and IAM policies to ensure the confidentiality, integrity, and availability of your AWS resources.

## Day 6: AWS Route 53

**Project:** Configure and manage a domain name using Route 53. We will register a domain, set up DNS records, and explore advanced features such as health checks, routing policies, and DNS-based failover.

## Day 7: Secure VPC Setup with EC2 Instances

**Project:**

- Design and configure a VPC:
    Create a VPC with custom IP ranges.
    Set up public and private subnets.
    Configure route tables and associate subnets.

- Implement network security:
    Set up network access control lists (ACLs) to control inbound and outbound traffic.
    Configure security groups for EC2 instances to allow specific ports and protocols.

- Provision EC2 instances:
    Launch EC2 instances in both the public and private subnets.
    Configure security groups for the instances to allow necessary traffic.
    Create and assign IAM roles to the instances with appropriate permissions.

- Networking and routing:
    Set up an internet gateway to allow internet access for instances in the public subnet.
    Configure NAT gateway or NAT instance to enable outbound internet access for instances in the private subnet.
    Create appropriate route tables and associate them with the subnets.

- SSH key pair and access control:
    Generate an SSH key pair and securely store the private key.
    Configure the instances to allow SSH access only with the generated key pair.
    Implement IAM policies and roles to control access and permissions to AWS resources.

- Test and validate the setup:
    SSH into the EC2 instances using the private key and verify connectivity.
    Test network connectivity between instances in different subnets.
    Validate security group rules and network ACL settings.

## Day 8: Amazon S3

This day focuses on Amazon S3, a scalable object storage service. We will learn how to create S3 buckets, upload and download objects, and organize data using S3 features like versioning, lifecycle policies, and access control.

## Day 9: AWS CLI

## Day 10: AWS CloudFormation

This day introduces Infrastructure as Code (IaC) using AWS CloudFormation. We will learn how to create CloudFormation templates to automate the provisioning of resources, manage stacks, and ensure consistent infrastructure across deployments.

**Project:** We will work on creating a CloudFormation template that provisions a fully configured application stack, including EC2 instances, networking components, and security groups.

## Day 11: AWS CodeCommit

This day focuses on AWS CodeCommit, a managed source control service. We will learn how to set up a Git repository in CodeCommit, collaborate with team members, and manage version control of your codebase.

**Project:** We will configure a CodeCommit repository for a team project, including setting up access control and collaboration workflows.

## Day 12: AWS CodePipeline

We will dive into AWS CodePipeline, a fully managed continuous delivery service. We will learn how to build end-to-end CI/CD pipelines by configuring source, build, and deployment stages, automating the entire software release process.

**Project:** We will create a CI/CD pipeline using CodePipeline for an application deployment, including source code integration, build, and automatic deployment to a target environment.

## Day 13: AWS CodeBuild

This day focuses on AWS CodeBuild, a fully managed build service. We will learn how to configure build projects in CodeBuild, define build specifications, and perform build and testing processes.

**Project:** We will configure and run CodeBuild for a project, including defining build specifications and integrating with other AWS services.

## Day 14: AWS CodeDeploy

We will explore AWS CodeDeploy, a service for automating application deployments to various compute environments. We will learn how to create deployment groups, configure deployment strategies, and perform automatic rollbacks if necessary.

**Project:** We will implement a Blue/Green deployment strategy for a sample application using CodeDeploy, ensuring zero-downtime deployments and easy rollback options.

## Day 15: AWS CloudWatch

This day focuses on monitoring AWS resources using AWS CloudWatch. We will learn how to create alarms, set up notifications, and collect metrics to gain insights into the health and performance of our applications and infrastructure.

**Project:** We will set up CloudWatch alarms for critical metrics of an application, define appropriate threshold conditions, and configure notification actions.

## Day 16: AWS Lambda

This day introduces serverless computing with AWS Lambda. We will learn how to create and deploy serverless functions, trigger them based on events, and leverage Lambda to build scalable and event-driven architectures.

## Day 17: AWS CloudWatch Events and EventBridge

This day focuses on AWS CloudWatch Events and EventBridge, services for event-driven architectures. We will learn how to create event rules, configure event targets, and build serverless event-driven workflows.

**Project:** We will build a serverless event-driven workflow using CloudWatch Events and EventBridge, demonstrating the integration and automation of different AWS services based on events.

## Day 18: AWS CloudFront

 We will learn about CloudFront service.

**Project:** We will configure a s3 bucket to host a static website and learn how to serve the requests to this website through CDN that is AWS Cloud Front.

## Day 19: AWS ECR (Elastic Container Registry)

We will explore AWS ECR, a fully managed container registry for storing and managing container images. We will learn how to push and pull Docker images to and from ECR, enabling seamless integration with ECS and other container services.

**Project:** We will build a CI/CD pipeline that automatically builds, pushes, and deploys Docker images to ECR, ensuring streamlined container image management.

## Day 20: AWS ECS (Elastic Container Service)

This day focuses on AWS ECS, a fully managed container orchestration service. We will learn how to run and manage containers using ECS, including creating task definitions, managing services, and scaling with auto-scaling capabilities.

**Project:** We will deploy a multi-container application using ECS, configure auto-scaling policies, and ensure high availability and efficient resource utilization.

## Day 21: AWS EKS (Elastic Kubernetes Service)

This day introduces AWS EKS, a fully managed Kubernetes service. We will learn how to deploy and manage Kubernetes clusters using EKS, including launching worker nodes, configuring networking, and deploying applications using Kubernetes manifests.

**Project:** We will deploy a sample application on EKS using Kubernetes manifests, demonstrating the capabilities of running containerized applications on a managed Kubernetes service.

## Day 22: AWS Systems Manager

This day focuses on AWS Secrets Manager, a service for storing and managing secrets such as database credentials, API keys, and other sensitive information. We will learn how to store, retrieve, and rotate secrets securely in your applications.

**Project:** We will configure Secrets Manager to store and manage secrets, integrate secret retrieval in an application, and implement secret rotation policies.

## Day 23: Create Infrastructure using Terraform

This day focusses on creating infrastructure using Terraform with real time example.

**Project:** We will create a VPC and deploy 2 applications in different availability zones. We will also create a load balancer to balance the load between the instances automatically.

## Day 24: AWS CloudTrail and Config

We will explore AWS CloudTrail and AWS Config, which provide auditing and compliance capabilities. We will learn how to track API calls using CloudTrail and ensure compliance with AWS Config rules.

**Project:** We will configure CloudTrail to log API activities and set up AWS Config rules to enforce compliance policies for your AWS resources.

## Day 25: AWS Elastic Load Balancer

We will explore AWS Elastic Load Balancer, a service for distributing incoming application traffic across multiple targets. We will learn how to configure and manage load balancers to ensure high availability, fault tolerance, and scalability.

**Project:** We will configure an Elastic Load Balancer for an application, define target groups, and observe the load balancing behavior across instances.

## Day 26: AWS Cloud Migration Strategies and Tools

This day focuses on learning how to migrate applications to AWS cloud. What are the most popular strategies and tools used to achieve the cloud migration.

## Day 30: AWS Project with RDS
