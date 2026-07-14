# Microsoft Infrastructure Administration & Identity Portfolio

> **Windows Server | Active Directory | Microsoft Entra ID | Microsoft Azure | Microsoft 365 | PowerShell**

---

# Status

**Active Development**

A structured, hands-on portfolio demonstrating practical Microsoft infrastructure administration across on-premises and cloud environments.

---

# Career Focus

**Junior Microsoft Systems Administrator with Identity & Access Management (IAM) Strength**

This portfolio demonstrates the progressive development of practical administration skills across the Microsoft enterprise ecosystem.

The objective is to build the knowledge and operational capability expected of a junior Microsoft Systems Administrator while developing a strong foundation in identity administration and cloud technologies.

The portfolio combines:

- Windows Server Administration
- Active Directory
- Microsoft Entra ID
- Microsoft 365
- Microsoft Azure
- Hybrid Identity
- PowerShell
- Enterprise Troubleshooting
- Security-aware Administration
- Professional Technical Documentation

The long-term career direction is to specialise in Microsoft Identity Engineering and cloud security while maintaining broad Microsoft infrastructure administration capability.

---

# Portfolio Overview

Modern Microsoft enterprise environments are no longer purely on-premises or purely cloud-based.

Instead, organisations increasingly operate **hybrid environments**, where traditional Windows infrastructure works alongside Microsoft cloud services.

This portfolio reflects that reality.

Rather than studying Microsoft technologies individually, each laboratory demonstrates how infrastructure, identity, cloud services, and security interact inside a modern enterprise environment.

The learning progression follows a logical administration pathway:

```
Windows Infrastructure
        ↓
Active Directory
        ↓
Microsoft Entra ID
        ↓
Hybrid Identity
        ↓
Microsoft 365
        ↓
Azure Administration
        ↓
Identity Security
        ↓
Detection Engineering
```

Each laboratory builds on previous knowledge while introducing progressively more advanced administration concepts.

---

# Portfolio Objectives

The primary objective of this repository is to demonstrate practical administration capability across interconnected Microsoft technologies.

The portfolio develops experience in:

- Windows Server administration
- Active Directory administration
- Microsoft Entra ID administration
- Microsoft 365 administration
- Azure administration
- Hybrid identity
- Identity and Access Management (IAM)
- PowerShell administration
- Enterprise troubleshooting
- Technical documentation
- Security-aware administration

Every laboratory follows a structured process based on implementation, validation, troubleshooting, investigation, and documentation.

The emphasis is placed on understanding *why* Microsoft technologies operate as they do rather than simply following configuration guides.

---

# Hybrid Laboratory Environment

This portfolio uses a **hybrid laboratory architecture** that combines local virtual infrastructure with Microsoft Azure.

This approach reflects how many real organisations operate while providing an efficient and sustainable learning environment.

The hybrid model also reduces cloud costs while allowing practical experience across both traditional and cloud-native technologies.

---

# Local Infrastructure

The local laboratory is hosted using **Oracle VirtualBox**.

VirtualBox provides a persistent Windows infrastructure for enterprise administration without consuming Azure compute resources.

The local environment hosts technologies including:

- Windows Server
- Windows 11
- Linux
- Active Directory
- DNS
- DHCP
- Group Policy
- File Services
- IIS
- PowerShell
- Enterprise troubleshooting scenarios

Using VirtualBox allows unrestricted experimentation, repeated rebuilds, and realistic infrastructure administration.

---

# Microsoft Azure Environment

Microsoft Azure is reserved for cloud-native services that cannot realistically be reproduced inside a local laboratory.

Azure services used throughout the portfolio include:

- Microsoft Entra ID
- Resource Groups
- Virtual Networks
- Network Security Groups
- Azure Storage
- Azure Key Vault
- Azure Monitor
- Log Analytics
- Azure Policy
- Azure Automation
- Azure Update Manager
- Microsoft Sentinel
- Azure Virtual Machines (when required)

