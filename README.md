# Task 3: Infrastructure as Code (IaC) with Terraform

## 🎯 Objective
Provision a local Docker container using Terraform to demonstrate Infrastructure as Code (IaC).

## 🛠 Tools Used
- **Terraform v1.13.3**
- **Docker Desktop**
- **Docker Provider** (`kreuzwerker/docker`)

## 📂 Project Structure


terraform-docker/
│── main.tf # Terraform configuration file
│── logs.txt # Execution logs (init, plan, apply, state, destroy)
│── README.md # Project documentation


## 🚀 Steps Performed
1. **Created `main.tf`** to provision:
   - Docker image: `nginx:latest`
   - Docker container: `nginx_container` (exposed on port 8080 → 80)

2. **Initialized Terraform**
   ```bash
   terraform init
3.Planned infrastructure

  terraform plan


4.Applied configuration

  terraform apply -auto-approve


5.Verified resources

  terraform state list


6.Destroyed infrastructure

  terraform destroy -auto-approve

✅ Outcome

Successfully provisioned and destroyed an Nginx container using Terraform.

Verified that the container was running at http://localhost:8080
.

Learned to use Terraform commands: init, plan, apply, state list, and destroy.
