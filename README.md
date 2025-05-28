# AWS Training
&nbsp;
&nbsp;

## FUNDAMENTALS OF AWS
- What is virtualization?
- Difference between physical and virtual servers?
- What is cloud?
- Benefits of cloud
- What is AWS, Azure, GCP and other cloud providers?
- How to create a free tier account in AWS?
- What are the services in AWS?
- How to create EC2 and work?
&nbsp;
&nbsp;

## INFRASTRUCTURE AND SYSTEM OPS
- What is Infrastructure?
- What is IAC and IAAS?
- What are the tools to create Infrastructure?
- What is deployment? What is Monitoring?
- Monitoring tools
&nbsp;
&nbsp;

## DATA ENGINEERING, DEVOPS AND ADMIN
- What is Data engineering?
- What are the advantages? And how to manage?
- What is DevOps? Why DevOps?
- SDLC
- DevOps Life Cycle
- DevOps tools: Git, Maven, Jenkins, Docker, Kubernetes, Terraform, Ansible, Grafana, Prometheus
- What is version control system?
- How to create GitHub account?
- How to create GitHub repository?
- How to install git in Ubuntu Linux server (EC2)?
- How to work with git repositories?
- What is branching and merging?
- What is the build process?
- Working with JAR and WAR files
- How to build the real Java code by using Maven?
- How to deploy the build in test environment?
- What is CICD?
- Jenkins installation
- How to automate the process by using Jenkins (CICD)?
- Jenkins file (Declarative syntax) and plugins
- What is Master-Slave concept?
- Jenkins file
- How to create EC2 instance by using Terraform?
- How to create a Docker container and image?
- How to deploy real-world application in Kubernetes cluster?
&nbsp;
&nbsp;

## CONTAINERIZATION, NODEJS ON AWS
- What is the difference between virtual servers and containers?
- What is containerization?
- Docker installation
- Creating the containers by using Docker
- Docker commands
- Docker architecture
- Docker image concept
- How to create the Docker image?
- How to push Docker image into Docker Hub?
- How to create account in Docker Hub?
- How to containerize the real-world application?
- Docker Volumes concept
&nbsp;
&nbsp;

### Introduction to Node.js
- What is Node.js?
- Why use Node.js? (Non-blocking, event-driven)
- Use cases (APIs, tools, scripting, DevOps automation)
&nbsp;
&nbsp;

### Setting Up Environment
- Install Node.js & npm
- Introduction to REPL and executing .js files
&nbsp;
&nbsp;

### Core Concepts
- Modules (Built-in: fs, path, http)
- Creating & using custom modules
- require() and module.exports
&nbsp;
&nbsp;

### Creating a Simple Web Server
- Using http module
- Handling basic requests & responses
- Routing basics (GET, POST)
&nbsp;
&nbsp;

### Working with npm
- Installing external packages (express, etc.)
- Understanding package.json
- Creating a simple Express app
&nbsp;
&nbsp;

### Hands-On / Demo
- Build a simple REST API using Express
- Example: CRUD for a "To-Do" or "Users" list
- Q&A and Wrap-Up
&nbsp;
&nbsp;

## ARCHITECTURE & SECURITY
### Introduction & Importance
- What is software/system architecture?
- Why security is critical in modern architecture?
- Real-world failures due to poor architecture/security
&nbsp;
&nbsp;

### Basic Architecture Concepts
- Monolithic vs Microservices vs Serverless
- 3-tier and N-tier architecture
- Common components: API gateway, load balancer, database, cache, etc.
- Deployment models: On-prem, Cloud, Hybrid
&nbsp;
&nbsp;

### Security Fundamentals
- CIA Triad (Confidentiality, Integrity, Availability)
- Authentication vs Authorization
- Common threats: OWASP Top 10 overview
- Secure coding basics
&nbsp;
&nbsp;

### Security in Architecture
- How to design secure systems:
  - Network security (VPCs, firewalls)
  - Data security (encryption at rest/in transit)
  - Identity and access (IAM roles, RBAC)
  - API security (tokens, rate limiting, HTTPS)
  - Logging & monitoring
&nbsp;
&nbsp;