Cloud virtual machines are deployed only for laboratories that specifically require Azure compute resources.

After each laboratory they are deallocated to minimise operational cost.

This mirrors good cloud administration practice within production environments.

---

# Laboratory Resource Strategy

The portfolio deliberately separates workloads between VirtualBox and Azure.

## Oracle VirtualBox

Used for:

- Windows Server
- Active Directory
- DNS
- DHCP
- Group Policy
- PowerShell
- Windows administration
- Linux administration
- Enterprise troubleshooting

The local infrastructure remains available continuously without cloud costs.

---

## Microsoft Azure

Used for:

- Microsoft Entra ID
- Azure Resource Management
- Azure networking
- Azure Storage
- Azure monitoring
- Azure governance
- Azure security
- Azure automation
- Hybrid identity
- Microsoft Sentinel

This strategy maximises practical experience while remaining sustainable within Microsoft Azure Free Account and Pay-As-You-Go limits.

It also reflects real-world hybrid Microsoft environments.

---

# Learning Methodology

Each laboratory follows a consistent methodology.

Every lab contains:

- Administrative scenario
- Objectives
- Environment preparation
- Implementation
- Validation
- Troubleshooting
- Evidence collection
- Lessons learned
- Technical documentation

This structure reinforces professional administrative practice rather than isolated technical exercises.

---

# Portfolio Roadmap

The portfolio progresses through seven major phases.

Each phase expands the scope of administration while building on previously acquired knowledge.

---

# Phase 1 — Identity Foundations ✅

Identity is the control plane of modern Microsoft environments.

For this reason, the portfolio begins with Microsoft Entra ID before expanding into broader infrastructure administration.

Completed laboratories establish practical understanding of:

- Authentication
- Authorisation
- Identity lifecycle
- RBAC
- Microsoft Graph
- Identity governance
- Administrative role validation
- Azure resource organisation

---

## Completed Laboratories

### 1.1 WSL2 Hybrid Security Laboratory Environment ✅

Created a Windows/Linux laboratory environment supporting identity analysis, authentication investigation, and security troubleshooting.

**Skills demonstrated**

- Hybrid laboratory environments
- Windows/Linux interoperability
- Security investigation
- Identity troubleshooting

---

### 1.2 Windows Authentication and Security Log Analysis ✅

Investigated Windows Security Event Logs to understand authentication behaviour and user activity.

**Skills demonstrated**

- Windows Event Viewer
- Authentication analysis
- Security monitoring
- Identity investigation

---

### 1.3 Microsoft Entra ID Authentication and RBAC Foundations ✅

Analysed Microsoft Entra ID authentication flows together with role-based access control.

**Skills demonstrated**

- Microsoft Entra ID
- Authentication
- RBAC
- Administrative permissions

---

### 1.4 Identity Lifecycle and Access Change Analysis ✅

Analysed identity lifecycle events using Microsoft audit logs.

**Skills demonstrated**

- Identity lifecycle
- Audit log analysis
- Governance
- Access tracking

---

### 1.5 Microsoft Entra ID Identity Operations: State vs Event Correlation ✅

Validated current Microsoft Entra ID configuration using Microsoft Graph and compared identity state against historical administrative events.

**Skills demonstrated**

- Microsoft Graph
- Identity validation
- Administrative investigation
- Event correlation

---

### 1.6 Microsoft Entra ID Identity Security and Governance Analysis ✅

Performed identity-focused security analysis covering governance, privileged access, and administrative security practices.

**Skills demonstrated**

- Identity governance
- Security analysis
- Administrative validation
- Identity-focused investigation

---

### 1.7 Global Administrator Role Assignment Validation ✅

Validated Microsoft Entra ID Global Administrator assignments and investigated apparent RBAC inconsistencies.

**Skills demonstrated**

- Privileged role validation
- RBAC analysis
- Administrative troubleshooting
- Identity consistency

---

