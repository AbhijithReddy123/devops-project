# 🚀 DevOps Project: Automated AWS Infrastructure with Terraform & Ansible

This project demonstrates how to provision and configure a complete AWS environment using **Terraform** for infrastructure as code and **Ansible** for configuration management. It includes automated setup of VPC, subnets, EC2 instances, security groups, and a web server.

---

## 🛠️ Tools & Technologies

- **Terraform**: Infrastructure provisioning
- **Ansible**: Configuration management
- **AWS EC2, VPC, IAM, S3**: Core cloud services
- **Nginx**: Web server setup
- **Ubuntu**: Base AMI for EC2
- **Git & GitHub**: Version control

---

## 📦 Project Structure

---

## 🚧 What It Does

- Provisions a **VPC** with public subnet
- Launches an **EC2 instance** with SSH access
- Configures **security groups** for HTTP and SSH
- Installs and configures **Nginx** via Ansible
- Uses **user data** for initial bootstrapping
- Documents setup for reproducibility and interviews

---

## 📋 How to Use

### 1. Clone the Repo
```bash
git clone https://github.com/AbhijithReddy123/devops-project.git
cd devops-project
