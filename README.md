# Hi, I'm Komal 👋

### Azure DevOps Engineer

I’m building hands-on experience with Azure cloud infrastructure, Terraform, and Azure DevOps CI/CD. My focus is on repeatable Infrastructure as Code, secure delivery workflows, cloud governance, and reliable operations.

## Technical Skills

- **Cloud:** Microsoft Azure, Virtual Machines, VNets, subnets, NSGs, Storage, Load Balancer, Key Vault
- **DevOps & CI/CD:** Azure DevOps, YAML pipelines, Azure Repos, GitHub, branching strategies, pull requests
- **Infrastructure as Code:** Terraform, modules, variables, outputs, Azure Blob remote state
- **DevSecOps:** tfsec, Checkov, infrastructure validation, security scanning, approval workflows
- **Identity & security:** Microsoft Entra ID, RBAC, Managed Identity, least-privilege access
- **Monitoring & operations:** Azure Monitor, Log Analytics, Linux, PowerShell, Bash
- **Cloud practices:** Landing Zones, networking, governance, backup and disaster recovery, FinOps

## Projects

- **[Hospital Management – Azure DevOps](https://github.com/komal324mane/hospital-management-azure-devops):** Portfolio project; visit the repository for implementation details and current status.
- **Terraform infrastructure automation & Azure DevOps pipelines — In progress:** Hands-on work with reusable Terraform and YAML CI/CD workflows for Azure infrastructure.

## DevOps Workflow

`Code` → `Git` → `Pull Request` → `Validation` → `Security Scan` → `Terraform Plan` → `Approval` → `Deployment` → `Monitoring`

## Learning Projects & Hands-on Labs

- **Azure Cloud foundations:** Practice provisioning VMs, virtual networks, subnets, NSGs, Storage, Load Balancers, and Key Vault.
- **Terraform on Azure:** Build and organize modules, configure variables and outputs, and practice remote state with Azure Blob Storage.
- **DevSecOps pipelines:** Explore YAML validation, tfsec and Checkov scanning, plan review, and gated deployment workflows.
- **Architecture reference designs:** Explore Azure Landing Zones, hub-and-spoke networking, identity and governance, backup and disaster recovery, and FinOps.

## Azure Architecture & DevSecOps Reference

The diagram below is a learning/reference architecture, not a claim of a production deployment.

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

## Tools

![Microsoft Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Checkov](https://img.shields.io/badge/Checkov-IaC%20Security-4B32C3?style=flat-square)
![tfsec](https://img.shields.io/badge/tfsec-Terraform%20Security-3B82F6?style=flat-square)

## Contact

- **GitHub:** [github.com/komal324mane](https://github.com/komal324mane)
