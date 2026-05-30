# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture
Author : your name   Reg no : yours   Date :

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

1.Launch multiple servers.

2.Deploy the application on each server.

3.Create a load balancer.

4.Add servers to the load balancer.

5.Configure auto-scaling.

6.Test load distribution.


---

## Output Screenshots 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d5ff435d-461b-4e93-aa0d-206a7a104dee" />

<img width="1269" height="556" alt="image" src="https://github.com/user-attachments/assets/506b5842-4241-4056-af57-2bd9a246d921" />

<img width="1258" height="636" alt="image" src="https://github.com/user-attachments/assets/f3e4dff0-d84d-4e80-b0a4-221e98f28e4e" />

<img width="1265" height="559" alt="image" src="https://github.com/user-attachments/assets/66c983dc-0c3b-4404-82b1-d205b7041990" />

<img width="1266" height="561" alt="image" src="https://github.com/user-attachments/assets/3347f1e9-bd8d-4444-aa20-d05baf0c7ab1" />

<img width="1267" height="556" alt="image" src="https://github.com/user-attachments/assets/fc96452e-9794-4fd0-bdaa-c60d73c84eb3" />

---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
