# ⚡ Lab 7 – AWS Infrastructure Deployment with Terraform

## 📌 Overview
In this lab, I automated the deployment of AWS infrastructure using **Terraform**.  
The focus was on creating reusable, modular Infrastructure-as-Code (IaC) templates to provision a **VPC, subnets, EC2 instances, and IAM roles**.  

This builds on earlier labs (like **Lab 6 – 3-Tier Web Application**) by shifting from manual console setup to **codified deployments**, enabling repeatability and scalability.

---

## 🏗️ Architecture Components
- **Terraform configuration files** (`main.tf`, `variables.tf`, `outputs.tf`)  
- **VPC** with multiple subnets across Availability Zones  
- **Internet Gateway (IGW)** and **NAT Gateway** for routing  
- **EC2 Instances** provisioned automatically  
- **IAM roles & policies** applied through Terraform  

---

## 🔑 Key Steps Completed
- Defined **provider configuration** for AWS in Terraform  
- Created a reusable **VPC module** with public and private subnets  
- Integrated **security groups** for web and application tiers  
- Launched **EC2 instances** with IAM roles attached  
- Validated deployments with `terraform plan` and `terraform apply`  

---

## ✅ Skills Demonstrated
- Infrastructure-as-Code (IaC) with **Terraform**  
- Modular cloud infrastructure design  
- Automated provisioning of AWS networking + compute resources  
- Version control and state management best practices  
- Reusable architecture for multi-lab consistency  

---

## 🚀 Next Steps
- Expand Terraform modules for **RDS MySQL integration**  
- Add **Application Load Balancer + Auto Scaling Groups**  
- Implement **remote state backend** (e.g., S3 + DynamoDB) for collaboration  
- Extend automation to **multi-cloud deployments (Azure + AWS)**  

---

📂 **Repository:** [Lab 7 – AWS Infrastructure Deployment with Terraform]
