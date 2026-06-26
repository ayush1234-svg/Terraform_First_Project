# Terraform First Project 🚀

This repository contains my hands-on Terraform projects while learning Infrastructure as Code (IaC) on AWS.

## 📂 Project Structure

```
aws/
├── local_state/
│   ├── main.tf
│   └── ...
└── remote_state/
    ├── main.tf
    └── ...
```

## 📌 Projects

### 1. Terraform Local State
- Configured the AWS provider.
- Created EC2 instances using Terraform.
- Used the `count` meta-argument to provision multiple instances.
- Managed infrastructure using Terraform's local state.

### 2. Terraform Remote State
- Created an Amazon S3 bucket to store Terraform state remotely.
- Configured an S3 backend for remote state management.
- Implemented state locking using Amazon DynamoDB.
- Migrated the local Terraform state to the remote backend.
- Verified that Terraform uses the remote state for future operations.

## 🛠️ Technologies Used

- Terraform
- AWS EC2
- Amazon S3
- Amazon DynamoDB
- Linux
- AWS CLI

## 📖 Concepts Learned

- Infrastructure as Code (IaC)
- Providers
- Resources
- Data Sources
- Variables
- Count Meta-Argument
- Local State
- Remote State
- State Migration
- State Locking
- Terraform Backend

## 🚀 Getting Started

1. Clone the repository.

```bash
git clone https://github.com/ayush1234-svg/Terraform_First_Project.git
```

2. Navigate to the desired project directory.

```bash
cd aws/local_state
```

or

```bash
cd aws/remote_state
```

3. Initialize Terraform.

```bash
terraform init
```

4. Preview the execution plan.

```bash
terraform plan
```

5. Apply the configuration.

```bash
terraform apply
```

## 📚 Learning Goal

This repository documents my journey of learning Terraform through practical AWS projects. As I continue learning, I plan to add:

- Terraform Variables
- Outputs
- Modules
- VPC
- Security Groups
- Load Balancer
- Auto Scaling
- Terraform + Ansible Integration

---

⭐ If you find this repository helpful, feel free to star it!
