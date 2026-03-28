# AWS 3-Tier DevOps Project

## Overview
This project shows how to deploy a 3-tier application on AWS using DevOps tools.

## Tools Used
AWS, Terraform, Docker, Jenkins, Kubernetes

## Project Structure
terraform → infrastructure  
docker → container  
jenkins → CI/CD  
kubernetes → deployment  
scripts → automation  

## Workflow
1. Create infrastructure using Terraform  
2. Build Docker image  
3. Push code to GitHub  
4. Jenkins runs pipeline  
5. Deploy application  

## Architecture
- Load Balancer (ALB)
- EC2 Instances
- RDS Database

## Result
- Automated deployment
- High availability
- Scalable infrastructure

