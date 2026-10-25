<h1 align="center">Hi, I'm Komal 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;size=23&amp;pause=1000&amp;color=38BDF8&amp;center=true&amp;vCenter=true&amp;width=720&amp;lines=Azure+DevOps+Engineer;Building+with+Azure+%7C+Terraform+%7C+CI%2FCD;Learn+%E2%80%A2+Build+%E2%80%A2+Automate+%E2%80%A2+Improve" alt="Animated text: Azure DevOps Engineer; building with Azure, Terraform, and CI/CD; learn, build, automate, improve" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&amp;logo=microsoftazure&amp;logoColor=white" alt="Azure" />
  <img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&amp;logo=azuredevops&amp;logoColor=white" alt="Azure DevOps" />
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&amp;logo=terraform&amp;logoColor=white" alt="Terraform" />
</p>

## ☁️ About Me

I’m an aspiring **Azure DevOps Engineer** building hands-on skills in Azure cloud infrastructure, Terraform, and Azure DevOps CI/CD. I enjoy turning infrastructure and delivery steps into repeatable, secure workflows—and sharing what I learn through practical projects.

## 🧰 Technical Skills

- **Azure Cloud:** Virtual Machines, VNets, subnets, NSGs, Storage, Load Balancer, Key Vault
- **DevOps & CI/CD:** Azure DevOps YAML pipelines, Azure Repos, Git, GitHub, branching, pull requests
- **Infrastructure as Code:** Terraform, modules, variables, outputs, Azure Blob remote state
- **DevSecOps:** tfsec, Checkov, infrastructure validation, security scans, approval workflows
- **Identity & security:** Microsoft Entra ID, RBAC, Managed Identity, least privilege
- **Monitoring & operations:** Azure Monitor, Log Analytics, Linux, PowerShell, Bash
- **Cloud practices:** Landing Zones, networking, governance, backup and disaster recovery, FinOps

## 🚀 Projects

### [Hospital Management – Azure DevOps](https://github.com/komal324mane/hospital-management-azure-devops)
Explore the project repository for its implementation, tools, and current status.

### Terraform Infrastructure & Azure DevOps Pipelines · In Progress
Hands-on work with Terraform infrastructure automation and YAML CI/CD pipelines for Azure.

## 🔄 DevOps Workflow

<p align="center">
  <strong>Code</strong> → <strong>Git</strong> → <strong>Pull Request</strong> → <strong>Validation</strong> → <strong>Security Scan</strong> → <strong>Terraform Plan</strong> → <strong>Approval</strong> → <strong>Deployment</strong> → <strong>Monitoring</strong>
</p>

## 🧪 Learning Projects & Hands-on Labs

- **Azure foundations:** Practice provisioning VMs, virtual networks, subnets, NSGs, Storage, Load Balancers, and Key Vault.
- **Terraform on Azure:** Build reusable modules and practice variables, outputs, and remote state with Azure Blob Storage.
- **DevSecOps pipelines:** Explore YAML validation, tfsec and Checkov scans, Terraform plan review, and gated deployments.
- **Architecture reference designs:** Learn Azure Landing Zones, hub-and-spoke networking, identity and governance, backup and disaster recovery, and FinOps.

## 🏗️ Azure Architecture & DevSecOps Reference

This is a **learning/reference architecture**, not a claim of a production deployment.

```mermaid
flowchart LR
    OnPrem[On-premises network] -->|VPN or ExpressRoute| Hub
    subgraph Azure[Azure reference environment]
        Hub[Hub VNet<br/>Firewall · Gateway · Private DNS]
        Hub -->|Peering and routes| App[Application spoke]
        Hub -->|Peering and routes| Shared[Shared services]
        App --> Private[PaaS private endpoints]
        Shared --> Monitor[Azure Monitor and Log Analytics]
    end
    Pipeline[Azure DevOps YAML pipeline<br/>Validate · Scan · Plan · Approve · Deploy] --> App
```

## 🛠️ Tools

![Microsoft Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Checkov](https://img.shields.io/badge/Checkov-IaC%20Security-4B32C3?style=flat-square)
![tfsec](https://img.shields.io/badge/tfsec-Terraform%20Security-3B82F6?style=flat-square)

## 🤝 Connect

I’m always learning and building—feel free to explore my work or connect with me here:

[![GitHub](https://img.shields.io/badge/GitHub-komal324mane-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/komal324mane)
