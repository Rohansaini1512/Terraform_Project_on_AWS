# Terraform AWS Infrastructure Project

## Overview

This project automates the creation of AWS infrastructure using Terraform. The infrastructure includes the following components:

- **VPC (Virtual Private Cloud)**: A custom VPC to host the resources.
- **Public Subnets**: Two public subnets in different availability zones.
- **Internet Gateway**: Allows instances in the VPC to access the internet.
- **Route Table**: Routes traffic from the subnets to the internet gateway.
- **Security Groups**: Firewall rules to control inbound and outbound traffic.
- **EC2 Instances**: Two t2.micro instances deployed in different subnets.
- **Application Load Balancer (ALB)**: Distributes traffic across the EC2 instances.
- **S3 Bucket**: Used for storage with specific access controls.

## Architecture Diagram

![Infrastructure Diagram](path_to_your_diagram_image.png)

## Prerequisites

- **Terraform**: Ensure Terraform is installed on your machine. You can download it from the [official Terraform website](https://www.terraform.io/downloads.html).
- **AWS Account**: You must have an AWS account with IAM credentials configured.

## Terraform Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/terraform-aws-project.git
   cd terraform-aws-project
