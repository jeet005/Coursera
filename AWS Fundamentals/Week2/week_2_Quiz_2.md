#### Q1. Which information is needed to create a virtual private cloud (VPC)?

- [ ] The Availability Zone that the VPC will reside in.
- [ ] The subnet that the VPC will reside in.
- [x] The AWS Region that the VPC will reside in.
- [ ] The group of subnets that the VPC will reside in.

Correct  
When a solutions architect creates a VPC, they need to specify the AWS Region that it will reside in, the IP range for the VPC, and the name of the VPC. For more information, see the Introduction to Amazon VPC video.

#### Q2. Which of the following can a route table be attached to?

- [ ] AWS Accounts
- [ ] Availability Zone
- [x] Subnets
- [ ] Regions

Correct  
A route table contains a set of rules (which are called routes) that determine where network traffic from a subnet or gateway is directed. Each subnet in a virtual private cloud (VPC) must be associated with a particular route table. For more information, see the Amazon VPC Routing video.

#### Q3. A company wants to allow resources in a public subnet to communicate with the internet. Which of the following must the company do to meet this requirement?

- [ ] Create a route to a private subnet
- [x] Attach an internet gateway to their VPC
- [x] Create a route in a route table to the internet gateway
- [ ] A and B
- [ ] B and C

Correct  
Unlike a modem at home, which can go down or go offline, an internet gateway is highly available and scalable. After the company creates an internet gateway, they then need to attach it to a virtual private cloud (VPC) and create a route table to route network traffic through the internet gateway. For more information, see the Introduction to Amazon VPC reading.

#### Q4. What is the compute as a service (CaaS) model?

- [ ] The CaaS model requires that users purchase virtual machines and manually provision servers to run a workload.
- [x] The CaaS model offers computing resources (such as virtual machines that run on servers in data centers) on demand, by using virtual services.
- [ ] The CaaS model offers large discounts for computing resources. However, users must run the workload from the server that is stored on-premises.
- [ ] The CaaS model delivers cloud-based applications to users across the globe, over the internet.

Correct  
The CaaS model provides virtual computing resources on demand. For more information, see the Compute as a Service on AWS video.

#### Q5. Which statement about the default settings of a security group is TRUE?

- [ ] Allows all inbound traffic and blocks all outbound traffic by default.
- [x] Blocks all inbound traffic and allows all outbound traffic by default.
- [ ] Allows all inbound and outbound traffic by default.
- [ ] Blocks all inbound and outbound traffic by default.

Correct  
Security groups control the traffic that is allowed to reach and leave the resources that are associated with the security group. By default, security groups block all incoming traffic, and allow outbound traffic. For more information, see the Secure Your Network with Amazon VPC Security video.

#### Q6. What does an Amazon Elastic Compute Cloud (Amazon EC2) instance type indicate?

- [x] Instance family and instance size
- [ ] Instance placement and instance size
- [ ] Instance tenancy and instance billing
- [ ] Instance Amazon Machine Image (AMI) and networking speed

Correct  
Instance types are named based on instance generation, family, additional capabilities, and size. For more information, see the Introduction to Amazon EC2 video.

#### Q7. What is the difference between using AWS Fargate or Amazon Elastic Compute Cloud (Amazon EC2) as the compute platform for Amazon Elastic Container Service (Amazon ECS)?

- [x] With AWS Fargate, AWS manages and provisions the underlying infrastructure for hosting containers.
- [ ] With Amazon ECS on Amazon EC2, AWS manages and provisions the underlying EC2 instance for containers.
- [ ] With AWS Fargate, users need to manage cluster capacity and scaling.
- [ ] With Amazon ECS on Amazon EC2, users need to upload only the source code. Amazon ECS takes care of the rest.

Correct  
With Fargate, users don’t need to provision, configure, or scale clusters of virtual machines to run containers. For more information, see Container Services on AWS.

#### Q8. Which statement about serverless is TRUE?

- [ ] Users must provision and manage servers.
- [ ] Users must manually scale serverless resources.
- [x] Users do not pay for idle resources.
- [ ] Users must manage availability and fault tolerance.

Correct  
Serverless architectures only incur a charge when they are in use and resources are being consumed. For more information, see the What is Serverless video.

