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

## Workflow


* Reviewed Existing Architecture
* Created a Launch Template
* Created an Auto Scaling Group
* Configured an Application Load Balancer
* Registered Auto Scaling Group with Load Balancer
* Configured Scaling Policies
* Tested Load Balancing and Scaling
---

## Output Screenshots 
<img width="1920" height="1080" alt="Screenshot (307)" src="https://github.com/user-attachments/assets/c9b63474-aaf6-4a2b-903f-c6f6d4972007" />
<img width="1920" height="1080" alt="Screenshot (308)" src="https://github.com/user-attachments/assets/f9387080-a37f-4c12-b066-dc26da9c7b99" />
<img width="1920" height="1080" alt="Screenshot (310)" src="https://github.com/user-attachments/assets/2e86b0ee-b4cc-4ca5-8d82-d49974167a94" />
<img width="1920" height="1080" alt="Screenshot (311)" src="https://github.com/user-attachments/assets/4840af0a-f6fe-4d61-8c51-82315d526d6d" />
<img width="1920" height="1080" alt="Screenshot (312)" src="https://github.com/user-attachments/assets/1e00fa95-ab57-480a-91dd-ba3df9df4651" />
<img width="1920" height="1080" alt="Screenshot (314)" src="https://github.com/user-attachments/assets/4d1bd187-d857-4ec5-8b90-6df8c640dd77" />


---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
