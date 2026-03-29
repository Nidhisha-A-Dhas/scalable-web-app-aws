# Scalable Web Application Deployment on AWS

## Overview

This project demonstrates deploying a scalable web application on AWS using EC2, Load Balancer, and Auto Scaling. The application is hosted on virtual machines and made accessible over the internet with high availability.

## Services Used

* EC2 (Virtual Machines)
* Apache Web Server
* Elastic Load Balancer (ELB)
* Auto Scaling Group (ASG)
* VPC & Security Groups

## Architecture

* Multiple EC2 instances host the application
* Load Balancer distributes incoming traffic
* Auto Scaling adjusts instances based on demand

## Implementation Steps

1. Created EC2 instances and connected via SSH
2. Installed Apache and hosted a website
3. Deployed a Flask application on cloud VM
4. Configured Load Balancer to distribute traffic
5. Set up Auto Scaling group for dynamic scaling

## Screenshots

Refer to the screenshots folder for setup and outputs

## Key Learnings

* Cloud deployment using AWS EC2
* Hosting applications on virtual machines
* Load balancing for high availability
* Auto scaling for performance optimization
* Basic cloud security using firewall rules
