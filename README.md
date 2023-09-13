# my_terraform_project_2

Open a terminal and navigate to the ~\terraform-count-ec2-demo directory:
cd ~\terraform-count-ec2-demo

The terraform init command initializes the plugins and providers that are required to work with AWS resources that need to be provisioned:
terraform init

Run the terraform plan command. Terraform plan command gives you an overview of which resources will be provisioned in your infrastructure:
terraform plan

Terraform apply command reads all the configuration files such as main.tf, variables.tf, terraform.tfvars, and then using the provider in provider.tf file it connects to the AWS account and launches the ec2 instances:
terraform apply
