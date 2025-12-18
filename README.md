# High Availability Web Application on AWS (EC2, ELB & CloudFront)

## 📌 Project Overview
This project demonstrates the deployment of a highly available web application on AWS using EC2 instances, Elastic Load Balancer, and Amazon CloudFront. A sample café website is hosted on multiple EC2 instances and distributed globally using CloudFront for improved performance and reliability.

## 🖥️ Application Setup
- Launched two EC2 instances using Amazon Linux
- Configured user data scripts to automatically deploy the café website
- Verified website accessibility through public IPs

## 🔐 Security Configuration
- Configured Security Groups to allow HTTP traffic
- Ensured secure and controlled access to EC2 instances

## ⚙️ Load Balancing
- Created a Target Group with health checks
- Configured an Elastic Load Balancer (ELB)
- Verified traffic distribution between EC2 instances

## 🌍 Content Delivery with CloudFront
- Integrated Amazon CloudFront with the Load Balancer
- Used CloudFront distribution for global content delivery
- Improved application performance and availability worldwide

## 🛠️ Technologies Used
- AWS EC2
- Elastic Load Balancer (ELB)
- Amazon CloudFront
- Security Groups
- User Data scripts

## ✅ Outcome
Successfully deployed a globally accessible, highly available web application with improved performance using AWS Cloud infrastructure.
