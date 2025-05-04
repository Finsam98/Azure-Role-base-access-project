# Azure-R# 🔐 Azure RBAC Model Design Project

A practical implementation of Azure Role-Based Access Control (RBAC) following the **principle of least privilege**. This project demonstrates how to set up secure, custom IAM controls across multiple resource groups in a simulated organization.

---

## 📌 Project Objectives

- Apply RBAC to isolate access for Developers, Security Team, and Finance Team
- Create and assign **built-in** and **custom roles**
- Demonstrate access control using Azure Portal and CLI
- Showcase cloud security engineering skills using Microsoft Azure

---

## 🧱 Resource Groups and Role Assignments

| Resource Group   | Role            | Assigned To         | Purpose                              |
|------------------|------------------|----------------------|----------------------------------------|
| RG-App           | Contributor      | Developer Group      | Deploy/manage app services             |
| RG-Security      | Reader / Custom Log Reader | Security Team | Read-only access to logs              |
| RG-Finance       | Billing Reader   | Finance User         | View billing data only                 |

---

