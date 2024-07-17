# Domain 1: AWS Cloud Practitioner Essentials (Modules 1-3)

## Question 1: What is Cloud Computing?
**Answer**: Cloud computing is the on-demand delivery of IT resources over the internet with pay-as-you-go pricing.

## Question 2: What are the three deployment models for cloud computing, their definitions, and uses?
**Answer**: The three deployment models for cloud computing are:
1. **Cloud**: Fully deployed in the cloud, all parts of the application run in the cloud.
2. **Hybrid**: Combines on-premises infrastructure or private cloud with public cloud.
3. **On-premises**: Resources are deployed in-house within an organization's own IT infrastructure.

## Question 3: What are the Benefits of cloud computing and their definitions?
**Answer**: The benefits of cloud computing include:
1. **Cost Savings**: Pay-as-you-go pricing.
2. **Scalability**: Scale resources up or down based on demand.
3. **Security**: Advanced security features and compliance with various standards.
4. **Speed and Agility**: Quickly deploy and iterate on applications.

## Question 4: What are the Amazon EC2 instance types and their definitions?
**Answer**: Amazon EC2 instance types include:
1. **General Purpose**: Balanced compute, memory, and networking resources.
2. **Compute Optimized**: High-performance processors for compute-intensive tasks.
3. **Memory Optimized**: Fast performance for memory-intensive applications.
4. **Storage Optimized**: High read/write access to large datasets.

## Question 5: What is a Load Balancer?
**Answer**: A load balancer distributes incoming application traffic across multiple targets, such as EC2 instances, to ensure no single instance bears too much load.

## Question 6: What is the primary purpose of AWS Regions in the global infrastructure?
**Answer**: AWS Regions allow users to deploy applications and services in different geographic areas to reduce latency and ensure compliance with data sovereignty regulations.

## Question 7: Describe the function of Amazon CloudFront in AWS's architecture.
**Answer**: Amazon CloudFront is a content delivery network (CDN) that delivers data, videos, applications, and APIs to users with low latency and high transfer speeds.

## Question 8: How do AWS Edge locations enhance the performance of Amazon CloudFront?
**Answer**: AWS Edge locations cache content closer to the end-users, reducing latency and improving load times for content delivery.

## Question 9: Explain how Amazon Route 53 integrates with AWS Edge locations to enhance user experiences.
**Answer**: Amazon Route 53 uses AWS Edge locations to route end-user requests to the nearest data center, enhancing performance and reliability.

## Question 10: What are the advantages of using AWS Outposts for local data processing needs?
**Answer**: AWS Outposts bring AWS infrastructure and services to on-premises locations for low-latency, local data processing while maintaining consistent operations with AWS cloud.

## Question 11: How are AWS Lambda and AWS Outposts different in what they offer for cloud computing?
**Answer**: AWS Lambda is a serverless computing service that runs code in response to events, while AWS Outposts extends AWS infrastructure to on-premises environments for local data processing.

## Question 12: What is high availability?
**Answer**: High availability refers to systems that are continuously operational with minimal downtime.

## Question 13: What are the benefits of AWS having a global infrastructure with multiple regions?
**Answer**: The benefits include reduced latency, improved disaster recovery, and compliance with data sovereignty regulations.

## Question 14: What is an AWS Region?
**Answer**: An AWS Region is a physical location around the world where AWS clusters data centers.

## Question 15: Why is data sovereignty important in AWS Regions?
**Answer**: Data sovereignty ensures that data is subject to the laws and regulations of the country where it is physically located.

## Question 16: How do AWS Regions enhance disaster recovery capabilities?
**Answer**: AWS Regions allow for data replication and backup across different geographic areas, improving disaster recovery options.

## Question 17: What are the four main factors to consider when choosing an AWS Region?
**Answer**: Factors to consider include compliance, proximity to customers, available services, and pricing.

## Question 18: What is an AWS Availability Zone?
**Answer**: An AWS Availability Zone is one or more discrete data centers with redundant power, networking, and connectivity within an AWS Region.

## Question 19: What is the purpose of having multiple Availability Zones within an AWS Region?
**Answer**: Multiple Availability Zones provide redundancy and high availability, ensuring that applications remain available even if one data center fails.

## Question 20: How does AWS ensure low latency communication between Availability Zones?
**Answer**: AWS ensures low latency communication through high-speed fiber connections between Availability Zones.

