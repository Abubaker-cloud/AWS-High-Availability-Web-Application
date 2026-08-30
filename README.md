# AWS High Availability Web Application

## 📌 Project Overview

A hands-on AWS Cloud Architecture project focused on building a scalable and highly available web application.

The main goal was to understand how multiple AWS services integrate together to create a reliable cloud architecture.

## 🏗️ Architecture
![AWS Architecture Diagram](architecture-diagram.png)

User → Application Load Balancer → Target Group → EC2 Auto Scaling Group → RDS

S3 → CloudFront

EC2 → CloudWatch → Alarm → SNS → Email

## ☁️ AWS Services Used

- Amazon VPC
- Amazon EC2
- Application Load Balancer (ALB)
- Target Groups
- Auto Scaling Groups (ASG)
- Amazon RDS (MySQL)
- Amazon S3
- Amazon CloudFront
- Amazon CloudWatch
- Amazon SNS
- Security Groups

## 🔐 Security

Security Groups were configured to control communication between the application and database layers.

The architecture separates access between the different components and restricts unnecessary network communication.

## 🛠️ Challenges & Troubleshooting

During the implementation, I faced challenges related to:

- EC2 ↔ RDS connectivity
- Target Group Health Checks
- CloudWatch Alarm configuration

Troubleshooting these issues helped me develop a better understanding of AWS networking, traffic flow, service integration, and problem-solving.

## 🎯 Key Learnings

- AWS Networking
- High Availability
- Scalability & Auto Scaling
- Load Balancing
- Database Connectivity
- Cloud Security
- Monitoring & Alerting
- AWS Service Integration

## 📚 Project Status

Completed — Project 1 of 3 AWS Cloud Architecture projects.
