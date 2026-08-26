# Enterprise Cybersecurity Risk Assessment

## NIST CSF 2.0 | Enterprise Risk Management | GRC

**Cybersecurity • GRC • Risk Management • NIST CSF 2.0 • Threat Analysis • Control Mapping**

---

## Executive Summary

This project is a simulated enterprise cybersecurity risk assessment for **IslandLink Business Services Ltd.**, a fictional mid-sized Jamaican organization.

The assessment evaluates cybersecurity risk across the organization's cloud services, identity environment, endpoints, network infrastructure, business applications, sensitive information assets and third-party service providers.

The project follows a risk-based GRC methodology that connects:

**Business Context → Assets → Threats & Vulnerabilities → Enterprise Risks → Controls → Risk Treatment**

The assessment uses **NIST Cybersecurity Framework 2.0** as the primary cybersecurity framework, supported by concepts from **NIST SP 800-30** and **ISO/IEC 27001:2022**.

> **Final Assessment: ELEVATED CURRENT CYBER RISK — PRIORITY REMEDIATION REQUIRED**

The assessment identified significant exposure in identity security, privileged access, ransomware resilience, financial fraud, legacy infrastructure, security monitoring, perimeter security and third-party risk.

---

## Project at a Glance

| Metric | Result |
|---|---:|
| Technology & Information Assets | **35** |
| Business Services Assessed | **10** |
| Crown-Jewel Assets | **8** |
| Threat & Vulnerability Scenarios | **36** |
| Enterprise Cybersecurity Risks | **22** |
| Critical Inherent Risks | **19** |
| High Residual Risks | **6** |
| Modeled Risk Exposure Reduction | **59%** |
| NIST CSF 2.0 Categories Assessed | **22** |
| Overall Current-to-Target CSF Alignment | **46%** |
| Risk Treatment Actions | **18** |
| Estimated Remediation Effort | **252 person-days** |

---

## Project Scenario

IslandLink Business Services Ltd. is a fictional Jamaican mid-sized company with approximately 150 employees operating from Kingston and Montego Bay.

The organization uses a hybrid work model and relies heavily on:

- Microsoft 365
- Microsoft Entra ID
- Windows endpoints
- Cloud-based accounting software
- CRM and HR SaaS platforms
- SharePoint and OneDrive
- Remote-access VPN
- Corporate Wi-Fi
- Firewalls and network infrastructure
- Legacy Active Directory and file services
- Cloud and local backups
- Remote monitoring and management tools
- Managed IT providers
- Public website and DNS infrastructure

The company has grown rapidly and adopted technology incrementally. Security controls exist, but governance and implementation are inconsistent across the environment.

---

## My Role

For this simulated engagement, I performed the role of a **Cybersecurity GRC / Risk Analyst**.

My responsibilities included:

- Defining assessment scope and business context
- Identifying critical business services
- Building an enterprise asset inventory
- Identifying crown-jewel systems and information
- Assessing threats and vulnerabilities
- Developing realistic attack paths
- Creating an enterprise cybersecurity risk register
- Performing inherent and residual risk analysis
- Designing executive risk dashboards and heatmaps
- Mapping cybersecurity controls to NIST CSF 2.0
- Developing a risk treatment strategy
- Building a 30/60/90-day remediation roadmap
- Defining evidence requirements and success metrics
- Preparing the final cybersecurity risk assessment report

---

## Assessment Methodology

The assessment followed a structured enterprise risk-management process.

### 1. Business Context

The organization's operating environment, critical business services, technology dependencies and security objectives were documented.

### 2. Asset Identification

Thirty-five technology and information assets were assessed using confidentiality, integrity and availability criteria.

Eight assets were identified as organizational **crown jewels**.

### 3. Threat & Vulnerability Assessment

Thirty-six realistic threat and vulnerability scenarios were developed.

Examples included:

