# Simple Web Server Deployment on AWS using Terraform

This project demonstrates how to deploy a basic Apache web server on an AWS EC2 instance using Terraform. The infrastructure includes:

- A custom VPC
- Public subnet
- Internet Gateway and route table
- Security group with web (HTTP/HTTPS) and SSH access
- Elastic IP for public access
- EC2 instance with Apache installed via user data

## 🛠️ Prerequisites

- [Terraform](https://www.terraform.io/downloads.html) installed
- AWS CLI configured with appropriate credentials
- An existing AWS key pair (`key_name` used in `main.tf`)

## 🚀 How to Deploy

1. Clone the repo:

```bash
git clone https://github.com/your-username/terraform-webserver.git
cd terraform-webserver
