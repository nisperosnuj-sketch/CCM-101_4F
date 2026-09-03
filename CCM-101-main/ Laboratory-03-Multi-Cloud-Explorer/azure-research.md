# Microsoft Azure Research

## 1. Overview
Microsoft Azure, launched in 2010, is Microsoft's public cloud computing platform. Azure provides a broad ecosystem for building, testing, deploying, and managing applications through Microsoft-managed data centers, seamlessly integrating with existing enterprise Microsoft stacks.

## 2. Global Infrastructure
* **Regions:** 60+ Regions available in over 140 countries.
* **Availability Zones:** Present across major regions with independent power, cooling, and networking.
* **Geographies:** Defined boundaries containing at least one region to maintain data residency and compliance limits.

## 3. Cloud Management Console
The Azure Portal (`portal.azure.com`) offers an intuitive, blade-based interface for resource monitoring and management. Management is also supported via Azure CLI, Azure PowerShell, and Azure Resource Manager (ARM) / Bicep templates.

*Screenshot Evidence:*  
![Azure Portal Overview](assets/screenshots/azure-console.png)

## 4. Core Services

* **Compute — Azure Virtual Machines (VMs):** On-demand Linux and Windows VM instances providing scalable computing resources.
* **Storage — Azure Blob Storage:** Massively scalable object storage for unstructured data, logs, backups, and streaming media.
* **Networking — Azure Virtual Network (VNet):** Building block for private networks in Azure, allowing secure communication between Azure resources, the internet, and on-premises networks.
* **Identity — Microsoft Entra ID (formerly Azure AD):** Cloud-based identity and access management service that provides single sign-on (SSO) and multi-factor authentication (MFA).

## 5. Three Key Advantages
1. **Hybrid Cloud Dominance:** Seamless integration with on-premises environments via Azure Arc and Azure Stack.
2. **Native Microsoft Enterprise Integration:** Unrivaled compatibility with Windows Server, Active Directory, SQL Server, and Microsoft 365.
3. **Hybrid Cost Benefits:** Azure Hybrid Benefit allows enterprises to reuse existing Windows Server and SQL Server licenses in the cloud.

## 6. Enterprise Use Cases
* Enterprise Hybrid Cloud deployments connecting corporate data centers to the cloud.
* Large-scale SQL Server database migrations to Azure SQL Managed Instance.
* Enterprise identity management and desktop virtualization via Azure Virtual Desktop.
