 Three-Tier Architecture on AWS

 Architecture

![AWS Three-Tier Architecture](aws-three-tier-architecture.png)

Project Overview

This project demonstrates a three-tier architecture on AWS using separate layers for the web, application, and database components.

The architecture consists of:

Web Layer – Handles user requests using an Application Load Balancer.

Application Layer – Runs application servers in private subnets.
Database Layer – Stores application data in a private database subnet

AWS Services Used

   Amazon VPC
-> Public and Private Subnets
-> Internet Gateway
-> NAT Gateway
-> Application Load Balancer
-> Amazon EC2
-> Auto Scaling
-> Amazon RDS
-> Architecture Flow

Internet → Load Balancer → Application Servers → RDS Database

Key Features

- Secure network isolation using public and private subnets
- Load balancing using Application Load Balancer
- Auto Scaling for application servers
- RDS database deployed in a private subnet
- NAT Gateway for outbound internet access from private resources
