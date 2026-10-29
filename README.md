# 🛡️ Week 2 — Network Security Configuration & Vulnerability Assessment

<p align="center">

**Cyber Security Analyst – Online Virtual Internship | 2026**

</p>

---

## 📌 Overview

This repository contains my **Week 2 Cyber Security Analyst internship task**, focused on **network security configuration, vulnerability assessment, risk analysis, and security improvement planning**.

The assessment uses a **hypothetical defensive network scenario** to demonstrate how a security analyst can identify weaknesses, evaluate risks, and recommend practical security controls.

---

## 🎯 Objectives

- 🔍 Review a secure network architecture
- 🛡️ Identify common network security weaknesses
- 📊 Assess vulnerability likelihood and impact
- 🔐 Recommend firewall, VLAN, VPN and wireless controls
- 📝 Develop a network hardening strategy
- 📈 Create a phased security improvement roadmap
- 🚨 Strengthen monitoring, logging and access control

---

## 🏗️ Network Architecture

The proposed architecture follows a **segmented network security model** using firewall controls, VLANs and restricted administrative access.

```text
                    INTERNET
                       │
                       ▼
              ┌─────────────────┐
              │ FIREWALL / NAT  │
              │   ACL • VPN     │
              └────────┬────────┘
                       │
                       ▼
                ┌─────────────┐
                │ CORE SWITCH │
                └──────┬──────┘
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
      VLAN 10       VLAN 20      VLAN 30
       USERS        SERVERS      GUEST WiFi
          │            │
          └────────────┴──────┐
                              ▼
                         VLAN 99
                       MANAGEMENT
```

---

## ⚠️ Simulated Vulnerability Findings

| ID | Finding | Risk |
|---|---|---|
| 🔴 F-01 | Weak Network Segmentation | Critical |
| 🔴 F-02 | Exposed Administrative Services | Critical |
| 🟠 F-03 | Outdated Network-Device Firmware | High |
| 🟠 F-04 | Weak Remote-Access Controls | High |
| 🟠 F-05 | Insufficient Centralized Logging | High |
| 🟠 F-06 | Insecure Wireless Configuration | High |

---

## 🔎 Assessment Methodology

```text
Asset Review
     ↓
Architecture Analysis
     ↓
Configuration Review
     ↓
Vulnerability Identification
     ↓
Risk Scoring
     ↓
Security Recommendations
     ↓
Validation & Monitoring
```

### Risk Model

**Risk = Likelihood × Impact**

Each finding is prioritized according to its potential business impact and probability of exploitation.

---

## 🔐 Key Security Recommendations

- Implement **VLAN-based network segmentation**
- Restrict administrative services using **ACLs**
- Enable **MFA for VPN and privileged access**
- Keep network devices and firmware **regularly patched**
- Separate **corporate and guest Wi-Fi**
- Centralize security logs using **SIEM/log management**
- Disable unnecessary network services
- Establish secure configuration baselines
- Maintain regular configuration backups
- Apply **least-privilege access control**

---

## 🗺️ Security Improvement Roadmap

### Phase 1 — 0–30 Days
- Inventory network infrastructure
- Review firewall and ACL rules
- Secure administrative interfaces
- Enable MFA
- Disable unnecessary services

### Phase 2 — 31–90 Days
- Implement VLAN segmentation
- Separate guest and corporate networks
- Establish patch-management procedures
- Centralize security logging
- Create secure configuration baselines

### Phase 3 — 3–6 Months
- Improve SIEM monitoring
- Automate configuration compliance
- Perform controlled vulnerability assessments
- Formalize change management
- Test incident-response procedures

---

## 📊 Project Files

```text
week-2-network-security-configuration/
│
├── 📄 README.md
│
├── 📁 report/
│   └── Week_2_Network_Security_Configuration_and_Vulnerability_Assessment_2026.docx
│
├── 📁 charts/
│   ├── network-architecture.png
│   └── vulnerability-risk-chart.png
│
└── 📁 references/
    └── sources.md
```

---

## 📚 References

The assessment is based on publicly available cybersecurity frameworks, security guidance and industry research.

📄 Detailed sources:

`references/sources.md`

---

## 👨‍💻 Author

**Injmam Ansari**

🎓 BCA Student  
🔐 Cybersecurity Intern  
📍 India

---

<p align="center">

⭐ **Week 2 Cybersecurity Internship Project — 2026** ⭐

</p>