### 1.8 Azure Foundation Lab: Resource Group Creation and Environment Baseline ✅

Created and validated the Azure Resource Group used as the management boundary for future cloud laboratories.

**Skills demonstrated**

- Azure Resource Groups
- Azure subscriptions
- Resource organisation
- Cloud environment preparation

---

# Phase 2 — Microsoft Infrastructure Administration

Having established identity foundations, the portfolio expands into traditional Microsoft infrastructure administration.

The objective is to develop the practical Windows Server knowledge expected from junior Microsoft Systems Administrators.

The majority of these laboratories are performed using the local VirtualBox environment, reflecting traditional enterprise infrastructure.

## Planned Laboratories

### 2.1 Windows Server Administration Foundations

**Platform:** Oracle VirtualBox

Topics:

- Windows Server deployment
- Administrative Tools
- Server Roles
- Features
- Services
- Event Viewer
- Local administration
- Windows troubleshooting

---

### 2.2 Active Directory Administration Fundamentals

**Platform:** Oracle VirtualBox

Topics:

- Active Directory Domain Services
- Domain Controllers
- Users
- Groups
- Organisational Units
- Administrative delegation
- Group Policy

---

### 2.3 PowerShell Administration Fundamentals

**Platform:** Oracle VirtualBox

Topics:

- PowerShell navigation
- Administrative cmdlets
- System information
- User management
- Basic automation
- Administrative scripting

---

### 2.4 Windows Server Security Fundamentals *(Planned)*

**Platform:** Oracle VirtualBox

Topics:

- Windows Firewall
- Event Logs
- Local Security Policy
- NTFS permissions
- Security auditing
- Administrative troubleshooting

---

# Phase 3 — Hybrid Microsoft Identity Administration

Modern Microsoft environments combine traditional Windows infrastructure with cloud identity services.

This phase demonstrates how Windows Server, Active Directory, Microsoft Entra ID, Microsoft 365, and Azure operate together within a hybrid enterprise environment.

Rather than treating each technology independently, the laboratories focus on understanding how identities, authentication, infrastructure, and cloud services interact throughout the enterprise.

The objective is to develop practical hybrid administration skills that bridge traditional infrastructure and modern cloud identity.

**Primary Platform**

- Oracle VirtualBox
- Microsoft Azure

---

## Planned Areas

- Active Directory and Microsoft Entra ID relationship
- Hybrid identity architecture
- Identity synchronisation concepts
- Authentication flows
- User lifecycle across environments
- Hybrid administration
- Administrative troubleshooting
- User and group management
- Identity validation

---

# Phase 4 — Microsoft 365 Administration

Microsoft 365 administration extends identity management into everyday enterprise operations.

This phase develops practical experience with Microsoft 365 administration tasks commonly performed by junior Microsoft administrators.

Identity management remains the central theme, connecting users, licences, groups, cloud applications, and device identity.

**Primary Platform**

- Microsoft 365
- Microsoft Entra ID
- Microsoft Azure

---

## Planned Areas

- User administration
- Group administration
- Licensing
- Microsoft 365 services
- Identity integration
- Device identity
- Administrative troubleshooting
- Operational support

---

# Phase 5 — Azure Infrastructure Administration (AZ-104 Alignment)

The Azure administration phase develops practical cloud administration capability aligned with the Microsoft Azure Administrator Associate certification.

Rather than deploying Azure resources unnecessarily, each laboratory focuses on understanding operational administration, governance, monitoring, and resource lifecycle management.

The Azure Resource Group established during Lab 1.8 provides the management boundary for all future Azure resources.

---

## 5.1 Azure Virtual Network Architecture

**Platform**

Microsoft Azure

**Skills Demonstrated**

- Azure Virtual Networks
- Subnets
- Network segmentation
- Address planning
- Infrastructure design

---

## 5.2 Azure Network Security Groups

**Platform**

Microsoft Azure

**Skills Demonstrated**

