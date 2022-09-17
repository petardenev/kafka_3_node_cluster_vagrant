# Terraform Guide
Use Terraform to create resources for kafka in AWS and Other Cloud Provider and kafka being managed by Ansible.

## How to Use for AWS?
* update `aws/var.tf` file with your requirements and variables.
* update your `~/.aws/credentials` file.
* export `AWS_PROFILE=<your aws profile>`.
* update `terraform/aws/data.tf` to include public/private subnets, default it looks for public subnets.
* Run `terraform init` in `terraform/aws` folder.
* Run `terraform plan` to see resources which will be created.
* Run `terraform apply` to create resources.
