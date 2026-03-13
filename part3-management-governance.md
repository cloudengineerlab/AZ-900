# AZ-900 Part 3 – Azure Management, Governance, Security, Pricing and Support

This document summarizes the core concepts of Azure management, governance, security, pricing, and support covered in Part 3 of the AZ-900 learning path.

---

# Identity and Access Management

Identity and access management ensures that the right users have the appropriate access to Azure resources.

Azure uses **Microsoft Entra ID** (formerly Azure Active Directory) to manage identities.

Main components:

| Component | Description |
|------|------|
| Microsoft Entra ID | Identity provider used to authenticate users and services. |
| Authentication | Verifying a user's identity (login). |
| Authorization | Determining what a user is allowed to do. |
| Single Sign-On (SSO) | Users log in once and access multiple applications. |
| Multi-Factor Authentication (MFA) | Additional security layer requiring multiple verification methods. |

---

# Role-Based Access Control (RBAC)

RBAC allows administrators to control who can access Azure resources and what actions they can perform.

RBAC is based on assigning **roles** to users, groups, or applications.

Example roles:

| Role | Permissions |
|------|------|
| Owner | Full access including access management |
| Contributor | Can create and manage resources |
| Reader | Can view resources but cannot modify them |

RBAC improves security by applying the **principle of least privilege**.

---

# Azure Security Tools

Azure provides several built-in tools to improve security and monitor threats.

| Tool | Purpose |
|------|------|
| Microsoft Defender for Cloud | Security monitoring and threat protection |
| Azure Key Vault | Secure storage for secrets, keys, and certificates |
| Azure Firewall | Network security service controlling traffic |
| Azure DDoS Protection | Protects applications from distributed denial-of-service attacks |

These tools help organizations protect applications and data running in Azure.

---

# Azure Governance

Governance ensures that Azure resources comply with organizational policies and standards.

Key governance tools include:

| Tool | Description |
|------|------|
| Azure Policy | Enforces rules and compliance across resources |
| Resource Locks | Prevent accidental deletion or modification of resources |
| Tags | Metadata used to organize and track resources |
| Management Groups | Organize multiple subscriptions for centralized management |

Governance helps organizations maintain control over large Azure environments.

---

# Azure Cost Management

Azure uses a **pay-as-you-go** pricing model.

Organizations only pay for the resources they consume.

Important cost tools:

| Tool | Purpose |
|------|------|
| Azure Pricing Calculator | Estimate the cost of Azure services before deployment |
| Azure Cost Management | Monitor and analyze Azure spending |
| Azure Budgets | Set spending limits and receive alerts |

These tools help organizations manage and optimize cloud spending.

---

# Service Level Agreements (SLA)

An SLA defines the expected uptime and availability of a cloud service.

Example:

| SLA | Maximum downtime per year |
|------|------|
| 99% | ~3.65 days |
| 99.9% | ~8.76 hours |
| 99.99% | ~52 minutes |

Higher SLA percentages indicate greater reliability.

Organizations often design systems using multiple services to achieve higher availability.

---

# Azure Support Plans

Microsoft provides several support plans for Azure customers.

| Plan | Description |
|------|------|
| Basic | Free support with access to documentation and community |
| Developer | Basic support for development environments |
| Standard | Faster response times for production workloads |
| Professional Direct | Advanced technical support |
| Premier / Unified | Enterprise-level support with dedicated resources |

Organizations choose support plans depending on their operational requirements.

---

# Key Takeaways

- Microsoft Entra ID manages identities and authentication.
- RBAC controls access to Azure resources.
- Azure provides security tools such as Defender for Cloud and Key Vault.
- Governance tools like Azure Policy and resource locks enforce compliance.
- Azure pricing follows a pay-as-you-go model.
- SLAs define the expected availability of Azure services.
