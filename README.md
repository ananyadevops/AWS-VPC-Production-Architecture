# AWS Highly Available VPC Architecture 🏗️

## Overview
Production-ready highly available AWS infrastructure 
built from scratch using AWS Console.
Designed to demonstrate real-world cloud architecture 
with high availability, security and scalability.

## Architecture Diagram
![Architecture](architecture-diagram.png)

## Architecture Components
- ✅ VPC (10.0.0.0/16)
- ✅ 2 Public Subnets (us-east-1a, us-east-1b)
- ✅ 2 Private Subnets (us-east-1a, us-east-1b)
- ✅ Internet Gateway
- ✅ NAT Gateway (2 AZs)
- ✅ Route Tables
- ✅ Application Load Balancer
- ✅ Auto Scaling Group
- ✅ EC2 Instances in Private Subnets
- ✅ Security Groups

## Key Concepts Used
- High Availability across 2 Availability Zones
- Private subnets for enhanced security
- NAT Gateway for secure outbound internet access
- Application Load Balancer for traffic distribution
- Auto Scaling for handling traffic spikes automatically

## Live Demo
Deployed a portfolio page on AWS EC2 using Nginx.
See `index.html` for the source code.

## Screenshots
All screenshots are available in the `screenshots/` folder.

## Tech Stack
`AWS VPC` `EC2` `ALB` `Auto Scaling Group` `NAT Gateway` `Route Tables` `Security Groups` `Nginx`

## Author
**Ananya Chauhan**  
DevOps Engineer | AWS Cloud Practitioner  
[GitHub](https://github.com/ananyadevops)
