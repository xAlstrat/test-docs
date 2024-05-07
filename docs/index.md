# COSMOS_CATALOG Infrastructure

This project contains the data product infrastructure

This project uses modules described here https://coderepo.appslatam.com/projects/COSMOS/repos/cosmos-common-terraform-modules/browse

### Folders

- config: this folder contains the pod description to be used by Jenkins
- tables: this folder contains the schemas in json format of the tables used in the project

## Files
- config.tf: terraform configuration
- main.tf: main terraform code, there modules are created to provision infrastructure
- variables.tf: terraform variables declaration
- terraform.tfvars: values to fill terraform variables
