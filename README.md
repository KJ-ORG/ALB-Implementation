# ALB-Implementation
Implement ALB for ec2 instances and validate routing and health checks
## Step-01: Create the required manifest files like version, variables, outputs for all the resources like ec2, security groups, ALB, VPC etc..

## Step-02: Execute Terraform Commands
  terraform init
  terraform validate
  terraform plan
  terraform apply -auto-approve

## Step-03: Validate the ALB url by hitting the ALB url from browser and terminate one of the instance and try hitting the ALB url to check that the ALB is routing the               traffic to the healthy instance