- Network Security Groups
- Traffic filtering
- Cloud access control
- Security configuration
- Network administration

---

## 5.3 Azure Virtual Machine Administration

**Platform**

Microsoft Azure

**Skills Demonstrated**

- Azure Virtual Machines
- Compute administration
- Resource lifecycle
- Virtual machine management
- Operational administration

Azure virtual machines are deployed only when required for specific laboratory exercises and are deallocated immediately after use to minimise operational costs.

---

## 5.4 Azure Storage Administration

**Platform**

Microsoft Azure

**Skills Demonstrated**

- Storage Accounts
- Blob Storage
- Access management
- Storage configuration
- Data protection

---

## 5.5 Azure Monitoring and Operational Troubleshooting

**Platform**

Microsoft Azure

**Skills Demonstrated**

- Azure Monitor
- Activity Logs
- Log Analytics
- Operational visibility
- Troubleshooting methodology

---

## 5.6 Azure Key Vault Administration *(Planned)*

**Platform**

Microsoft Azure

**Skills Demonstrated**

- Secret management
- Certificate management
- Secure administration
- Key management

---

## 5.7 Azure Policy and Governance *(Planned)*

**Platform**

Microsoft Azure

**Skills Demonstrated**

- Azure Policy
- Governance
- Compliance
- Resource standardisation

---

## 5.8 Azure Automation and Update Manager *(Planned)*

**Platform**

Microsoft Azure

**Skills Demonstrated**

- Azure Automation
- Update Manager
- Scheduled administration
- Operational maintenance

---

# Phase 6 — Microsoft Enterprise Administration Integration

This phase combines all previous technologies into realistic enterprise administration scenarios.

Rather than focusing on individual services, the laboratories demonstrate how Microsoft infrastructure is administered in production environments.

The emphasis is placed on investigation, troubleshooting, validation, documentation, and operational reasoning.

**Hybrid Platform**

- Windows Server
- Active Directory
- Microsoft Entra ID
- Microsoft 365
- Microsoft Azure

---

## Planned Scenarios

- User lifecycle management
- Authentication troubleshooting
- Access troubleshooting
- Resource access validation
- Administrative documentation
- Hybrid administration workflows
- Configuration validation

---

# Phase 7 — Identity Security and Cloud Security Evolution

The final phase builds upon Microsoft administration foundations to develop identity-focused cloud security capability.

This represents the long-term progression from Microsoft Systems Administration towards Identity Engineering and Detection Engineering.

The emphasis shifts from administration to security operations, monitoring, governance, and investigation.

**Hybrid Platform**

- Windows Server
- Microsoft Entra ID
- Azure
- Microsoft Sentinel

---

## Planned Areas

- Conditional Access
- Privileged Identity Management (PIM)
- Identity Governance
- Access Reviews
- Microsoft Defender
- Microsoft Sentinel
- Identity monitoring
- Identity investigation
- Detection engineering fundamentals

---

# Technical Focus Areas

## Microsoft Infrastructure Administration

- Windows Server
- Windows administration
- Active Directory
- Enterprise infrastructure
- Microsoft administration
- Enterprise troubleshooting

---

## Microsoft 365 Administration

- User administration
- Group management
- Licensing
- Cloud services
- Device identity
- Identity integration

---

## Microsoft Entra ID Administration

- Authentication
- Identity lifecycle
- Role-Based Access Control (RBAC)
- Identity governance
- Privileged access
- Administrative validation

---

## Microsoft Azure Administration

- Resource Groups
- Virtual Networks
- Virtual Machines
- Storage
- Monitoring
- Governance
- Automation
- Operational management

---

## Automation and Operations

- PowerShell
- Administrative automation
- Log analysis
- Configuration validation
- Troubleshooting
- Technical documentation

---

# Skills Demonstrated

## Infrastructure Administration

- Windows Server administration
- Active Directory administration
- Microsoft infrastructure management
- Azure resource management
- Enterprise troubleshooting

---

## Identity Administration

