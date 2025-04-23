# -Infrastructure-Automation-Using-Terraform-on-AWS-
# AWS Infrastructure Automation with Terraform

## Features
- Creates VPC, Subnet, and Security Group
- Launches an EC2 instance with SSH access
- Key pair management

## Prerequisites
- AWS Account
- Terraform installed
- SSH key at `~/.ssh/id_rsa.pub`

## How to Use

1. Set your AWS credentials:

```bash
export TF_VAR_aws_access_key="YOUR_ACCESS_KEY"
export TF_VAR_aws_secret_key="YOUR_SECRET_KEY"
