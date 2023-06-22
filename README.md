# Terraform-Import

A test to the ability to use config driven import within Terraform, allowing resources to be imported into Terraform State and then managed using Terraform moving forward.

## Steps:
 1. Edit `import.tf` file.
 2. Run `terraform plan -generate-config-out new.tf`.
 3. Run `terraform apply`.