### Case Study or Demo
- Simple architecture diagram with security layers
- Walkthrough of secure API flow or login process
- OR quick cloud architecture (AWS/Azure) with IAM and security groups


# AWS Training
&nbsp;
&nbsp;

## Table of Contents
- [Fundamentals of AWS](#fundamentals-of-aws)
  - [What is Virtualization?](#what-is-virtualization)
  - [Difference Between Physical and Virtual Servers](#difference-between-physical-and-virtual-servers)
  - [What is Cloud?](#what-is-cloud)
  - [Benefits of Cloud](#benefits-of-cloud)
  - [What is AWS, Azure, GCP, and Other Cloud Providers?](#what-is-aws-azure-gcp-and-other-cloud-providers)
  - [How to Create a Free Tier Account in AWS?](#how-to-create-a-free-tier-account-in-aws)
  - [What are the Services in AWS?](#what-are-the-services-in-aws)
  - [How to Create EC2 and Work?](#how-to-create-ec2-and-work)
- [Infrastructure and System Ops](#infrastructure-and-system-ops)
  - [What is Infrastructure?](#what-is-infrastructure)
  - [What is IAC and IAAS?](#what-is-iac-and-iaas)
  - [What are the Tools to Create Infrastructure?](#what-are-the-tools-to-create-infrastructure)
  - [What is Deployment? What is Monitoring?](#what-is-deployment-what-is-monitoring)
  - [Monitoring Tools](#monitoring-tools)
- [Terraform](#terraform)
  - [Terraform Commands](#terraform-commands)
- [Git](#git)
  - [Key Concepts](#key-concepts)
  - [Git Commands](#git-commands)
- [Data Engineering Fundamentals](#data-engineering-fundamentals)
  - [What is Data Engineering?](#what-is-data-engineering)
  - [Advantages and Management](#advantages-and-management)
  - [Management Best Practices](#management-best-practices)
- [DevOps Overview](#devops-overview)
  - [What is DevOps?](#what-is-devops)
  - [Why DevOps?](#why-devops)
  - [Development Lifecycle](#development-lifecycle)
- [DevOps Tools Installation & Setup](#devops-tools-installation--setup)
  - [Essential DevOps Tools](#essential-devops-tools)
  - [AWS CLI Installation](#aws-cli-installation)
  - [Terraform Installation](#terraform-installation)
  - [Git Installation](#git-installation)
- [Version Control with Git](#version-control-with-git)
  - [What is Version Control System?](#what-is-version-control-system)
  - [GitHub Account Setup](#github-account-setup)
  - [Creating GitHub Repository](#creating-github-repository)
  - [Git Repository Operations](#git-repository-operations)
  - [Branching and Merging](#branching-and-merging)
- [Build Process with Maven](#build-process-with-maven)
  - [Maven Installation](#maven-installation)
  - [Working with JAR and WAR Files](#working-with-jar-and-war-files)
  - [Building Java Code with Maven](#building-java-code-with-maven)
- [Deployment Process](#deployment-process)
  - [Test Environment Setup](#test-environment-setup)
  - [Tomcat Installation and Setup](#tomcat-installation-and-setup)
  - [SSH Key Setup for Secure File Transfer](#ssh-key-setup-for-secure-file-transfer)
  - [Deployment Process (Your Workflow)](#deployment-process-your-workflow)
  - [On Test Environment](#on-test-environment)
  - [Deployment Verification](#deployment-verification)
- [Jenkins Installation and Setup](#jenkins-installation-and-setup)
  - [Prerequisites Setup](#prerequisites-setup)
  - [Tomcat Installation (Jenkins Container)](#tomcat-installation-jenkins-container)
  - [Jenkins WAR File Installation](#jenkins-war-file-installation)
  - [Starting Jenkins Server](#starting-jenkins-server)
  - [Initial Jenkins Setup](#initial-jenkins-setup)
  - [Application Configuration Steps](#application-configuration-steps)
  - [Setting Up Poll SCM in Jenkins](#setting-up-poll-scm-in-jenkins)
  - [Setting Up Git WebHooks in Jenkins](#setting-up-git-webhooks-in-jenkins)
&nbsp;
&nbsp;

## FUNDAMENTALS OF AWS
&nbsp;
&nbsp;

### What is Virtualization?
Virtualization is the process of creating a virtual version of a physical resource, such as a server, storage device, or network. It allows multiple virtual instances to run on a single physical machine, optimizing resource utilization and providing flexibility in managing workloads.
&nbsp;
&nbsp;

### Difference Between Physical and Virtual Servers
- **Physical Servers**: Dedicated hardware machines that run an operating system and applications. They require physical space, power, and cooling, and are typically more expensive to maintain.
- **Virtual Servers**: Software-based instances that run on a physical server using virtualization technology. They share the underlying hardware resources and can be easily created, modified, or deleted, offering greater flexibility and cost efficiency.
&nbsp;
&nbsp;

### What is Cloud?
Cloud computing is the delivery of computing services (such as servers, storage, databases, networking, software, and analytics) over the internet ("the cloud"). It allows users to access and use resources on-demand without the need for physical infrastructure.
&nbsp;
&nbsp;

### Benefits of Cloud
- **Cost Efficiency**: Reduces capital expenses by eliminating the need for physical hardware.
- **Scalability**: Easily scale resources up or down based on demand.
- **Flexibility**: Access resources from anywhere with an internet connection.
- **Disaster Recovery**: Provides backup and recovery solutions to protect data.
- **Automatic Updates**: Cloud providers manage software updates and maintenance.
&nbsp;
&nbsp;

### What is AWS, Azure, GCP, and Other Cloud Providers?
- **AWS (Amazon Web Services)**: A comprehensive cloud platform offering a wide range of services, including computing power, storage, and databases.
- **Azure**: Microsoft’s cloud computing platform that provides services for building, deploying, and managing applications through Microsoft-managed data centers.
- **GCP (Google Cloud Platform)**: Google’s suite of cloud computing services that runs on the same infrastructure that Google uses internally for its end-user products.
- **Other Providers**: Notable cloud providers include IBM Cloud, Oracle Cloud, DigitalOcean, and Alibaba Cloud.
&nbsp;
&nbsp;

### How to Create a Free Tier Account in AWS?
1. Go to the AWS Free Tier page.
2. Click on "Create a Free Account."
3. Provide your email address, password, and AWS account name.
4. Enter your contact information and payment details (you won’t be charged for free tier usage).
5. Verify your identity via phone.
6. Choose a support plan (Basic is free).
7. Complete the registration process.
&nbsp;
&nbsp;

### What are the Services in AWS?
AWS offers a wide range of services, including:
- **Compute**: EC2, Lambda, Elastic Beanstalk
- **Storage**: S3, EBS, Glacier
- **Databases**: RDS, DynamoDB, Redshift
- **Networking**: VPC, Route 53, CloudFront
- **Machine Learning**: SageMaker, Rekognition
- **Security**: IAM, KMS, Shield
&nbsp;
&nbsp;

### How to Create EC2 and Work?
1. Log in to the AWS Management Console.
2. Navigate to the EC2 Dashboard.
3. Click on "Launch Instance."
4. Choose an Amazon Machine Image (AMI).
5. Select an instance type.
6. Configure instance details (network, IAM role, etc.).
7. Add storage and tags as needed.
8. Configure security group settings (firewall rules).
9. Review and launch the instance.
10. Connect to the instance using SSH (for Linux) or RDP (for Windows).
&nbsp;
&nbsp;

## INFRASTRUCTURE AND SYSTEM OPS
&nbsp;
&nbsp;

### What is Infrastructure?
Infrastructure refers to the underlying physical and virtual resources that support the operation of IT services and applications. This includes servers, storage, networking, and data centers.
&nbsp;
&nbsp;

### What is IAC and IAAS?
- **IAC (Infrastructure as Code)**: A practice that allows infrastructure to be provisioned and managed using code and automation tools, enabling version control and repeatability.
- **IAAS (Infrastructure as a Service)**: A cloud computing model that provides virtualized computing resources over the internet. Users can rent virtual machines, storage, and networks on a pay-as-you-go basis.
&nbsp;
&nbsp;

### What are the Tools to Create Infrastructure?
Common tools for creating and managing infrastructure include:
- **Terraform**: An open-source tool for building, changing, and versioning infrastructure safely and efficiently.
- **AWS CloudFormation**: A service that allows you to define and provision AWS infrastructure using templates.
- **Ansible**: An automation tool for configuration management and application deployment.
- **Puppet and Chef**: Tools for automating the management of infrastructure.
&nbsp;
&nbsp;

### What is Deployment? What is Monitoring?
- **Deployment**: The process of making an application or service available for use. This can involve installing software, configuring settings, and ensuring that the application is running correctly.
- **Monitoring**: The practice of continuously observing the performance and health of applications and infrastructure to ensure they are functioning as expected. This includes tracking metrics, logs, and alerts.
&nbsp;
&nbsp;

### Monitoring Tools
Common monitoring tools include:
- **Amazon CloudWatch**: A monitoring service for AWS resources and applications.
- **Prometheus**: An open-source monitoring and alerting toolkit designed for reliability and scalability.
- **Grafana**: A visualization tool that integrates with various data sources to create dashboards for monitoring.
- **Nagios**: An open-source monitoring system that enables monitoring of systems, networks, and infrastructure.
&nbsp;
&nbsp;

## Terraform
&nbsp;
&nbsp;

Terraform is an open-source, Infrastructure as Code (IaC) tool created by HashiCorp that allows users to define and provision infrastructure as code. It enables developers to manage infrastructure across various platforms, including public clouds like AWS, Azure, and Google Cloud, as well as on-premises environments. Terraform uses a declarative approach, allowing users to define the desired state of their infrastructure, and then Terraform automatically manages the provisioning and updates to achieve that state.
&nbsp;
&nbsp;

### Terraform Commands
1. `terraform init`: Initializes a new or existing Terraform configuration. This command downloads the necessary provider plugins and sets up the backend for state management.
2. `terraform plan`: Creates an execution plan, showing what actions Terraform will take to change the current infrastructure to match the desired state defined in the configuration files. It does not make any changes.
3. `terraform apply`: Applies the changes required to reach the desired state of the configuration. This command will prompt for confirmation before making any changes unless the `-auto-approve` flag is used.
4. `terraform destroy`: Destroys the infrastructure managed by Terraform, removing all resources defined in the configuration files. This command will also prompt for confirmation before proceeding.
5. `terraform validate`: Validates the configuration files for syntax errors and checks whether the configuration is valid.
6. `terraform fmt`: Formats Terraform configuration files to a canonical format and style, making them easier to read and maintain.
7. `terraform show`: Displays the current state or a specific resource in a human-readable format. It can also be used to show the output of a plan.
8. `terraform output`: Displays the output values defined in the Terraform configuration. This is useful for retrieving information about resources created by Terraform.
9. `terraform state`: Manages the Terraform state file. This command can be used to inspect, list, or modify the state file directly.
10. `terraform import`: Imports existing infrastructure into Terraform management. This allows you to bring resources that were created outside of Terraform under its control.
11. `terraform workspace`: Manages workspaces, which allow you to create and manage multiple states for the same configuration. This is useful for managing different environments (e.g., development, staging, production).
12. `terraform providers`: Displays the providers required by the configuration and their versions.
&nbsp;
&nbsp;

## Git
&nbsp;
&nbsp;

Git is a distributed version control system that allows multiple developers to work on a project simultaneously while keeping track of changes made to files. It helps in managing source code history, collaboration, and versioning.
&nbsp;
&nbsp;

### Key Concepts
- **Repository (Repo)**: A directory that contains your project files and the entire history of changes made to those files. It can be local (on your machine) or remote (on a server like GitHub).
- **Commit**: A snapshot of changes made to the files in the repository. Each commit has a unique identifier (hash) and a message describing the changes.
- **Branch**: A separate line of development in a repository. The default branch is usually called main or master. Branches allow you to work on features or fixes without affecting the main codebase.
- **Merge**: The process of integrating changes from one branch into another. This is often done to combine feature branches back into the main branch.
- **Clone**: Creating a local copy of a remote repository.
- **Pull**: Fetching changes from a remote repository and merging them into your local branch.
- **Push**: Sending your local commits to a remote repository.
&nbsp;
&nbsp;

### Git Commands
1. `git init`: Initializes a new Git repository in the current directory.
2. `git clone <repository-url>`: Creates a local copy of a remote repository.
3. `git status`: Displays the current status of the working directory, including staged, unstaged, and untracked files.
4. `git add <file>`: Stages changes to a specific file for the next commit. Use `git add .` to stage all changes.
5. `git commit -m "commit message"`: Commits the staged changes to the repository with a descriptive message.
6. `git log`: Displays the commit history for the repository.
7. `git branch`: Lists all branches in the repository. The current branch is highlighted with an asterisk.
8. `git checkout <branch-name>`: Switches to a different branch.
9. `git merge <branch-name>`: Merges changes from the specified branch into the current branch.
10. `git pull`: Fetches changes from the remote repository and merges them into the current branch.
11. `git push`: Pushes local commits to the remote repository.
12. `git remote -v`: Lists the remote repositories associated with the local repository.
13. `git stash`: Temporarily saves changes that are not ready to be committed, allowing you to switch branches or pull changes without losing your work.
14. `git stash pop`: Restores the most recently stashed changes.
&nbsp;
&nbsp;

## Data Engineering Fundamentals
&nbsp;
&nbsp;

### What is Data Engineering?
Data Engineering is the practice of designing, building, and maintaining systems that collect, store, and analyze data at scale. It involves creating data pipelines, managing data infrastructure, and ensuring data quality and accessibility.
&nbsp;
&nbsp;

### Advantages and Management
- **Scalability**: Handle large volumes of data efficiently.
- **Automation**: Reduce manual processes through automated pipelines.
- **Data Quality**: Ensure clean, reliable data for analytics.
- **Cost Optimization**: Efficient resource utilization.
- **Real-time Processing**: Enable streaming data analysis.
&nbsp;
&nbsp;

### Management Best Practices
- Implement monitoring and alerting.
- Use version control for data pipeline code.
- Establish data governance policies.
- Regular backup and disaster recovery planning.
&nbsp;
&nbsp;

## DevOps Overview
&nbsp;
&nbsp;

### What is DevOps?
DevOps is a cultural and technical movement that emphasizes collaboration between Development and Operations teams to deliver software faster and more reliably.
&nbsp;
&nbsp;

### Why DevOps?
- **Faster Time to Market**: Accelerated development and deployment.
- **Improved Quality**: Continuous testing and integration.
- **Better Collaboration**: Breaking down silos between teams.
- **Increased Efficiency**: Automation of repetitive tasks.
- **Enhanced Reliability**: Consistent and predictable deployments.
&nbsp;
&nbsp;

### Development Lifecycle
#### SDLC (Software Development Life Cycle)
1. Planning: Requirements gathering and project planning.
2. Analysis: System analysis and design.
3. Design: Architecture and component design.
4. Implementation: Code development.
5. Testing: Quality assurance and testing.
6. Deployment: Production release.
7. Maintenance: Ongoing support and updates.
&nbsp;
&nbsp;

#### DevOps Life Cycle
1. Plan: Project planning and requirement analysis.
2. Code: Development and version control.
3. Build: Compilation and packaging.
4. Test: Automated testing and quality checks.
5. Release: Deployment preparation.
6. Deploy: Production deployment.
7. Operate: Monitoring and maintenance.
8. Monitor: Performance tracking and feedback.
&nbsp;
&nbsp;

## DevOps Tools Installation & Setup
&nbsp;
&nbsp;

### Essential DevOps Tools
- **Git**: Version control system.
- **Maven**: Build automation tool for Java.
- **Jenkins**: Continuous Integration/Continuous Deployment.
- **Docker**: Containerization platform.
- **Kubernetes**: Container orchestration.
- **Terraform**: Infrastructure as Code.
- **Ansible**: Configuration management.
- **Grafana & Prometheus**: Monitoring and alerting.
&nbsp;
&nbsp;

### AWS CLI Installation
```bash
# Download AWS CLI v2
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
&nbsp;
&nbsp;

# Install unzip if not available
sudo apt-get update
sudo apt-get install unzip
&nbsp;
&nbsp;

# Extract and install AWS CLI
unzip awscliv2.zip
sudo ./aws/install
&nbsp;
&nbsp;

# Verify installation
aws --version
&nbsp;
&nbsp;

# Configure AWS CLI
aws configure
# Enter your Access Key ID, Secret Access Key, Default region, and output format
