# Microsoft Infrastructure Administration & Identity Portfolio

Microsoft 365 | Windows Server | Active Directory | Microsoft Entra ID | Microsoft Azure | PowerShell

---

# Status

Active Development

A structured, hands-on portfolio demonstrating practical Microsoft infrastructure administration across on-premises, hybrid, and cloud environments.

---

# Career Focus

## Junior Microsoft Systems Administrator with Identity and Access Management (IAM) Strength

This repository documents the progressive development of practical Microsoft enterprise administration skills through structured laboratory exercises and technical documentation.

The objective is to build the practical knowledge expected of a junior Microsoft Systems Administrator while establishing a strong foundation in hybrid identity, cloud administration, and security-aware operations.

The portfolio focuses on developing capability across:

- Windows Server Administration
- Active Directory
- Microsoft Entra ID
- Microsoft 365
- Microsoft Azure
- Hybrid Identity
- Identity and Access Management (IAM)
- PowerShell Administration
- Enterprise Troubleshooting
- Technical Documentation

The long-term objective is to progress naturally from Microsoft infrastructure administration into Microsoft Identity Engineering and cloud security.

---

# Portfolio Overview

Modern Microsoft enterprise environments are no longer built solely around on-premises infrastructure or cloud services.

Instead, organisations increasingly operate hybrid environments where Windows Server, Active Directory, Microsoft Entra ID, Microsoft 365, and Microsoft Azure function together as a unified enterprise platform.

This portfolio reflects that operational reality.

Rather than studying Microsoft technologies independently, each laboratory demonstrates how infrastructure, identity, cloud services, administration, and security interact within modern Microsoft environments.

The learning progression follows a structured path:

```text
Windows Infrastructure
        │
        ▼
Active Directory
        │
        ▼
Microsoft Entra ID
        │
        ▼
Hybrid Identity
        │
        ▼
Microsoft 365 Administration
        │
        ▼
Azure Administration
        │
        ▼
Enterprise Administration
        │
        ▼
Identity Security
        │
        ▼
Detection Engineering
```

Each laboratory builds directly upon previous knowledge while introducing progressively more advanced administration concepts.

---

# Portfolio Objectives

The primary objective of this repository is to demonstrate practical administration capability across the Microsoft enterprise ecosystem.

The portfolio develops practical experience in:

- Windows Server administration
- Active Directory administration
- Microsoft Entra ID administration
- Microsoft 365 administration
- Azure administration
- Hybrid identity
- Identity and Access Management (IAM)
- PowerShell administration
- Enterprise troubleshooting
- Security-aware administration
- Professional technical documentation

Every laboratory follows the same structured methodology:

- Planning
- Implementation
- Validation
- Troubleshooting
- Evidence collection
- Documentation
- Lessons learned

The emphasis is placed on understanding why Microsoft technologies operate as they do rather than simply following configuration guides.

---

# Hybrid Laboratory Architecture

This portfolio uses a hybrid laboratory architecture combining local virtual infrastructure with Microsoft Azure.

This approach reflects how many organisations operate while providing an efficient and sustainable learning environment.

It enables practical experience across both traditional Microsoft infrastructure and modern cloud administration without relying exclusively on Azure virtual machines.

---

# Local Infrastructure

Primary Platform

Oracle VirtualBox

The local environment provides persistent enterprise infrastructure that can be rebuilt, modified, and tested without consuming Azure compute resources.

Technologies hosted locally include:

- Windows Server
- Windows 11
- Ubuntu Linux
- Active Directory Domain Services
- DNS
- DHCP
- Group Policy
- File Services
- IIS
- PowerShell
- Windows administration
- Enterprise troubleshooting scenarios

Running these workloads locally enables unrestricted experimentation while closely reflecting traditional enterprise infrastructure.

---

# Microsoft Azure

Azure is reserved for services that are cloud-native or where practical experience requires Microsoft-hosted infrastructure.

Azure resources used throughout this portfolio include:

- Microsoft Entra ID
- Azure Resource Groups
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

Azure virtual machines are deployed only when a laboratory specifically requires cloud compute resources.

After validation they are deallocated to minimise operational costs.

This reflects good cloud administration practice while remaining within the limits of the Azure Free Account and Pay-As-You-Go model.

---

# Laboratory Resource Strategy

The portfolio deliberately separates workloads between Oracle VirtualBox and Microsoft Azure.

This approach maximises practical experience while avoiding unnecessary cloud expenditure.

