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

## 🔄 Workflow
1. Terraform provisions AWS infrastructure
2. Docker builds application image
3. Code pushed to GitHub
4. Jenkins triggers CI/CD pipeline
5. Application deployed on AWS

## Architecture
- Load Balancer (ALB)
- EC2 Instances
- RDS Database

## 📊 Result
- Automated deployment process
- Improved scalability
- Reduced manual effort

  ## 📌 Future Improvements
- Add monitoring using Prometheus & Grafana
- Implement Kubernetes auto-scaling

