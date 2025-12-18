# SOS Online Shop — DevOps Capstone Project

## Project Overview
This repository contains the DevOps implementation for **SOS Online Shop**, an e-commerce platform.  
The project focuses on automating cloud infrastructure provisioning, CI/CD pipelines, testing, monitoring, and security using industry-standard DevOps practices.

This work is developed as part of an academic **Capstone Project**, demonstrating real-world DevOps workflows and cloud deployment strategies.



## Project Objectives
- Automate infrastructure deployment using **Terraform**
- Implement CI/CD pipelines with **GitHub Actions**
- Ensure infrastructure validation and testing
- Apply cloud security best practices
- Enable monitoring, logging, and alerting
- Align implementation with an IEEE 29148-compliant SDD



## Architecture Overview
The solution uses AWS managed services to reduce operational complexity:

- **GitHub** — Source control
- **GitHub Actions** — CI/CD automation
- **Terraform** — Infrastructure as Code
- **AWS Services**:
  - VPC (Public & Private Subnets)
  - Application Load Balancer
  - ECS / Elastic Beanstalk (Compute)
  - RDS & DynamoDB (Data Layer)
  - S3 & CloudFront (Storage & CDN)
  - CloudWatch & SNS (Monitoring & Alerts)
  - IAM & KMS (Security)



## Repository Structure
```text
.
├── .github/
│   └── workflows/
│       └── sos-ci-cd.yml
├── infra/
│   ├── main.tf
│   └── modules/
├── docs/
│   ├── SDD.pdf
│   └── diagrams/
└── README.md
