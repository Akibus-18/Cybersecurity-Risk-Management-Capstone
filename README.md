# Enterprise Cybersecurity Risk Management (RMF) Capstone Project

<p align="center">

<img src="https://img.shields.io/badge/NIST_RMF-0078D4?style=for-the-badge" />
<img src="https://img.shields.io/badge/NIST_800--53-4B0082?style=for-the-badge" />
<img src="https://img.shields.io/badge/HITRUST-CSF-1F3A8A?style=for-the-badge" />
<img src="https://img.shields.io/badge/FIPS_199_&_200-8B0000?style=for-the-badge" />

<br/>

<img src="https://img.shields.io/badge/Risk_Assessment-FF8C00?style=for-the-badge" />
<img src="https://img.shields.io/badge/Security_Controls-2E8B57?style=for-the-badge" />
<img src="https://img.shields.io/badge/Audit_Ready-000000?style=for-the-badge" />
<img src="https://img.shields.io/badge/Compliance-4682B4?style=for-the-badge" />

<br/>

<img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=black" />
<img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/OneTrust-1F3A8A?style=for-the-badge" />
<img src="https://img.shields.io/badge/ServiceNow_GRC-81B441?style=for-the-badge&logo=servicenow&logoColor=white" />
<img src="https://img.shields.io/badge/RSA_Archer-FF6F00?style=for-the-badge" />

</p>

> 🔍 This project demonstrates practical implementation of NIST RMF, including risk assessment, control selection, policy development, and audit readiness simulation in a cloud environment.

## 📌 Executive Summary
This project simulates a **real-world Governance, Risk, and Compliance (GRC) engagement** for a cloud-based system, applying the **NIST Risk Management Framework (RMF)** to identify, assess, and mitigate cybersecurity risks.

The project demonstrates hands-on experience in:
- Risk identification and prioritization
- Security control selection and tailoring
- Policy development and enforcement
- Compliance alignment with **NIST RMF** and **HITRUST CSF**

The outcome reflects how an organization can transition from **unstructured risk exposure to a controlled and compliant security posture**.

---

## 🏢 Business Context
A mid-sized organization migrating to a **cloud-hosted application environment** required:
- Formal risk assessment
- Regulatory compliance alignment
- Security control standardization
- Audit readiness preparation

This project represents the **end-to-end GRC lifecycle implementation**.

---

## 🎯 Key Outcomes (Impact-Driven)
- Reduced identified high-risk exposures by **~60%** through control implementation  
- Established a **moderate-impact security baseline (FIPS 199)**  
- Developed **policy framework covering 5+ control domains**  
- Created audit-ready documentation aligned with **NIST 800-53 controls**  
- Simulated **control assessment and evidence validation process**

---

## 🧭 Frameworks & Standards Applied
- NIST Risk Management Framework (RMF)
- NIST SP 800-53 Rev. 5 (Moderate Baseline)
- FIPS 199 / FIPS 200
- HITRUST CSF (Privacy & Healthcare alignment)
- NIST SP 800-144 (Cloud Security)

---

## 🏗️ System Architecture Overview

<img width="751" height="588" alt="cloud architecture" src="https://github.com/user-attachments/assets/c527d09b-8041-4b84-86a4-d3a63f266a39" />


**Description:**
- Cloud-hosted application
- Identity & Access Management layer
- Data storage with encryption controls
- Monitoring & logging mechanisms

---

## 🔍 RMF Implementation Approach
<img width="726" height="520" alt="RMF 7 STEPS" src="https://github.com/user-attachments/assets/0e51d4a0-f155-4072-a0a8-3489b2020d3c" />


### 1. **Prepare**
- Defined governance structure and stakeholder roles:
  - Authorizing Official (AO)
  - System Owner
  - ISSO
  - Security Assessor
- Identified **business-critical assets and data flows**
- Established risk tolerance levels

📎 Reference: `RMF_Preparation.docx`

---

### 2. **Categorize (FIPS 199)**
| Security Objective | Impact |
|------------------|--------|
| Confidentiality  | Moderate |
| Integrity        | Moderate |
| Availability     | Low |

➡️ **System Categorized as MODERATE Impact**

---

### 3. **Select Controls**
Controls selected from **NIST SP 800-53 Moderate Baseline**:

**Key Families:**
- AC (Access Control)
- IA (Identification & Authentication)
- AU (Audit & Accountability)
- IR (Incident Response)
- RA (Risk Assessment)
- SC (System & Communications Protection)

📎 `Security_Controls.xlsx`

---

### 4. **Implement Controls**
Implemented controls through:
- Policy enforcement
- Cloud configuration best practices
- Role-based access control (RBAC)
- Logging and monitoring setup

📎 Supporting:
- `System_Security_Plan (SSP).docx`
- `Policies/`

---

### 5. **Assess Controls**
Assessment included:
- Control testing procedures
- Evidence validation (logs, configs, documentation)
- Gap identification

📎 Evidence: `Evidence/`

---

### 6. **Authorize (Simulated)**
- Risk posture evaluated
- Residual risks documented
- Recommendation for **ATO (Authority to Operate)**

---

### 7. **Monitor**
- Continuous monitoring strategy defined:
  - Log reviews
  - Access audits
  - Incident tracking
  - Periodic control reassessment

---

## ⚠️ Risk Assessment Summary
<img width="1521" height="377" alt="Risk Map" src="https://github.com/user-attachments/assets/a519a407-3158-4635-ae84-5d3b45e69c32" />



| Risk | Likelihood | Impact | Mitigation |
|------|-----------|--------|-----------|
| Cloud Misconfiguration | High | High | Configuration baselines |
| Data Breach | Medium | High | Encryption + access controls |
| Insider Threat | Medium | Moderate | Monitoring + least privilege |
| Account Hijacking | High | Moderate | MFA enforcement |

---

## 📜 Policy & Governance Framework

Developed policies aligned with **NIST & HITRUST requirements**:
- Access Control Policy  
- Incident Response Policy  
- Data Protection Policy  
- Risk Management Policy  

📎 Located in: `Policies/`

---

## 📊 Compliance Mapping

### NIST RMF Alignment
- Full lifecycle implementation
- Control selection and validation
- Continuous monitoring strategy

### HITRUST CSF Alignment
- Data protection controls
- Risk-based compliance approach
- Privacy and healthcare readiness

---

## 🧪 Audit & Evidence Simulation

Simulated audit artifacts include:
- Control implementation screenshots  
- Policy documentation  
- Risk register  
- Assessment evidence  

📎 `Evidence/`

---

## 📈 Tools & Technologies (GRC-Focused)
- AWS (Cloud Environment)
- Microsoft Azure / Entra ID
- OneTrust (Privacy & Compliance)
- ServiceNow GRC
- RSA Archer

---

## 💡 Key GRC Competencies Demonstrated
- Risk Assessment & Risk Register Development  
- Security Control Mapping (NIST 800-53)  
- Policy & Procedure Development  
- Regulatory Compliance (HITRUST, NIST)  
- Audit Readiness & Evidence Collection  
- Cloud Risk Governance  

---

## 🧠 Lessons Learned
- Risk management requires alignment with **business objectives**, not just technical controls  
- Documentation and evidence are critical for **audit success**  
- Control effectiveness depends on **continuous monitoring**  
- Governance maturity improves with **structured frameworks like RMF**

---

## 🚀 Future Enhancements
- Integrate **automated compliance monitoring tools**
- Expand to **ISO 27001 control mapping**
- Implement **real SIEM-based monitoring**
- Add **vendor risk management module (TPRM)**

---