- Business Email Compromise
- Credential theft
- Password spraying
- Cloud account takeover
- Privileged account compromise
- Ransomware
- Backup compromise
- Legacy infrastructure exploitation
- Firewall and VPN exploitation
- Cloud data leakage
- Insider data exfiltration
- Third-party compromise
- RMM supply-chain compromise
- Website compromise
- DNS/domain takeover
- Infrastructure outages

### 4. Risk Analysis

Threat scenarios were consolidated into **22 enterprise cybersecurity risks**.

Each risk includes:

**Likelihood × Impact = Risk Score**

Risk was evaluated at both:

- **Inherent Risk** — before considering the expected effectiveness of treatment
- **Residual Risk** — projected risk after recommended controls operate effectively

### 5. Control Assessment

Cybersecurity controls were mapped against the six functions of **NIST CSF 2.0**:

**Govern • Identify • Protect • Detect • Respond • Recover**

### 6. Risk Treatment

Eighteen remediation actions were prioritized according to business impact, risk exposure, dependencies and implementation effort.

---

## Key Cybersecurity Risks

The highest-priority enterprise risks included:

| Risk | Inherent Risk | Projected Residual Risk |
|---|---|---|
| Cloud Account Compromise from Incomplete MFA | Critical | Moderate |
| Privileged Identity / Administrator Takeover | Critical | High |
| Ransomware / Enterprise File Encryption | Critical | High |
| Backup Compromise / Recovery Failure | Critical | High |
| Legacy Infrastructure Exploitation | Critical | High |
| Firewall / VPN Exploitation | Critical | Moderate |
| Business Email Compromise / Payment Fraud | Critical | High |
| RMM / Managed IT Supply-Chain Compromise | Critical | Moderate |
| Critical SaaS Vendor Breach | Critical | High |
| Accounting System Integrity Compromise | Critical | Moderate |

---

## Major Risk Themes

### Identity & Privileged Access

Key issues included incomplete MFA coverage, legacy accounts, stale privileges, privileged administration from general-purpose workstations and unmanaged legacy credentials.

### Ransomware & Recovery

Legacy infrastructure, endpoint weaknesses, broad file permissions and unproven backup resilience created a significant ransomware pathway.

### Financial Fraud

Finance and executive mailboxes were identified as high-value Business Email Compromise targets.

### Security Monitoring

Security telemetry existed across Microsoft 365, endpoints, firewalls and other systems, but monitoring was fragmented and centralized detection capability was immature.

### Third-Party Risk

Managed IT providers, RMM platforms and critical SaaS vendors created important supply-chain and privileged-access dependencies.

### Cloud Data Protection

External sharing, bulk exports and inconsistent data-handling controls increased the risk of accidental or intentional information disclosure.

---

## NIST CSF 2.0 Current vs. Target Profile

All **22 NIST CSF 2.0 Categories** were assessed.

| CSF Function | Current Alignment to Target |
|---|---:|
| Govern | **56%** |
| Identify | **68%** |
| Protect | **36%** |
| Detect | **25%** |
| Respond | **46%** |
| Recover | **28%** |

### Overall Weighted Alignment

**46%**

The strongest area was **Identify**, reflecting the asset, threat and enterprise risk-management work completed during the assessment.

The largest gaps were found in:

- Protect
- Detect
- Recover
- Supplier governance
- Privileged access
- Data protection
- Incident analysis
- Recovery validation

The percentages represent a simulated **Current vs. Target Profile alignment model** developed for this portfolio project.

They are **not NIST certification scores or official NIST maturity ratings**.

---

## Risk Treatment Strategy

The remediation program contains **18 treatment actions** across multiple security workstreams.

Priority controls include:

- Universal MFA
- Conditional access
- Privileged-access governance
- Hardened administrator access
- Independent payment verification
- Anti-impersonation controls
- Endpoint and server patch management
- Firewall and VPN hardening
- Immutable backups
- Tested restoration procedures
- Legacy-system isolation and migration
- Centralized security logging
- Incident-response playbooks
- Vendor security assurance
- Data Loss Prevention
- External-sharing restrictions
- Security awareness training
- Formal cybersecurity governance