| Technology | Primary Platform |
|------------|------------------|
| Windows Server | Oracle VirtualBox |
| Active Directory | Oracle VirtualBox |
| DNS | Oracle VirtualBox |
| DHCP | Oracle VirtualBox |
| Group Policy | Oracle VirtualBox |
| PowerShell | Oracle VirtualBox |
| Windows Administration | Oracle VirtualBox |
| Linux Administration | Oracle VirtualBox |
| Enterprise Troubleshooting | Oracle VirtualBox |
| Microsoft Entra ID | Microsoft Azure |
| Azure Administration | Microsoft Azure |
| Azure Networking | Microsoft Azure |
| Azure Storage | Microsoft Azure |
| Azure Monitoring | Microsoft Azure |
| Azure Governance | Microsoft Azure |
| Azure Automation | Microsoft Azure |
| Microsoft Sentinel | Microsoft Azure |
| Hybrid Identity | Oracle VirtualBox and Microsoft Azure |

This strategy reflects modern enterprise environments where traditional infrastructure and cloud services operate together rather than replacing one another.

---

# Learning Methodology

Every laboratory follows a consistent professional workflow.

Each laboratory includes:

- Administrative scenario
- Objectives
- Environment preparation
- Implementation
- Validation
- Troubleshooting
- Evidence collection
- Lessons learned
- Professional documentation

This methodology encourages operational thinking rather than simply completing technical exercises.

The emphasis is placed on administrative decision-making, validation, troubleshooting, and evidence-based investigation.

---

# Repository Roadmap

The portfolio progresses through seven structured phases.

Each phase expands the scope of Microsoft administration while building directly upon previous knowledge.

| Phase | Status |
|-------|--------|
| Identity Foundations | Completed |
| Microsoft Infrastructure Administration | In Progress |
| Hybrid Microsoft Identity Administration | Planned |
| Microsoft 365 Administration | Planned |
| Azure Infrastructure Administration (AZ-104 Alignment) | Planned |
| Microsoft Enterprise Administration Integration | Planned |
| Identity Security and Cloud Security Evolution | Future |

This progression reflects how Microsoft administration skills naturally evolve from infrastructure management towards identity engineering and cloud security.

---

# Phase 1 — Identity Foundations

Identity forms the control plane of modern Microsoft environments.

For this reason, the portfolio begins with Microsoft Entra ID before expanding into broader infrastructure administration.

These laboratories establish practical understanding of:

- Authentication
- Authorisation
- Identity lifecycle
- Role-Based Access Control (RBAC)
- Microsoft Graph
- Identity governance
- Privileged access validation
- Azure resource organisation

The knowledge gained during this phase provides the foundation for every subsequent laboratory.

---

# Completed Laboratories

## 1.1 WSL2 Hybrid Security Laboratory Environment

Created a Windows/Linux laboratory environment supporting authentication analysis, identity investigation, and security troubleshooting.

Skills demonstrated:

- Hybrid laboratory environments
- Windows/Linux interoperability
- Identity troubleshooting
- Security investigation methodology

---

## 1.2 Windows Authentication and Security Log Analysis

Investigated Windows Security Event Logs to understand authentication behaviour, user sessions, and security events.

Skills demonstrated:

- Windows Event Viewer
- Authentication analysis
- Security monitoring
- Identity investigation

---

## 1.3 Microsoft Entra ID Authentication and RBAC Foundations

Analysed Microsoft Entra ID authentication flows together with Role-Based Access Control.

Skills demonstrated:

- Microsoft Entra ID administration
- Authentication concepts
- RBAC fundamentals
- Administrative permissions

---

## 1.4 Identity Lifecycle and Access Change Analysis

Performed audit log analysis to understand identity lifecycle events and access changes.

Skills demonstrated:

- Identity lifecycle management
- Audit log analysis
- Identity governance
- Access tracking

---

# 1.5 Microsoft Entra ID Identity Operations: State vs Event Correlation

Validated the current Microsoft Entra ID configuration using Microsoft Graph API and compared the present identity state with historical administrative events recorded within audit logs.

The objective was to understand the relationship between current identity configuration and historical identity activity.

Skills demonstrated:

- Microsoft Graph fundamentals
- Identity state validation
- Event correlation
- Identity troubleshooting

---

# 1.6 Microsoft Entra ID Identity Security and Governance Analysis

Performed identity-focused security analysis covering governance, administrative roles, privileged access, and security best practices.