#### Q9. True or False: AWS Lambda is always the best solution when running applications on AWS.

- [ ] True
- [x] False

Correct  
AWS Lambda is a good solution for running on-demand workloads with runtimes of under 15 minutes, without needing to provision and manage servers. However, it does not fit all use cases. For more information, see the Choose the Right Compute Service video.

#### Q10. Which compute service does Amazon Elastic Compute Cloud (Amazon EC2) provide?

- [ ] Container services
- [ ] Serverless
- [x] Virtual machines (VMs)
- [ ] Analytics

Correct  
Amazon EC2 is a web service that provides secure and resizable compute capacity in the cloud. For more information, see Reading: Compute as a Service on AWS.

#### Q11. Which stage of the instance lifecycle is an instance in when the account starts to accumulate charges?

- [ ] When an instance is in a pending stage
- [x] When an instance is in a running stage
- [ ] When an instance is stopped
- [ ] When an instance is terminated

Correct  
Users start accumulating charges for instance usage when their instance is running. For more information, see Amazon EC2 Instance Lifecycle.

#### Q12. Which component of the c5.4xlarge instance determines the instance family and generation number?

- [ ] 4x
- [ ] Large
- [ ] 4xlarge
- [x] c5

Correct  
The c5 determines that this instance is a compute-optimized instance that belongs to the C family with the fifth-generation number. For more information, see Reading: Amazon EC2 Instance Lifecycle.

#### Q13. Which container runtime can be used to host a container on an Amazon Elastic Compute Cloud (Amazon EC2) instance?

- [x] Docker
- [ ] Container
- [ ] Amazon Simple Storage Service (Amazon S3)
- [ ] Amazon EC2

Correct  
A container is a standardized unit that packages code and all of its dependencies. For more information about the correct answer, see Reading: Container Services on AWS.

#### Q14. What is an example of an event that invokes an AWS Lambda function?

- [ ] An AWS API call that is made by an AWS Identity and Access Management (IAM) role
- [x] An upload of a file to the Amazon Simple Storage Service (Amazon S3) source bucket
- [ ] An incoming HTTP request to a website that is hosted on Amazon Elastic Compute Cloud (Amazon EC2)
- [ ] A simple WordPress website that has no API integration

Correct  
An upload of a file to the S3 source bucket can invoke a Lambda function. For more information, see Introduction to AWS Lambda.

#### Q15. True or False: With serverless, users do not need to provision and manage servers.

- [x] True
- [ ] False

Correct  
A serverless architecture is a way to build and run applications and services without needing to manage infrastructure. For more information, see Reading: Serverless and AWS Lambda.

#### Q16. True or False: All AWS services require users to configure a virtual private cloud (VPC).

- [ ] True
- [x] False

Correct  
With serverless services, AWS does not require a VPC for networking purposes. For more information, see Networking on AWS.

#### Q17. An engineer is working with networks in the AWS Cloud. What should the engineer use to configure the size of their network?

- [x] Classless Inter-Domain Routing (CIDR) notation
- [ ] IPv6 notation
- [ ] IPv4 notation
- [ ] IP addresses

Correct  
In AWS, users choose their network size by using CIDR notation. For more information, see Reading: Networking on AWS.

#### Q18. What is the difference between network access control lists (ACLs) and security groups?

- [ ] By default, network ACLs allow incoming traffic and block outgoing traffic from a subnet. Users can change these settings to provide an additional layer of security. However, the default configurations of security groups block all traffic.
- [ ] By default, network ACLs block all traffic from a subnet. However, the default configurations of security groups allow all inbound and outbound traffic. Users can change these settings to provide an additional layer of security.
- [ ] By default, network ACLs block incoming traffic and allow outgoing traffic. The default configurations of security groups block all traffic. Users can change these settings when they configure networking for their instance.
- [x] By default, network ACLs allow incoming and outgoing traffic from a subnet. Users can change these settings to provide an additional layer of security. However, the default configurations of security groups block all inbound traffic and allow all outbound traffic.

Correct  
Network ACLs are considered stateless. By default, they allow all traffic in and out of the subnet. However, users can restrict data at the subnet level by including both the