- Microsoft Entra ID
- Authentication
- Identity lifecycle
- RBAC
- Identity governance
- Privileged access management

---

## Security Operations

- Security log analysis
- Audit investigation
- Identity behaviour analysis
- Evidence-based troubleshooting
- Operational documentation

---

## Automation

- PowerShell
- Administrative scripting
- Configuration management
- Automation fundamentals

---

# Microsoft Enterprise Architecture

```

Microsoft Infrastructure
│
├── Windows Server
├── Active Directory
├── DNS
├── DHCP
├── File Services
├── Group Policy
└── PowerShell
│
▼
Hybrid Identity
│
├── Microsoft Entra ID
├── Microsoft 365
└── Azure
│
▼
Cloud Administration
│
├── Resource Groups
├── Networking
├── Compute
├── Storage
├── Monitoring
├── Governance
└── Automation
│
▼
Identity Security
│
├── Conditional Access
├── Identity Governance
├── Microsoft Defender
└── Microsoft Sentinel
│
▼
Detection Engineering

```

---

# Evidence-Based Learning Approach

Every laboratory follows a consistent professional methodology.

Each exercise demonstrates:

- A realistic administrative scenario
- Practical implementation
- Configuration validation
- Troubleshooting
- Evidence collection
- Technical reasoning
- Professional documentation
- Lessons learned

The objective is to understand how Microsoft technologies are administered, supported, secured, and integrated under realistic operational conditions.

---

# Certification Alignment

## Microsoft AZ-104 — Azure Administrator Associate

Focus Areas

- Azure administration
- Networking
- Compute
- Storage
- Monitoring
- Governance
- Identity integration

---

## Microsoft SC-300 — Identity and Access Administrator Associate

Focus Areas

- Microsoft Entra ID
- Authentication
- Identity lifecycle
- RBAC
- Identity governance
- Privileged access

Future certifications will be selected according to practical career progression and demonstrated technical capability.

---

# Career Direction

## Current Objective

**Junior Microsoft Systems Administrator with IAM Strength**

Developing practical capability across:

- Windows Server
- Active Directory
- Microsoft Entra ID
- Microsoft 365
- Microsoft Azure
- Hybrid identity
- PowerShell
- Enterprise troubleshooting
- Security-aware administration

---

## Long-Term Objective

Progression towards:

- Microsoft Identity Engineering
- Identity & Access Management (IAM)
- Cloud Administration
- Cloud Security
- Identity-focused Detection Engineering

---

# Portfolio Development Philosophy

The portfolio follows a structured progression from infrastructure administration towards identity-focused cloud security.

```

Windows Server
↓

Active Directory
↓

Microsoft Entra ID
↓

Hybrid Identity
↓

Microsoft 365
↓

Azure Administration
↓

Identity Security
↓

Detection Engineering

```

Each phase builds directly upon previous knowledge.

The objective is not simply to learn individual Microsoft technologies but to understand how they work together to support secure, reliable, and scalable enterprise environments.

---

# Core Principles

### Microsoft infrastructure provides the foundation.

Windows Server, Active Directory, Microsoft 365, and Azure form the enterprise platform on which organisations operate.

### Identity controls access.

Authentication, authorisation, RBAC, and identity governance determine who can access enterprise resources.

### Security validates behaviour.

Monitoring, logging, investigation, governance, and operational visibility help ensure systems remain secure and compliant.

### Practical experience drives professional growth.

Hands-on laboratories, structured troubleshooting, evidence-based validation, and clear technical documentation develop the skills required for modern Microsoft administration.

---

# Repository Commitment

Every completed laboratory included in this repository demonstrates:

- Practical implementation
- Administrative reasoning
- Configuration validation
- Troubleshooting methodology
- Professional documentation
- Lessons learned

This portfolio is intended to reflect the continuous development of practical Microsoft administration capability, progressing from foundational infrastructure administration towards identity-focused cloud security and detection engineering.

