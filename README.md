# IAM Engineering Progression Map — Identity Security Engineering (Microsoft Entra ID)

Identity & Access Management (IAM) | Microsoft Entra ID | Azure Cloud Security | SOC Fundamentals

---

## Overview

This portfolio demonstrates a structured progression in identity security engineering using Microsoft Entra ID, Windows authentication telemetry, and RBAC-based access control analysis.

The focus is on understanding how identity behaves across systems — from authentication and access assignment through to governance and identity drift over time.

Rather than treating IAM as isolated concepts, this work analyses identity as a system that evolves continuously and can introduce risk through misalignment, accumulation of access, or behavioural drift.

---

## Core Focus Areas

- Microsoft Entra ID identity lifecycle (provisioning, authentication, access governance)
- Authentication and sign-in behaviour analysis
- Role-Based Access Control (RBAC) and group-based access design
- Identity drift and access evolution over time
- Evidence-based IAM analysis using exported logs

---

## IAM Engineering Approach

Each investigation follows a structured reasoning model:

- Observe identity behaviour (authentication, access changes, system events)
- Interpret why the behaviour occurred within the IAM system
- Map it to IAM controls (RBAC, policies, lifecycle rules, governance)
- Identify risks, inconsistencies, or drift over time
- Document findings in a reproducible, evidence-based format

This approach prioritises reasoning over tooling, focusing on identity as a dynamic system rather than static configuration.

---

## Projects

### 01 — Portfolio Hub
Overview of IAM engineering progression and lab structure.

### 02 — WSL2 Hybrid Lab Foundations
Infrastructure setup for identity security experimentation in a lightweight hybrid environment.

### 03 — Endpoint Authentication Behaviour Analysis
Windows Security Event Log analysis focused on authentication patterns and identity telemetry.

### 04 — Entra ID Authentication & RBAC
Analysis of authentication vs authorization within Microsoft Entra ID, focusing on RBAC logic and access control.

### 05 — Identity Drift & Governance Analysis
Investigation of identity state changes over time using audit logs and group membership evolution.

---

## Evidence-Based Work

All labs are built using exported logs, reproducible environments, and structured analysis.

The focus is on observable identity behaviour rather than theoretical scenarios, reflecting how IAM issues appear in real systems.

---

## Career Direction

Current focus areas:

- Microsoft Entra ID (SC-300 aligned learning path)
- Identity and Access Management operations
- Authentication and access control analysis
- Early-stage identity governance and risk awareness
- Progression toward cloud security and detection engineering roles

---

## Final Note

Identity security is not only about configuring access correctly at a point in time.

It is about understanding how identity behaves, evolves, and sometimes drifts into unintended risk across systems.

That is the capability this portfolio is designed to demonstrate.
