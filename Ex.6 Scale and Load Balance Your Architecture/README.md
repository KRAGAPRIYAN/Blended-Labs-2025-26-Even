# Lab 6 – Scale and Load Balance Your Architecture

## Title
**Scale and Load Balance Your Architecture**

**Author:** K RAGAPRIYAN  
**Register Number:** [212225040323]  
**Date:** 23 November 2026

---

## Objective

The objective of this experiment is to understand how to design and implement a scalable and highly available architecture on AWS using Auto Scaling Groups and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically adjusting computing resources based on workload demand, and ensuring fault tolerance and continuous application availability.

---

## Prerequisites

- Basic knowledge of Amazon EC2 and Amazon VPC.
- Completion of previous AWS labs (IAM, EC2, EBS, and Database Server).
- Access to AWS Academy Lab.
- Stable internet connection.

---

## Tools Used

- AWS Management Console
- Amazon EC2
- Application Load Balancer (ALB)
- Auto Scaling Groups (ASG)
- Amazon CloudWatch
- Amazon EC2 Launch Templates

---

## Tasks Performed

### Task 1: Review Existing Architecture
Reviewed the existing EC2-based application architecture created in previous experiments to understand its configuration and requirements for scalability.

### Task 2: Create a Launch Template
Created a launch template to define the EC2 instance configuration, including the Amazon Machine Image (AMI), instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group
Created an Auto Scaling Group using the launch template and configured the minimum, maximum, and desired number of EC2 instances.

### Task 4: Configure an Application Load Balancer
Created an Application Load Balancer (ALB) and configured a target group to distribute incoming application traffic across registered EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer
Attached the Auto Scaling Group to the target group of the Application Load Balancer to automatically register newly launched instances and manage traffic distribution.

### Task 6: Configure Scaling Policies
Configured scaling policies based on CPU utilization using Amazon CloudWatch alarms to automatically adjust the number of EC2 instances according to workload demand.

### Task 7: Test Load Balancing and Scaling
Tested the architecture by generating application traffic and observing the distribution of requests across EC2 instances. Also monitored the Auto Scaling Group to verify its scaling behaviour.

---

## Workflow

1. Logged in to the AWS Management Console using the AWS Academy Lab credentials.
2. Opened the Amazon EC2 dashboard and reviewed the existing EC2 instance configuration.
3. Created a Launch Template by specifying the required AMI, instance type, security group, and other instance settings.
4. Created an Auto Scaling Group using the newly created Launch Template.
5. Configured the minimum, maximum, and desired capacity of the Auto Scaling Group.
6. Configured the Application Load Balancer and created a target group for the EC2 instances.
7. Attached the Auto Scaling Group to the target group of the Application Load Balancer.
8. Configured scaling policies using CloudWatch metrics to monitor CPU utilization and automatically adjust the number of instances.
9. Tested the application through the Load Balancer DNS endpoint and observed traffic distribution across the available EC2 instances.
10. Monitored the Auto Scaling Group and EC2 dashboard to verify instance scaling and application availability.

---

## Output Screenshots

### Screenshot 1: AWS Architecture Configuration
![Screenshot 1](Screenshot%202026-11-23%20153256.png)

---

### Screenshot 2: Auto Scaling / Load Balancer Configuration
![Screenshot 2](Screenshot%202026-11-23%20153347.png)

---

### Screenshot 3: Load Balancing and Scaling Output
![Screenshot 3](Screenshot%202026-11-23%20153427.png)

---

## Result

Thus, the experiment demonstrated the implementation of a scalable and highly available cloud architecture using Amazon EC2 Auto Scaling Groups and Elastic Load Balancing. It helped understand how incoming traffic can be distributed across multiple EC2 instances and how computing resources can be automatically adjusted based on workload demand, improving application availability, scalability, and fault tolerance.

---

**End of Experiment – Lab 6**