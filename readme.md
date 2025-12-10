# DevOps Practical Work – AWS EC2 Instance

This repository contains documentation and screenshots of the DevOps practical tasks I performed using an AWS EC2 instance. The objective of this work is to understand essential DevOps processes by setting up and configuring a cloud server, installing required tools, and deploying a sample application.

---

## 🚀 Overview

During this practical task, I completed the following:

- Launched and configured an AWS EC2 instance
- Connected to the server using SSH
- Installed DevOps-related tools and packages
- Executed essential Linux commands
- Installed and configured a web server (Apache/Nginx)
- Deployed a sample webpage/application
- Captured screenshots as proof of work

All screenshots are stored inside the **/screenshots** folder.

---

## 🖥️ Tools & Technologies Used

- AWS EC2 (Ubuntu)
- Linux Terminal
- SSH
- Git & GitHub
- Apache / Nginx
- DevOps workflow commands

---

## 📌 Steps Performed

### 1. Created EC2 Instance
- Selected Ubuntu Server AMI  
- Configured t2.micro instance  
- Added security group rules (SSH, HTTP, HTTPS)  
- Launched the instance  

**Screenshot:** `DEV OPS.PDF `

---

### 2. Connected to EC2 Instance via SSH

```bash
ssh -1 my-key-pair.pem ubuntu@ec2-54-123-45-67.compute-1.amazonaws.com 
