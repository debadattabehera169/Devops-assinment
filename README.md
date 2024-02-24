# Assingment-2
# Terraform:
It is a tool for infrastructure provisioning and building infrastructure with the help of Code known as IaC(Infrastructure as Code). The main advantage of using this kind of tool is to modify the whole infrastructure and restructure it within seconds. As par the name suggests this kind of tool provides a mechanism where we need to write scripts that provide a full functional infrastructure.

Terraform use Hashicorp Configuration Language (HCL) for provisioning.

Benefits of Terraform
Platform independent provisioning, large no. of providers.
Multi-Platform
Privilege mechanism inbuilt
Steps to use
Install terraform.
choco install terraform
Connect with provider.
Install Azure CLI
Crating Service Principle(SP) in azure.
Configure with provider.
az login
Init the directory
Write scripts for infra.
infra.tf
Provisioning infra with terraform.
# initalizing
terraform init

# validate the .tf file.
terraform validate

# Check the plan are to be executable or not.
terraform plan

# apply the terraform plan
terraform apply