---

## 30 / 60 / 90-Day Remediation Roadmap

### 0–30 Days

Focus on immediate attack paths and governance.

- Universal MFA
- Remove authentication exceptions
- Begin payment-verification controls
- Begin immutable backup implementation
- Begin firewall/VPN hardening
- Establish cyber-risk governance

### 31–60 Days

Strengthen high-impact enterprise controls.

- Privileged-access governance
- Finance fraud controls
- Backup restoration validation
- Perimeter hardening
- Risk appetite approval
- Executive risk oversight

### 61–90 Days

Standardize operating controls.

- Endpoint patch compliance
- Secure configuration baselines
- Laptop encryption
- Device compliance
- Asset reconciliation
- Vulnerability review

### 90+ Days

Build sustainable cybersecurity capability.

- Centralized security monitoring
- Incident-response program
- Vendor risk management
- Cloud data protection
- Security awareness
- Cybersecurity policy framework
- Legacy-system migration
- Infrastructure resilience

---

## Management Assessment

The organization's current cybersecurity posture presents an **elevated enterprise risk profile**.

The assessment identified significant inherent exposure across identity systems, privileged access, financial processes, legacy infrastructure, ransomware recovery, network boundaries and supplier relationships.

The proposed control program is expected to materially reduce cyber risk.

However, projected residual-risk scores should **not** be considered achieved simply because a remediation action is marked complete.

Residual risk should only be formally reduced after control effectiveness is supported by appropriate operating evidence.

Examples include:

- MFA coverage reports
- Privileged-access reviews
- Patch compliance reports
- Firewall configuration evidence
- Backup restoration tests
- Security monitoring coverage
- Incident-response exercises
- Vendor assurance evidence
- DLP and external-sharing reports

---

## Project Deliverables

### Final Assessment Report

[View Cybersecurity Risk Assessment Report](Cybersecurity_Risk_Assessment_Report_Project2.pdf)

### Enterprise Asset Inventory

[View Enterprise Cybersecurity Asset Inventory](Enterprise_Cybersecurity_Asset_Inventory_Project2.xlsx)

### Threat & Vulnerability Matrix

[View Threat and Vulnerability Matrix](Threat_and_Vulnerability_Matrix_Project2.xlsx)

### Cybersecurity Risk Register

[View Cybersecurity Risk Register](Cybersecurity_Risk_Register_Project2.xlsx)

### Executive Risk Dashboard

[View Risk Heatmap and Executive Dashboard](Risk_Heatmap_and_Executive_Dashboard_Project2.xlsx)

### NIST CSF 2.0 Control Mapping

[View NIST CSF 2.0 Control Mapping](NIST_CSF_2.0_Control_Mapping_Project2.xlsx)

### Risk Treatment Plan

[View Risk Treatment Plan](Risk_Treatment_Plan_Project2.xlsx)

---

## Skills Demonstrated

**Cybersecurity Risk Assessment**  
**Governance, Risk & Compliance (GRC)**  
**Enterprise Risk Management**  
**NIST CSF 2.0**  
**Risk Registers**  
**Inherent & Residual Risk Analysis**  
**Threat Modeling**  
**Vulnerability Analysis**  
**Asset Management**  
**Control Mapping**  
**Risk Treatment Planning**  
**Security Governance**  
**Identity & Access Management**  
**Third-Party Risk Management**  
**Cloud Security**  
**Incident Response**  
**Ransomware Resilience**  
**Executive Risk Reporting**

---

## Portfolio Disclaimer

This project is a simulated professional cybersecurity risk assessment created for portfolio and skills-demonstration purposes.

The organization, systems, assets, personnel, vendors, risks, vulnerabilities, control implementations, assessment results and conclusions are fictional.

No confidential information belonging to a real organization was used.

NIST CSF 2.0 and ISO/IEC 27001 mappings are provided for educational and professional demonstration purposes.

This project does not represent NIST certification, ISO certification, legal advice, regulatory approval or evidence that any real organization has implemented the controls described.
