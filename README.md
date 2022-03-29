# LAUNCHING EC2 Instance in AWS using Terraform code
The repo aims to create a EC2 enviroment as specified and is dynamically adjusted.
- Repo has the following module:
  - main.tf
  - credentials.tf (Recommeded to use the system credential itself).
  - input-script.py to configure all the coustom inputs and create a abstraction layer above the code.
  - system-config.sh to check all the requirements are available.
