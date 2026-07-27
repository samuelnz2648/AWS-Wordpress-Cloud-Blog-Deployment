# Cloud Blog Deployment with WordPress

A cloud computing project completed for **ICC104 — Introduction to Cloud Computing** at Media Design School.

This project involved deploying a functional WordPress blog on **Amazon Web Services (AWS)** using an Ubuntu EC2 virtual machine and a manually configured **LAMP stack**.

## Project Overview

The deployment used:

* **Linux** — operating system
* **Apache** — web server
* **MySQL** — database
* **PHP** — server-side scripting
* **WordPress** — content management system

## AWS Services Used

* Amazon EC2
* Amazon EBS
* Elastic IP
* Security Groups
* Amazon CloudWatch
* AWS Budgets and Billing

## Key Tasks

* Created and configured an Ubuntu EC2 instance
* Installed Apache, MySQL, and PHP
* Created a dedicated WordPress database and user
* Downloaded and configured WordPress
* Set the required Linux file ownership and permissions
* Assigned a static Elastic IP address
* Monitored CPU usage, network traffic, and instance health
* Configured a zero-spend AWS budget alert
* Compared cloud hosting with traditional on-premises hosting
* Explored virtualization and resource pooling

## Deployment Process

```text
Create AWS Account
        ↓
Launch Ubuntu EC2 Instance
        ↓
Configure Network and Security Rules
        ↓
Install Apache, MySQL, and PHP
        ↓
Create WordPress Database
        ↓
Download and Configure WordPress
        ↓
Complete WordPress Web Installer
        ↓
Monitor Usage with CloudWatch
```

## Outcome

The project successfully deployed a functional WordPress blog on AWS. The `t3.micro` instance remained below approximately 1% CPU utilization during testing, and the deployment remained within the available free usage allowance.

## Project Deliverables

* `ICC104_PR2_Ong_Samuel.pdf` — written deployment report
* Screencast video demonstrating:

  * The AWS EC2 instance
  * The WordPress admin dashboard
  * The public WordPress blog
* Deployment screenshots and configuration evidence

## Author

**Samuel Ong**
ICC104 — Introduction to Cloud Computing
Media Design School
