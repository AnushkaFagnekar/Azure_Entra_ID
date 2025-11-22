# Azure Entra (Azure AD) User Automation Using Terraform

This project automates the creation and management of Azure Entra ID (Azure Active Directory) users using Terraform.  
It demonstrates how Infrastructure as Code (IaC) can be used to manage identity resources in a secure and repeatable way.

---

## 🚀 Project Overview

This Terraform project does the following:

- Fetches your Azure AD domain dynamically using `azuread_domains`
- Reads user details from a CSV file (`users.csv`)
- Creates Entra ID users automatically
- Generates user passwords based on naming rules
- Forces password change on first login
- Sets user attributes such as department, job title, and display name
- Uses `for_each` to create multiple users efficiently
- Supports remote or local Terraform backend

---

## 📁 Project Structure
- main.tf
- main.tfplan
- groups.tf
- users.csv
- provider.tf

---


Author: Anushka Fagnekar
DevOps Engineer | Azure | Terraform | Kubernetes

GitHub: https://github.com/AnushkaFagnekar