# lab-mandaroty11

## Instructions:
### Part 1: Designing Cloud Infrastructure
* **Task:**
  * Design a cloud infrastructure for a scalable web application.
  * Include components like compute instances, storage, and network configurations.
  * Use AWS EC2, S3, and VPC to build the basic architecture.
### Part 2: IAM Configuration
* **Task:**
  * Define IAM roles and policies for different components of the architecture, such as developers, admins, and application servers.
  * Ensure that each role adheres to the principle of least privilege.
### Part 3: Resource Management Strategy
* **Task:**
  * Develop a strategy for managing resources that includes auto-scaling, load balancing, and cost optimization using AWS Auto Scaling, ELB, and AWS Budgets.
### Part 4: Theoretical Implementation
Using the AWS services identified, outline the architecture for the web application. Describe how each component interacts with others, focusing on the flow of data and control between services. This description should detail the role of each service in the architecture, ensuring a clear understanding of their interactions and dependencies.

## Solution

Next I will outline a general architecture for a web application with low-medium demand on AWS.

We are using a region, with its respective VPC by default, an ALB to distribute the load to the EC2 instances, use of Cache and RDS as databases and AutoScaling

![image](https://github.com/LuisGutierrezRdz/lab-mandaroty11/assets/115661340/0a8f4edd-0643-4855-882b-db6edbe4073c)
