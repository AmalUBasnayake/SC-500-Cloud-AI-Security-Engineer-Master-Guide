<p align="center">
  <img src="assets/sc500-master-guide-banner.png" alt="SC-500 Cloud & AI Security Engineer Master Guide">
</p>

<h1 align="center">
SC-500 Cloud & AI Security Engineer - Master Guide
</h1>

<p align="center">
A practical, continuously updated guide covering Cloud & AI Security,
Microsoft Security, hands-on labs, detection, investigation, response,
automation, and exam preparation.
</p>

<p align="center">

<img src="https://img.shields.io/badge/Microsoft-SC--500-0078D4?style=for-the-badge&logo=microsoft">
<img src="https://img.shields.io/badge/Cloud%20Security-Azure-0078D4?style=for-the-badge&logo=microsoftazure">
<img src="https://img.shields.io/badge/AI%20Security-Focused-00A4EF?style=for-the-badge">
<img src="https://img.shields.io/badge/Hands--On-Labs-111827?style=for-the-badge">
<img src="https://img.shields.io/badge/Exam-Preparation-111827?style=for-the-badge">

</p>

# 🛡️ SC-500 Cloud & AI Security Engineer - Master Guide

> A practical, continuously updated learning and hands-on engineering guide for **Microsoft Certified: Cloud and AI Security Engineer Associate (SC-500)**.

This repository is a living resource built around a practical engineering approach:

**Concept → Architecture → Microsoft Security Service → Hands-on Lab → Detection → Investigation → Response → Automation → Exam & Interview Preparation**

---

## 🎯 Purpose

This guide connects **SC-500 exam knowledge with real-world Cloud & AI Security Engineering**.

The guide connects:

- 🔐 Identity & Access
- 🗄️ Data & Secrets
- 🌐 Network Security
- 🤖 AI Security
- 🖥️ Compute & Application Security
- 🛡️ Microsoft Defender for Cloud
- 🔎 Microsoft Sentinel
- 🚨 Detection & Incident Response
- ⚙️ Automation
- 🤖 Microsoft Security Copilot
- 📋 Governance & Security Architecture

The study approach follows **What it is → How it works → Key settings → Exam traps**, followed by hands-on implementation and revision.

---

# 🧭 Learning Roadmap

## 01 — Identity, Access & Governance

- Microsoft Entra ID
- Privileged Identity Management (PIM)
- Conditional Access
- MFA & Passwordless Authentication
- Authentication Strength
- Application Identities
- App Registrations vs Enterprise Applications
- OAuth Permissions & Consent
- Managed Identities
- Azure Key Vault
- Azure Policy
- Azure RBAC
- Resource Locks
- Backup Security
- Infrastructure as Code Security

### Core Engineering Questions

- Who is requesting access?
- What resource is being accessed?
- What level of privilege is actually required?
- Can standing privilege be replaced with just-in-time access?
- Can secrets be eliminated with managed identity?
- Can access be restricted with Conditional Access?
- Can configuration be enforced with Azure Policy?

---

## 02 — Storage, Database & Network Security

- Azure Storage Security
- Storage Firewall
- SAS & Authorization
- Encryption & Data Protection
- Azure SQL Security
- Microsoft Defender for Databases
- Network Security Groups
- Application Security Groups
- Azure Virtual Network Manager
- Virtual WAN Security
- VPN Security
- Microsoft Entra Private Access
- Private Endpoints
- Private Link
- Azure Firewall
- Network Watcher
- DDoS Protection
- Web Application Firewall

### Core Engineering Questions

- Is the data publicly reachable?
- Can private connectivity replace public exposure?
- Which identity or authorization mechanism should access the data?
- Which network control should enforce the boundary?
- How will network activity be monitored and investigated?

---

## 03 — AI, Compute & Application Security

### 🤖 AI Security

- Microsoft Copilot & AI application security
- Microsoft Purview DSPM
- Overshared SharePoint data
- Copilot Studio real-time protection
- Microsoft Entra Agent ID
- AI Gateway in Azure API Management
- Microsoft Foundry
- Defender for AI Services
- AI security guardrails
- Data & AI security
- Agent security
- AI runtime protection
- Defender XDR blast-radius analysis
- Microsoft 365 admin center / Agent management

### 🖥️ Compute Security