## Question 21: Why is it important to run EC2 instances across multiple AZs?
**Answer**: Running EC2 instances across multiple AZs improves fault tolerance and high availability.

## Question 22: How do regional AWS services enhance high availability?
**Answer**: Regional AWS services distribute workloads across multiple AZs, providing high availability and fault tolerance.

## Question 23: What is the purpose of Amazon CloudFront?
**Answer**: Amazon CloudFront delivers content with low latency and high transfer speeds by caching it at edge locations worldwide.

## Question 24: What are edge locations in AWS?
**Answer**: Edge locations are data centers that cache copies of content closer to end-users to reduce latency.

## Question 25: What is AWS Outposts?
**Answer**: AWS Outposts bring AWS infrastructure and services to on-premises locations for low-latency, local data processing.

## Question 26: How do Availability Zones within AWS Regions contribute to disaster recovery and high availability?
**Answer**: Availability Zones ensure redundancy and isolation, allowing applications to remain operational in case of an outage in one zone.

## Question 27: How do AWS Edge locations and Amazon CloudFront improve content delivery?
**Answer**: AWS Edge locations cache content closer to users, while Amazon CloudFront optimizes delivery routes, reducing latency and improving load times.

## Question 28: What is an API in the context of AWS?
**Answer**: An API (Application Programming Interface) allows software applications to interact with AWS services programmatically.

## Question 29: What is the primary method of interacting with AWS services?
**Answer**: The primary methods of interacting with AWS services are the AWS Management Console, AWS CLI (Command Line Interface), and AWS SDKs (Software Development Kits).

## Question 30: Why is automation important in cloud deployment?
**Answer**: Automation reduces manual intervention, increases consistency, and speeds up deployment processes.

## Question 31: What is the primary advantage of using AWS Elastic Beanstalk over manual methods like the AWS Management Console?
**Answer**: AWS Elastic Beanstalk automates deployment, scaling, and management of applications, allowing developers to focus on writing code instead of managing infrastructure.

## Question 32: What is AWS Elastic Beanstalk used for?
**Answer**: AWS Elastic Beanstalk is used for deploying and managing applications in the cloud without worrying about the underlying infrastructure.

## Question 33: How does AWS CloudFormation help in managing AWS resources?
**Answer**: AWS CloudFormation allows users to define infrastructure as code, automating the provisioning and updating of AWS resources in a repeatable and consistent manner.

## Question 34: What are the main components of AWS Global Infrastructure?
**Answer**: The main components include AWS Regions, Availability Zones, and Edge locations.

## Question 35: Which AWS services automatically run across multiple Availability Zones?
**Answer**: Services like Amazon RDS (Relational Database Service) and Amazon S3 (Simple Storage Service) run across multiple Availability Zones by default.

## Question 36: What is the recommended best practice for deploying infrastructure in AWS?
**Answer**: The best practice is to deploy infrastructure across multiple Availability Zones to ensure high availability and fault tolerance.

# Domain 1: AWS Educate - Getting Started with Compute Lab

## Question 1: What is Amazon EC2?
**Answer**: Amazon EC2 (Elastic Compute Cloud) provides scalable computing capacity in the AWS cloud, allowing users to run virtual servers.

## Question 2: What is Amazon EC2 and its primary benefits?
**Answer**: Amazon EC2 offers resizable compute capacity, flexibility, and cost-effective solutions for running applications in the cloud.

## Question 3: What is a Security Group in EC2?
**Answer**: A security group acts as a virtual firewall for EC2 instances, controlling inbound and outbound traffic based on defined rules.

## Question 4: What are the four main purchasing options for EC2 instances, and what are their key characteristics?
**Answer**: The four main purchasing options are:
1. **On-Demand**: Pay for instances by the second with no long-term commitments.
2. **Reserved**: Significant discount for committing to use EC2 over a 1- or 3-year term.
3. **Spot**: Bid for unused EC2 capacity at a potentially lower cost.
4. **Dedicated Hosts**: Physical servers dedicated for your use.

## Question 5: How does EC2 pricing work?
**Answer**: EC2 pricing is based on factors such as instance type, region, operating system, and purchasing option.

## Question 6: What is an Amazon Machine Image (AMI)?
**Answer**: An AMI is a pre-configured template for an EC2 instance that includes the operating system, application server, and