The laboratory focused on understanding how identity governance contributes to secure Microsoft enterprise environments.

Skills demonstrated:

- Identity governance
- Administrative security
- Security analysis
- Identity-focused investigation

---

# 1.7 Microsoft Entra ID Global Administrator Role Assignment Validation

Validated Global Administrator role assignments within Microsoft Entra ID and investigated whether duplicate portal entries represented genuine RBAC duplication or only a user interface representation.

The investigation relied on Microsoft Graph identity attributes together with privileged role assignments to validate administrative consistency.

Skills demonstrated:

- Microsoft Entra ID administration
- Privileged role validation
- RBAC analysis
- Administrative troubleshooting
- Identity consistency validation

---

# 1.8 Azure Foundation Lab: Resource Group Creation and Environment Baseline

Created and validated an Azure Resource Group to establish the management boundary for future Azure laboratories.

The laboratory prepared the Azure environment for networking, compute, storage, monitoring, governance, and automation exercises.

Skills demonstrated:

- Azure Resource Groups
- Azure subscriptions
- Azure resource organisation
- Azure Portal administration
- Cloud environment preparation

---

# Phase 2 — Microsoft Infrastructure Administration Foundations

Having established the identity foundation, the portfolio now expands into broader Microsoft infrastructure administration.

The objective is to develop the practical Windows Server knowledge expected of junior Microsoft Systems Administrators while strengthening understanding of the enterprise infrastructure that supports modern Microsoft environments.

Most laboratories within this phase are performed using Oracle VirtualBox, allowing unrestricted experimentation without consuming Azure compute resources.

---

## 2.1 Windows Server Administration Foundations

Platform

Oracle VirtualBox

Objective

Develop practical Windows Server administration skills required for Microsoft infrastructure support roles.

Planned areas:

- Windows Server installation
- Server roles and features
- Administrative Tools
- Computer Management
- Services management
- Event Viewer
- Windows administration
- Local user administration
- System troubleshooting

---

## 2.2 Active Directory Administration Fundamentals

Platform

Oracle VirtualBox

Objective

Develop practical administration skills using Active Directory Domain Services (AD DS).

Planned areas:

- Active Directory Domain Services
- Domain Controllers
- Forests
- Domains
- Organisational Units
- Users
- Groups
- Administrative delegation
- Group Policy
- Permissions management

---

## 2.3 PowerShell Administration Fundamentals

Platform

Oracle VirtualBox

Objective

Develop practical PowerShell administration capability for enterprise Microsoft environments.

Planned areas:

- PowerShell navigation
- Cmdlets
- Objects and pipelines
- System information gathering
- Service management
- User administration
- Basic scripting
- Administrative automation

---

## 2.4 Windows Server Security Fundamentals

Platform

Oracle VirtualBox

Objective

Develop practical understanding of Windows Server security administration.

Planned areas:

- Windows Defender Firewall
- Windows Security
- Local Security Policy
- NTFS permissions
- Event Logs
- Security auditing
- Administrative troubleshooting

---

# Phase 3 — Hybrid Microsoft Identity Administration

Modern Microsoft environments combine traditional infrastructure with cloud identity services.

This phase demonstrates how Windows Server, Active Directory, Microsoft Entra ID, Microsoft 365, and Azure operate together within hybrid enterprise environments.

The objective is to understand identity management across both on-premises and cloud platforms.

Platform

Oracle VirtualBox and Microsoft Azure

Planned areas:

- Active Directory and Microsoft Entra ID relationship
- Hybrid identity architecture
- Identity synchronisation concepts
- Authentication flows
- User lifecycle management
- Hybrid administration
- Identity validation
- Administrative troubleshooting

---

# Phase 4 — Microsoft 365 Administration

Microsoft 365 administration extends identity management into day-to-day enterprise operations.

This phase develops practical experience with the administrative tasks commonly performed by junior Microsoft administrators.

Identity management remains the central theme, connecting users, licences, cloud services, applications, and devices.

Platform

Microsoft 365 and Microsoft Azure

Planned areas:

- User administration
- Group administration
- Licensing
- Microsoft 365 services
- Identity integration
- Device identity
- Administrative troubleshooting
- Operational support

---

# Phase 5 — Azure Infrastructure Administration

This phase develops practical Microsoft Azure administration aligned with the Microsoft Azure Administrator Associate (AZ-104) certification.

Rather than deploying unnecessary resources, every laboratory focuses on operational administration, governance, monitoring, security, and resource lifecycle management.

