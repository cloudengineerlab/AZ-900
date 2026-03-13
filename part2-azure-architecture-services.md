# AZ-900 Part 2 – Azure Architecture and Services

This document summarizes the core Azure architecture and services covered in Part 2 of the Microsoft Azure AZ-900 learning path.

---

# Azure Regions

An Azure region is a geographic area that contains one or more datacenters.

Each region provides:

- high availability
- redundancy
- low latency for users in nearby areas

Examples of Azure regions:

- West Europe (Netherlands)
- North Europe (Ireland)
- East US

Organizations deploy resources to a region closest to their users.

---

# Availability Zones

Availability zones are physically separate datacenters within a region.
 
Each zone has:

- independent power
- independent cooling
- independent networking

Purpose:

Increase application availability and protect against datacenter failures.

Example:

Region: West Europe  
Zone 1  
Zone 2  
Zone 3

If one zone fails, the application can continue running in another zone.

---

# Region Pairs

Azure regions are paired together to support disaster recovery.

Examples:

West Europe ↔ North Europe  
East US ↔ West US

Benefits:

- data replication
- platform updates applied sequentially
- disaster recovery support

---

# Azure Resources

A resource is any service created in Azure.

Examples of Azure resources:

- Virtual Machines
- Storage Accounts
- Virtual Networks
- Databases

Resources are the building blocks of Azure solutions.

---

# Resource Groups

A resource group is a container that holds related Azure resources.

Example:

Resource Group: WebApp-RG

Contains:

- virtual machine
- database
- storage account

Benefits:

- organize resources
- manage permissions
- manage lifecycle

Important:

Deleting a resource group deletes all resources inside it.

---

# Azure Subscriptions

A subscription is a logical container used for:

- billing
- access control
- resource limits

Each subscription can contain multiple resource groups.

Example structure:

Subscription  
→ Resource Group  
→ Resources

Organizations may use multiple subscriptions for different departments or projects.

---

# Management Groups

Management groups allow administrators to organize multiple subscriptions.

Structure:

Management Group  
→ Subscription  
→ Resource Group  
→ Resource

Benefits:

- centralized policy management
- access control across subscriptions
- governance for large organizations

---

# Azure Compute Services

Compute services allow applications to run in Azure.

| Service | Description |
|------|------|
| Virtual Machines | Full control over operating system and infrastructure. |
| Azure App Service | Platform for hosting web applications. |
| Azure Functions | Serverless computing that runs code in response to events. |
| Azure Kubernetes Service (AKS) | Managed Kubernetes container orchestration. |

---

# Azure Networking Services

Networking services enable communication between resources and users.

| Service | Description |
|------|------|
| Virtual Network (VNet) | Private network in Azure. |
| VPN Gateway | Connects on-premises networks to Azure. |
| Load Balancer | Distributes traffic across servers. |
| Application Gateway | Web traffic load balancing with advanced routing. |
| Azure DNS | Domain name resolution service. |

---

# Azure Storage Services

Azure provides multiple storage options depending on the type of data.

| Storage Type | Description |
|------|------|
| Blob Storage | Stores unstructured data such as images and videos. |
| File Storage | Managed file shares accessible through SMB protocol. |
| Queue Storage | Stores messages for communication between services. |
| Table Storage | NoSQL key-value storage for structured data. |

---

# Key Takeaways

- Azure regions contain datacenters used to deploy services.
- Availability zones provide redundancy within a region.
- Region pairs support disaster recovery.
- Resources are organized in resource groups and subscriptions.
- Azure provides services for compute, networking, and storage.

Understanding these components is essential for working with Microsoft Azure infrastructure.
