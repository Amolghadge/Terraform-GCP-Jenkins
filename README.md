# Terraform-GCP-Jenkins

#Requirements
Terraform plugins
Terraform 0.10.x
terraform-provider-google plugin v1.8.0
ruby-2.5.x
Configure a Service Account
In order to execute this module you must have a Service Account with the following project roles:

roles/compute.admin
roles/iam.serviceAccountUser
roles/compute.networkAdmin
roles/compute.networkAdmin is required on the host project if a shared VPC is used.

#Enable API's
In order to operate with the Service Account you must activate the following APIs on the project where the Service Account was created:

Compute Engine API - compute.googleapis.com
Install
Terraform
Be sure you have the correct Terraform version (0.10.x), you can choose the binary here:

https://releases.hashicorp.com/terraform/
#File structure
The project has the following folders and files:

/: root folder
/examples: examples for using this module
/helpers: scripts used in the build process
/templates: templates used in the provisioning process
/test: folders with files for testing the module (see Testing section on this file)
/main.tf: contains the resources to create
/variables.tf: all the variables for the module
/output.tf: the outputs of the module
/README.md: this file
