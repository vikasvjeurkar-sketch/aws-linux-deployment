# AWS Linux Server Deployment

## Overview
A hands-on project deploying a secure, scalable web server environment on AWS using EC2, EBS, and S3.

## Tech Stack
* **Cloud:** AWS (EC2, S3, IAM, EBS)
* **OS:** Amazon Linux 2023
* **Web Server:** Apache (httpd)

## Key Features
* **Storage:** Attached a secondary EBS volume for data persistence.
* **Security:** Configured Security Groups to restrict SSH access to a specific IP.
* **Access Management:** Created IAM users with limited permissions to follow security best practices.
* **Backups:** Automated sync of web files to S3.

## How to Reproduce
1. Launch EC2...
2. Run `scripts/setup.sh`...
