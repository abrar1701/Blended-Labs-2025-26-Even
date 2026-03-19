# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: Mohamed Abrar M
* **Register Number**: 212223040111
* **Date of Submission**: 19-03-2026

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)

(Write the steps you followed in your own words)

1. Launched EC2 Instance for Database Server
2. Configureed Security Group for Database Access
3. Connected to EC2 Instance
4. Installed Database Server
5. Started and Configured Database Service
6. Created a Sample Database
7. Tested Database Connectivity

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1920" height="1080" alt="Screenshot (288)" src="https://github.com/user-attachments/assets/09383823-3cbb-459b-bdde-27d8f8308d3f" />

---

### Screenshot 2: Database Service Running

<img width="1920" height="1080" alt="Screenshot (289)" src="https://github.com/user-attachments/assets/328fcbc0-be7f-42d8-9053-45f4902cb01c" />

---

### Screenshot 3: Sample Database and Table

<img width="1920" height="1080" alt="Screenshot (290)" src="https://github.com/user-attachments/assets/c59820e7-1198-4a42-be35-125a9a36307f" />

---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