The Azure Resource Group established in Lab 1.8 provides the management boundary for all future Azure laboratories.

---

## 5.1 Azure Virtual Network Architecture

Platform

Microsoft Azure

Skills demonstrated:

- Azure Virtual Networks
- Address planning
- Subnet design
- Network segmentation
- Infrastructure planning

---

## 5.2 Azure Network Security Groups

Platform

Microsoft Azure

Skills demonstrated:

- Network Security Groups
- Cloud access control
- Traffic filtering
- Azure security configuration
- Network administration

---

## 5.3 Azure Virtual Machine Administration

Platform

Microsoft Azure

Skills demonstrated:

- Azure Virtual Machines
- Compute administration
- Resource lifecycle management
- Operational administration
- Infrastructure management

Azure virtual machines are deployed only when required by a laboratory and are deallocated after validation to minimise operational costs.

---

## 5.4 Azure Storage Administration

Platform

Microsoft Azure

Skills demonstrated:

- Storage Accounts
- Blob Storage
- File Storage
- Data management
- Access control
- Cloud storage administration

---

## 5.5 Azure Monitoring and Operational Troubleshooting

Platform

Microsoft Azure

Skills demonstrated:

- Azure Monitor
- Activity Logs
- Log Analytics
- Operational visibility
- Troubleshooting methodology

---

## 5.6 Azure Key Vault Administration

Platform

Microsoft Azure

Planned areas:

- Secret management
- Certificate management
- Key management
- Secure administration

---

## 5.7 Azure Policy and Governance

Platform

Microsoft Azure

Planned areas:

- Azure Policy
- Governance
- Compliance
- Resource standardisation

---

## 5.8 Azure Automation and Update Manager

Platform

Microsoft Azure

Planned areas:

- Azure Automation
- Update Manager
- Scheduled administration
- Operational maintenance

---

# Phase 6 — Microsoft Enterprise Administration Integration

This phase combines the knowledge developed throughout the portfolio into realistic enterprise administration scenarios.

Rather than focusing on individual Microsoft technologies, the laboratories demonstrate how Windows Server, Active Directory, Microsoft Entra ID, Microsoft 365, and Azure operate together within modern enterprise environments.

The objective is to develop practical administrative judgement by implementing, validating, troubleshooting, and documenting complete Microsoft administration workflows.

Platform

Oracle VirtualBox and Microsoft Azure

Planned areas:

- User lifecycle management across multiple platforms
- Identity troubleshooting
- Authentication troubleshooting
- Resource access validation
- Hybrid administration workflows
- Operational documentation
- Enterprise support scenarios
- Administrative best practices

---

# Phase 7 — Identity Security and Cloud Security Evolution

The final phase builds upon the Microsoft administration foundation developed throughout the portfolio.

Rather than treating security as a separate discipline, this phase demonstrates how security naturally evolves from understanding infrastructure, identity, administration, and operational behaviour.

The objective is to develop practical capability in identity-focused cloud security.

Platform

Microsoft Azure

Planned areas:

- Conditional Access
- Privileged Identity Management (PIM)
- Identity Governance
- Access Reviews
- Microsoft Defender for Cloud
- Microsoft Sentinel
- Identity monitoring
- Security investigations
- Identity-based Detection Engineering

---

# Technical Focus Areas

## Microsoft Infrastructure Administration

- Windows Server administration
- Windows administration
- Active Directory
- DNS
- DHCP
- Group Policy
- File Services
- IIS
- Enterprise troubleshooting
- Administrative tools

---

## Microsoft Entra ID and Identity Administration

- Authentication
- Authorisation
- Identity lifecycle
- Role-Based Access Control (RBAC)
- Microsoft Graph
- Identity governance
- Administrative role management
- Hybrid identity
- Privileged access validation

---

## Microsoft Azure Administration

- Resource Groups
- Virtual Networks
- Network Security Groups
- Azure Virtual Machines
- Azure Storage
- Azure Key Vault
- Azure Monitor
- Azure Policy
- Azure Automation
- Azure Update Manager
- Log Analytics
- Governance
- Operational administration

---

## Microsoft 365 Administration

- User administration
- Group administration
- Licensing
- Identity integration
- Administrative support
- Service management
- Operational troubleshooting

---

## PowerShell Administration

- PowerShell fundamentals
- Administrative automation
- System administration
- Configuration validation
- Operational scripting

---

## Security and Operations

