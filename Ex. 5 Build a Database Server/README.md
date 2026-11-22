# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: K RAGAPRIYAN
* **Register Number**: 212225040323
* **Date of Submission**: 20/11/2026

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

1. Launch an EC2 instance in AWS and configure the required instance type, operating system, and security group.

2. Connect to the EC2 instance using SSH and update the system packages.

3. Install a Database Management System (DBMS) such as MySQL or MariaDB on the EC2 instance.

4. Configure the database server, create a sample database, and create a user with appropriate permissions.

5. Verify the database server connectivity by connecting to the database and executing basic SQL queries.



---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

![alt text](<Screenshot 2026-11-22 224109.png>)

---

### Screenshot 2: Database Service Running

![alt text](<Screenshot 2026-11-22 224126.png>)

---

### Screenshot 3: Sample Database and Table

![alt text](<Screenshot 2026-11-22 224152.png>)

---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
