# Azure Active Directory & Cloud Infrastructure Lab

## Project Overview
Deployed and configured a cloud-based enterprise identity and access management (IAM) lab on Microsoft Azure, simulating a multi-machine corporate network environment.

## Architecture & Technologies Used
* **Cloud Platform:** Microsoft Azure Virtual Machines (`Standard_B2s`)
* **Operating Systems:** Windows Server 2022 Datacenter & Windows 10 Pro
* **Core Services:** Active Directory Domain Services (AD DS), DNS, Remote Desktop (RDP), Azure Virtual Networks (VNets)

## Key Tasks Performed
1. **Cloud Provisioning:** Deployed a Resource Group (`AD-Lab`) containing a Windows Server Domain Controller (`DC01`) and a client endpoint (`PC01`).
2. **Network Configuration:** Configured static private IP addressing and custom Azure VNet DNS routing to ensure seamless internal communication between cloud assets.
3. **Identity Management:** Promoted `DC01` to a Domain Controller (`mycompany.local`), created organizational units, and provisioned mock employee user accounts.

## Lab Screenshots

### Azure Resource Group & Running VMs
![Azure Resource Group](<insert-exact-screenshot-filename-1.png>)

### Active Directory Users & Computers
![Active Directory Setup](<insert-exact-screenshot-filename-2.png>)