- Authentication analysis
- Identity investigation
- Windows Event Log analysis
- Azure Activity Log analysis
- Administrative troubleshooting
- Evidence-based investigation
- Technical documentation
- Security-aware administration

---

# Architecture Model

This portfolio reflects how modern Microsoft enterprise environments operate as interconnected systems.

```text
                    Security
                         │
                         ▼
         Microsoft Sentinel
         Microsoft Defender
         Monitoring
         Investigation
                         │
                         ▼
                  Identity Layer
          Microsoft Entra ID
          Authentication
          Authorisation
          RBAC
          Identity Governance
                         │
                         ▼
               Infrastructure Layer
      Windows Server
      Active Directory
      Microsoft 365
      Azure Infrastructure
      PowerShell
```

The architecture follows three fundamental principles:

Infrastructure provides enterprise services.

Identity controls access to those services.

Security validates behaviour across the entire environment.

---

# Evidence-Based Learning Approach

Every laboratory within this repository is based upon controlled Microsoft environments rather than theoretical demonstrations.

Each laboratory includes:

- A realistic administrative scenario
- Defined objectives
- Structured implementation
- Configuration validation
- Troubleshooting
- Evidence collection
- Technical documentation
- Lessons learned

This methodology reflects how Microsoft administrators work within operational environments.

The emphasis is placed on understanding administrative reasoning rather than simply completing configuration tasks.

---

# Certification Alignment

## Microsoft Azure Administrator Associate (AZ-104)

The Azure administration section aligns with the practical knowledge expected of Azure Administrators.

Primary focus areas include:

- Azure administration
- Compute
- Networking
- Storage
- Monitoring
- Governance
- Identity integration

---

## Microsoft Identity and Access Administrator (SC-300)

The identity administration section aligns with Microsoft Entra ID administration and hybrid identity management.

Primary focus areas include:

- Authentication
- Identity lifecycle
- RBAC
- Identity governance
- Hybrid identity
- Administrative permissions
- Microsoft Graph

Future certifications will be selected according to practical career progression rather than certification collection alone.

---

# Career Direction

## Current Objective

Junior Microsoft Systems Administrator with Identity and Access Management (IAM) strength.

Current development focuses on:

- Windows Server
- Active Directory
- Microsoft Entra ID
- Microsoft 365
- Azure
- Hybrid identity
- PowerShell
- Enterprise troubleshooting
- Security-aware administration

---

## Long-Term Direction

The portfolio is designed to support progression towards:

- Microsoft Identity Engineering
- Identity and Access Management (IAM)
- Azure Administration
- Cloud Security
- Identity-focused Detection Engineering

Each stage builds directly upon the previous one, creating a logical progression from infrastructure administration to identity-focused cloud security.

---

# Repository Structure

The laboratories are organised according to a progressive learning pathway.

```text
1. Identity Foundations
      ↓
2. Microsoft Infrastructure Administration
      ↓
3. Hybrid Microsoft Identity Administration
      ↓
4. Microsoft 365 Administration
      ↓
5. Azure Infrastructure Administration
      ↓
6. Microsoft Enterprise Administration Integration
      ↓
7. Identity Security and Cloud Security Evolution
```

This structure reflects how Microsoft enterprise technologies are deployed, administered, and secured within modern organisations.

---

# Portfolio Philosophy

This repository is built around one central principle:

Understanding infrastructure first creates stronger administrators and better security professionals.

The portfolio deliberately develops broad Microsoft administration capability before progressing into specialist identity engineering and cloud security.

Rather than learning isolated technologies, every laboratory contributes to a connected understanding of how Microsoft enterprise environments function as complete systems.

The objective is to become a Microsoft professional who understands not only how to configure enterprise technologies, but also how to troubleshoot them, secure them, and explain them through clear technical documentation.

---

# Core Principles

Microsoft infrastructure provides the operational foundation.

Identity controls access to enterprise resources.

Cloud services extend enterprise capability.

Security validates administrative and user behaviour.

Evidence-based investigation supports effective troubleshooting.

Practical experience develops professional capability.

Continuous learning drives long-term progression.

---

# Repository Status

This portfolio is under continuous development.

New laboratories will be added as practical skills expand across Microsoft infrastructure administration, hybrid identity, Azure administration, Microsoft 365, and identity-focused cloud security.

The repository is intended to demonstrate consistent technical progression through practical implementation, structured investigation, validation, troubleshooting, and professional documentation.

---
