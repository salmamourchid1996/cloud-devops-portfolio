# Secure Multi-Tier Web App on AWS

## Overview
This project demonstrates a secure, scalable web application hosted on AWS using Terraform for IaC and GitHub Actions for CI/CD.

## Architecture
- Frontend: React app hosted on S3 + CloudFront  
- Backend: Python API running on EC2  
- Database: RDS (PostgreSQL) in private subnet  
- Networking: VPC with public/private subnets  
- Security: IAM roles, Security Groups, AWS WAF  
- Monitoring: CloudWatch  

## Tech Stack
AWS, Terraform, GitHub Actions, Docker