- Azure Virtual Machines
- Disk Encryption
- Trusted Launch
- Secure Boot
- vTPM
- Integrity Monitoring
- Azure Bastion
- Just-in-Time VM Access
- Azure Arc
- Defender for Servers
- Vulnerability Management
- Agentless Scanning
- Containers
- Azure Kubernetes Service (AKS)
- Azure Container Registry (ACR)
- Azure Container Instances (ACI)
- Container Apps
- Azure Functions
- Logic Apps
- Azure App Service
- Web Application Firewall
- API Management

### Core Engineering Questions

- What workload generated the activity?
- Which identity initiated the request?
- Was the activity expected?
- Which model, agent, application, or endpoint was involved?
- What data was exposed or accessed?
- What security controls can reduce the attack surface?
- How can the activity be detected and investigated?

---

# 04 — Security Posture, Detection & Response

## 🛡️ Microsoft Defender for Cloud

- Cloud Security Posture Management (CSPM)
- Security Recommendations
- Secure Score
- Regulatory Compliance
- Security Standards
- Attack Paths
- Cloud Security Explorer
- Secret Scanning
- Multicloud Security
- Defender for Servers
- Defender for Storage
- Defender for SQL
- Defender for AI Services
- External Attack Surface Management (EASM)
- Microsoft Defender Vulnerability Management

### Engineering Focus

**Identify → Prioritize → Remediate → Monitor**

---

## 🔎 Microsoft Sentinel

- Workspace Architecture
- Data Connectors
- Analytics Rules
- KQL
- Custom Log Tables
- Windows Security Events
- Data Collection Rules
- Windows Event Forwarding
- Syslog & CEF
- Automation Rules
- Logic Apps
- Playbooks
- Incident Investigation
- Threat Detection
- SOAR
- Microsoft Purview Audit integration

### Engineering Focus

**Collect → Normalize → Detect → Investigate → Respond → Automate**

---

## 🤖 Microsoft Security Copilot

- Security Copilot Architecture
- Workspaces
- Security Compute Units (SCUs)
- Permissions & Roles
- Plugins
- Microsoft Agents
- Security Store Agents
- AI-Assisted Investigation
- AI-Assisted Response

---

# 🧪 Hands-on Labs

The theoretical concepts in this guide are connected to practical Azure and Microsoft Security labs.

Each lab follows an engineering workflow:

```text
Objective
   ↓
Scenario
   ↓
Architecture
   ↓
Prerequisites
   ↓
Implementation
   ↓
Security Configuration
   ↓
Validation
   ↓
Telemetry / Evidence
   ↓
Detection
   ↓
Investigation
   ↓
Response
   ↓
Automation
   ↓
Lessons Learned
```

## 🔬 Lab Documentation Standard

Each published lab should document, where applicable:

1. **Objective**
2. **Scenario**
3. **Architecture**
4. **Prerequisites**
5. **Implementation**
6. **Security Controls**
7. **Validation**
8. **Evidence / Screenshots**
9. **Telemetry**
10. **Detection Logic**
11. **Investigation**
12. **Response**
13. **Automation**
14. **Lessons Learned**
15. **Interview Questions**
16. **Related SC-500 Topics**

---

# 🔗 AI Security Hands-on Lab Portfolio

The current AI Security lab portfolio contains **7 hands-on projects** covering AI infrastructure security, data protection, content safety, threat detection, security posture, runtime protection, and investigation/response.

