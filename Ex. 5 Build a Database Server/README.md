# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: Hemalatha R
* **Register Number**: 212224040114
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

### **Student Explanation – 5 Points**

1. Created an Amazon RDS database using the MySQL engine.
2. Configured the database instance with username, password and storage settings.
3. Created a Multi-AZ deployment for better availability and durability.
4. Configured VPC and security groups to allow database connectivity.
5. Connected the web application to the RDS database and tested adding, editing and deleting contacts.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1917" height="1091" alt="image" src="https://github.com/user-attachments/assets/2e6f10d7-fe78-4ae7-8d14-fb81797dbbd7" />

---

### Screenshot 2: Database Service Running

<img width="1917" height="1090" alt="Screenshot 2026-11-20 120352" src="https://github.com/user-attachments/assets/5d18d325-04cb-4361-aea3-6271449d1bfe" />

---

### Screenshot 3: Sample Database and Table

<img width="1227" height="717" alt="image" src="https://github.com/user-attachments/assets/b5369bc3-503e-49eb-a5eb-04ab7c756f4f" />


---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
