## Intro to Cloud Computing
Cloud computing is on-demand delivery of computing power and other IT resources through the internet with pay-as-you-go pricing, meaning you only pay for what you use.

Unlike cloud computing, traditional computing has a long procurement cycle, requires space, staff, physical security and capital expenses. 

Cloud computing models allow for more flexible software solutions. You can terminate unneeded resources on-demand and pay only for what you use. You can also scale resources up or down fairly easily.

### Cloud Service Models
There are 3 main CSMs. IaaS, PaaS, and SaaS.

**1. IaaS (Infrastructure as a Service):** The services in this category usually provide you with access to features such as networking, computers, and data storage space. This has the highest level of flexibility and control over the IT resources you paid for.

**2. PaaS (Platform as a Service):** There is less freedom over the hardware and OS, which gives you time to focus on deployment and management of applications.

**3. SaaS (Software as a Service):** With this, the service provider gives you the complete product, which means there is no need to think about how the infrastructure is managed, only the software given to you.

### Cloud Deployment Models
**1. Cloud:** This is fully developed and runs in the cloud. Some applications may have migrated from existing infrastructure to reap the benefits of cloud computing. Cloud-based apps can be built on low or high level infrastructure.

**2. Hybrid:** This connects applications between cloud-based resources and resources not on the cloud. This usually takes place between cloud and on-premises infrastructure.

**3. On-premises:** Basically a private cloud sometimes using virtualization and resource management tools.

## Advantages of Cloud Computing
1. Companies can trade capital expense (which is the money the company uses to acquire, maintain and upgrade physical hardware, whether its being used or not) for variable expense (expenses that can easily be altered or even avoided). In other words, you only pay for what is being used, not everything you acquired, saving money on technology.

2. You can benefit from massive economies of scale. You can gain lower variable cost because usage from thousands of customers is aggregated in the cloud. AWS achieves higher economies of scale which becomes lower pay-as-you-go prices for the customer.

3. Eliminate guessing about infrastruxture capacity. With cloud computing, you can as much or as little as needed, and scaling up or down is easier and faster.

4. With cloud computing, new IT resources can be acquired within minutes, reducing the time it takes to make these resources available to developers.

5. You can stop spending money on running and maintaining data centers. 

## Intro to AWS
AWS is a secure cloud plaform that offers a lot of global cloud-based services. You pay only for the services you use and how long you use them.

The services you choose depends on the goals of your business and tech requiremnts. Some AWS services include:

**1. Compute Services:**
* Amazon EC2
* AWS Lambda
* Amazon Elastic Beastalk
* Amazon EC2 Auto Scaling
* Amazon ECS, EKS and ECR
* AWS Fargate

**2. Storage Services:**
* Amazon S3
* Amzon S3 Glacier
* Amazon EFS
* Amazon EBS

**3. Management and Governance services**
* AWS Trusted Advisor
* AWS CloudWatch
* AWS CloudTrail
* AWS Well-Architected Tool
* AWS Auto Scaling
* AWS Command Line Interface
* AWS Config
* AWS Management Console
* AWS Organizations

There are 3 ways to interact with AWS:

**AWS Management Console:** A graphical interface with majority of the features offered by AWS.

**AWS Command Line Interface:** Provides utilities that can be launched using a command line script in Linux, Mac or Windows.

**Software Development Kits:** Provides packages used to access AWS in different programming languages. This is easy to use in existing applications and also allows you to create applications to deploy.

## AWS Cloud Adoption Framework
The AWS CAF provides guidance to help organizarions build a comprehensive approach to cloud computing across the organization to accelerate successful cloud computing. In order for an organization to successfully migrate to the cloud, 3 elements (ie. people, processes and technology) must be aligned. AWS consists of six perspectives:
* Business capabilities: Business, people and governance.
* Technical capabilities: Platform, security and operations.*

**Business Prespective:** Deals with IT finance, IT stategy, benefits realization and business risk management.

**People's Perspective:** Deals with resource management, incentive management, career mangement, training management and organizational change management.

**Governance Perspective:** Deals with Portfolio management, program and project management, business performance measurement and license management.

**Platform Perspective:** Deals with compute provisioning, network provisioning, storage provisioning, database provisioning, systems and solutions architecture and app development.

**Security Perspective:** Identity and access management, detective control, infrastructure security, data protection and incident response.

**Operations Perspective:** Service monitoring, app performance monitoring, resource inventory management, reportng and analysis and IT service catalog.

## Economics and Billing
There are 3 fundamental cost drivers with AWS;
* Compute: Charged by the hour usually and varies by instance type.
* Storage: Usually charged per GB.
* Data transfer: Outbound is charged but inbound isn't. Also usually charged by GB.

Reserved instances help you to save 75% over equivalent on-demand capacity. There are 3 options:
* All Upfront Reserved Instances
* Partial Upfront reserved instances
* No upfront reserved instances

As AWS grows, they focus on lowering the cost of doing business, which results in savings from economies of scale being passed to the user.
