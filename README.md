# Terraform Project
In this project, I used Terraform to Deploy VPC, Subnets, and EC2 on AWS
This repository contains Terraform code for deploying a Virtual Private Cloud (VPC) with a public subnet, a private subnet, and an EC2 instance on AWS. This is a quick and easy way to spin up a new environment in AWS for testing, development or production purposes.

# Prerequisites
Before using this Terraform configuration, you need to have the following:

  An AWS account
  
  AWS CLI installed and configured on your local machine
  
  Terraform installed on your local machine

# Usage
To use this Terraform code, follow these steps:

1. Clone this repository to your local machine:

`git clone https://github.com/<YOUR-GITHUB-USERNAME>/Terra-project.git
cd Terra-project`

2. Initialize the Terraform backend by running the following command:
 
 `terraform init`

3. Customize the variables in `variables.tf` and `main.tf` according to your requirements. You can modify the VPC CIDR block, subnets, EC2 instance type, etc.

4. Plan the Terraform deployment:
 `terraform plan`

5. If the plan looks good, apply the Terraform deployment:

 `terraform apply`

6. Once the deployment is complete, you can SSH into the EC2 instance using the public IP address.

7. To destroy the environment when you're done, run:

 `terraform destroy`

# Files
This repository contains the following files:

`main.tf`: The main Terraform configuration file for deploying VPC, subnet, and EC2 instances.

`variables.tf`: Defines the variables used in the main.tf configuration file.

README.md: This file.

Contributing
If you find any issues or would like to contribute to this project, please open an issue or a pull request on GitHub.