| # | Lab / Project | Primary Focus | Repository |
|---|---|---|---|
| 01 | **Azure OpenAI Private Endpoint Zero Trust Lab** | Azure OpenAI, Private Endpoint, Key Vault, Managed Identity, RBAC, Zero Trust networking | [View Lab](https://github.com/AmalUBasnayake/Azure-OpenAI-Private-Endpoint-Zero-Trust-Lab) |
| 02 | **Azure Content Safety — Prompt Guard** | Azure AI Content Safety and prompt/input protection | [View Lab](https://github.com/AmalUBasnayake/azure-content-safety-prompt-guard) |
| 03 | **Microsoft Purview — AI Shield DLP Lab** | Sensitivity Labels, DLP, Microsoft 365 Copilot data protection and Purview DSPM for AI | [View Lab](https://github.com/AmalUBasnayake/purview-ai-shield-dlp-lab) |
| 04 | **AI Threat Detection & Response with Microsoft Sentinel** | AI threat detection, KQL, Sentinel analytics and response | [View Lab](https://github.com/AmalUBasnayake/SC-500-Lab-04-AI-Threat-Detection-Response-Microsoft-Sentinel) |
| 05 | **AI Security Posture & Threat Protection with Microsoft Defender for Cloud** | AI security posture management and threat protection | [View Lab](https://github.com/AmalUBasnayake/SC-500-Lab-05-AI-Security-Posture-Threat-Protection-Microsoft-Defender-for-Cloud) |
| 06 | **AI Runtime Threat Protection with Microsoft Defender for Cloud** | AI runtime protection and cloud workload security | [View Lab](https://github.com/AmalUBasnayake/SC-500-Lab-06-AI-Runtime-Threat-Protection-Microsoft-Defender-for-Cloud) |
| 07 | **AI Security Investigation & Response with Microsoft Defender XDR** | AI security investigation, incident analysis and response | [View Lab](https://github.com/AmalUBasnayake/SC-500-Lab-07-AI-Security-Investigation-Response-Microsoft-Defender-XDR) |

## 🧩 AI Security Learning Progression

These labs can be viewed as an evolving engineering path:

```text
Secure AI Infrastructure
        ↓
Prompt / Content Safety
        ↓
AI Data Protection & DLP
        ↓
Threat Detection
        ↓
Security Posture Management
        ↓
Runtime Threat Protection
        ↓
Investigation & Response
```

The labs are maintained as **standalone GitHub projects** and are linked here so the Master Guide can act as the central learning roadmap.

> More AI security labs will be added as new scenarios are built, validated, and documented.

---

# 📘 Study Notes

The complete study notes are designed to cover the SC-500 skills measured list and connect exam preparation with practical implementation.

They include:

- Exam snapshot
- SC-500 skill domains and weights
- AZ-500 → SC-500 changes
- Identity, access & governance
- Storage, databases & networking
- AI security
- Servers & virtual machines
- Application platform services
- Defender for Cloud
- Microsoft Sentinel
- Microsoft Security Copilot
- Scenario → best-answer mapping
- Least-privilege role picker
- Numbers and defaults to memorize
- Exam traps
- Final-week plan
- Verification checklist
- Labs and resources
- Microsoft Learn learning-path mapping

> The complete study notes PDF will be maintained under `Study-Notes/` as the detailed reference companion to this repository.

---

# 🧠 Engineering Mindset

The goal is not only to memorize Microsoft security services.

Think like a Cloud & AI Security Engineer:

```text
Identity
   ↓
Data
   ↓
Network
   ↓
Workloads
   ↓
Detection
   ↓
Investigation
   ↓
Response
   ↓
Automation
   ↓
AI Security
   ↓
Governance & Architecture
```

When evaluating a security design, consider:

- Least privilege
- Zero Trust
- Attack surface reduction
- Defense in depth
- Secure-by-default configuration
- Identity-first security
- Private connectivity
- Secrets elimination
- Detection and visibility
- Incident response
- Automation
- Operational maintainability
- Governance and compliance

---

# 🔐 Security Decision Principles

### Identity

Prefer identity-based access and least privilege over long-lived credentials.

### Secrets

Prefer managed identity and secure secret-management mechanisms over hard-coded credentials.

### Network

Prefer private connectivity and restrictive network controls where the architecture supports them.

### Privilege

Prefer just-in-time and time-bound privileged access over unnecessary standing privilege.

### Detection

Make security controls observable through appropriate telemetry, logs, analytics, and alerts.

### Response

Reduce manual effort through automation where safe and appropriate.

### AI

Treat AI workloads, agents, identities, data access, prompts, model interactions, and runtime activity as security-relevant components.

---

# 🚨 Investigation & Response Framework

A practical investigation should answer:

```text
1. What happened?
2. Which workload generated the activity?
3. Which identity initiated the request?
4. Was the activity expected?
5. Which resource, model, agent, application, or endpoint was involved?
6. What data or privilege was involved?
7. What telemetry supports the finding?
8. What detection identified the activity?
9. What is the potential impact / blast radius?
10. What containment or remediation is appropriate?
11. Can the response be safely automated?
12. What control should prevent recurrence?
```

---

# ⚙️ Detection & Automation

```text
Security Control
      ↓
Telemetry
      ↓
Detection
      ↓
Alert
      ↓
Incident
      ↓
Investigation
      ↓
Response
      ↓
Automation
      ↓
Continuous Improvement
```

Technologies used throughout the labs may include:

- Microsoft Sentinel
- KQL
- Microsoft Defender XDR
- Microsoft Defender for Cloud
- Microsoft Entra ID
- Azure Monitor / Log Analytics
- Logic Apps
- Microsoft Security Copilot
- Microsoft Purview

---

# 🎯 Exam Preparation

The guide supports SC-500 exam preparation through:

- Domain-focused study
- Scenario-based questions
- Least-privilege decisions
- Service comparisons
- Configuration-focused learning
- Exam traps
- Memory techniques
- Final revision
- Hands-on implementation

## Exam Mindset

> **Enforce least privilege → reduce exposure → protect secrets → secure workloads → monitor posture → detect threats → investigate → respond → automate.**

When multiple controls appear technically possible, evaluate which one best satisfies the scenario's security requirements, least-privilege principles, exposure reduction, and operational needs.

---

# ⚡ Cheat-Sheet Topics

Planned quick-reference material includes:

- PIM vs RBAC
- Conditional Access controls
- Authentication methods
- App Registration vs Enterprise Application
- Delegated vs Application permissions
- System-assigned vs User-assigned Managed Identity
- Key Vault control plane vs data plane
- Azure Policy effects
- Azure RBAC roles
- Private Endpoint vs Service Endpoint
- NSG vs Azure Firewall vs WAF
- Defender for Cloud capabilities
- Sentinel analytics rules vs automation rules
- Automation rules vs playbooks
- AI security controls
- Security Copilot capabilities
- Least-privilege role selection

---

# 📈 Progress Tracker

This is a **living guide** and will continuously evolve as new concepts, labs, investigations, and security scenarios are implemented.

```text
🟢 Completed
🟡 In Progress
⚪ Planned
```

| Area | Status |
|---|---|
| Identity & Access | 🟢 |
| Governance | 🟢 |
| Storage Security | 🟢 |
| Network Security | 🟢 |
| AI Security | 🟢 — 7 hands-on labs |
| Compute Security | 🟢 |
| Defender for Cloud | 🟢 |
| Microsoft Sentinel | 🟢 |
| Security Copilot | 🟡 |
| Investigation & Response | 🟢 |
| Automation / SOAR | 🟢 |
| Advanced AI Security Labs | 🟡 |

> Status values will be updated as the public guide and supporting labs evolve.

---

# 📂 Repository Structure

```text
SC-500-Cloud-AI-Security-Engineer-Master-Guide/
│
├── README.md
├── ROADMAP.md
├── PROGRESS.md
│
├── Study-Notes/
│   └── SC-500-Complete-Study-Notes.pdf
│
├── Domain-01-Identity-Governance/
├── Domain-02-Storage-Networking/
├── Domain-03-AI-Compute/
├── Domain-04-Defender-Sentinel-Copilot/
│
├── Labs/
├── Investigation-Response/
├── Cheat-Sheets/
└── Resources/
```

The structure will grow as new material is published.

---

# 📚 Resources

The repository will collect and organize relevant learning resources, including:

- Microsoft Learn
- Microsoft security documentation
- SC-500 skills measured information
- Azure security documentation
- Microsoft Entra documentation
- Microsoft Defender documentation
- Microsoft Sentinel documentation
- Microsoft Purview documentation
- Microsoft Security Copilot documentation
- Hands-on lab resources
- Supporting technical references

---

# 🚧 Living Project

This repository is intentionally **work in progress**.

New content will be added as I:

- Build new hands-on labs
- Validate security configurations
- Document implementation steps
- Develop detection and investigation workflows
- Explore Microsoft Cloud & AI Security capabilities
- Expand exam preparation material
- Improve practical security engineering guidance

> **The goal is to learn, build, validate, document, and share.**

---

# 👨‍💻 Author

**Amal Udayanga Basnayake**

IT & Systems Specialist | Cybersecurity | Azure Security | SIEM & Threat Detection

### Profiles

- GitHub: https://github.com/AmalUBasnayake
- Portfolio: https://amalcyberlab.vercel.app
- LinkedIn: https://www.linkedin.com/in/amal-udayanga-basnayake
- Medium: https://medium.com/@amalubasnayake

---

# ⭐ Follow the Journey

If you find this guide useful, feel free to ⭐ the repository and follow the project as it evolves.

**Learn. Build. Secure. Detect. Respond. Automate.**

---

## 📌 Disclaimer

This is an independent learning and hands-on engineering resource. Microsoft product names, services, and trademarks belong to Microsoft. Always verify current product capabilities, licensing, exam requirements, and documentation against the latest official Microsoft sources.
