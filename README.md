# Information Governance Policy — Cafe de Fantastica

A professional Information Governance Policy designed for *Cafe de Fantastica Ltd*, a fictional UK-based café chain. This project demonstrates how a real-world organisation should manage, protect, and govern its information assets in line with UK law and international security standards.

---

## What Is This?

This is a complete **Information Governance Policy (IGP)**, a formal document that defines how an organisation handles its data. It covers everything from who is responsible for data, to how long records are kept to what happens when something goes wrong.

Although it was built for a fictional café business. Still, the policy itself is designed to be realistic and fit-for-purpose  as if it were being handed to a real organisation to implement.

---

## Why Was It Built?

*Cafe de Fantastica* is a tech-dependent business. It handles customer orders online, stores employee and payment data, works with third-party delivery partners, and runs cloud-based systems across CRM platforms, integrated POS systems, and inventory management software. All of that creates real data risk both internally and through third parties.

Without a governance policy, the organisation would have:
- No clear ownership of data
- No plan when a breach happens
- No way to prove legal compliance
- No structure for keeping or deleting records safely

This policy solves all of that.

---

## What Does It Cover?

**Who is responsible**
Clear roles are defined across the organisation: Board of Directors, CIO, CRO, IT Manager, HR Manager, Branch Managers, and all staff, each with specific data protection obligations.

**Legal compliance**
Built around UK GDPR, Data Protection Act 2018, Privacy and Electronic Communications Regulations (PECR), PCI-DSS for payment data, Computer Misuse Act 1990, and ICO guidance.

**International standards**
Aligned with ISO/IEC 27001 (information security management), ISO 22301:2019 (business continuity), ISO 31000 (risk management), and NIST SP 800-30 (risk assessment methodology).

**Record management**
Role-based access control (RBAC) is enforced throughout, applying the principle of least privilege. Multi-factor authentication (MFA) is implemented to prevent unauthorised access. All system interactions, access, modification, and deletion are logged and reviewed through audit trails.

**Data retention and disposal**
Retention periods defined by legal and business requirements:
- Customer order records — 2 years
- Employee records — 7 years post-employment
- Financial and tax data — minimum 6 years (HMRC requirement)

Secure disposal methods include cryptographic erasure, degaussing, overwriting, physical shredding, pulping, and supervised incineration.

**Risk management and business continuity**
Structured risk identification and scoring using an impact/likelihood matrix, aligned with ISO 31000 and NIST SP 800-30. Business Continuity Planning (BCP) ensures critical functions remain operational during disruptions, with key services replicated across redundant cloud infrastructure and pre-certified backup vendors in place.

**Disaster recovery**
Disaster Recovery Plan (DRP) built to ISO 22301:2019 standards with clearly defined objectives:
- Online ordering platform RTO — 4 hours
- Online ordering platform RPO — 24 hours

Hourly automated backups are stored in geographically redundant locations, encrypted, and validated weekly. Real-time monitoring with automated alerts and cloud-based failover systems.

**Ethics**
Data minimisation is applied throughout, only collecting what is necessary for a declared purpose. Transparent consent processes aligned with PECR and UK GDPR. Accountability is enforced through designated data custodians. Non-discrimination and fairness are embedded in all data-driven decisions.

**Compliance framework**
A three-level compliance model:
1. **Training and awareness** — mandatory role-specific training, simulated phishing exercises, and annual policy acknowledgement for all staff
2. **Real-time monitoring** — automated tools tracking data access and triggering alerts for suspicious activity
3. **Formal auditing** — quarterly internal audits by the Information Governance Committee and annual external audits by qualified ISO 27001 auditors

**Governance management system (IGPMS)**
A secure digital document repository built on ISO/IEC 27001 ISMS standards, housing all policies, version histories, audit logs, and data flow maps. Compliance dashboards provide real-time KPI visibility, including training completion rates, policy acknowledgement rates, and incident response times.

**Implementation**
A five-stage rollout strategy:
1. Initiation and planning
2. Policy dissemination and infrastructure setup
3. Training and capacity building
4. Monitoring and adjustment
5. Continuous improvement

Progress tracked against KPIs, including audit pass rates, breach reduction levels, and training completion rates reported directly to the Board.

---

## How Was It Made?

The policy was researched and written from the ground up, drawing on:
- UK regulatory guidance from the ICO and HMRC
- International security and governance standards (ISO, NIST)
- Academic and industry literature on information governance and cybersecurity
- Real-world best practices for access control, data classification, incident response, and disaster recovery

The accompanying report critically analyses every decision made in the policy, justifying the legal basis, the chosen frameworks, and the full implementation strategy.

---

## Repository Contents


The full policy and report: [`CafeDeFantastica-Information-Governance-Policy.pdf`](https://github.com/SHOBUsi/information-governance-policy-msc/blob/main/CafeDeFantastica-Information-Governance-Policy.pdf) 

---

## Author

**Soriful Islam Shoaib**   
[GitHub](https://github.com/SHOBUsi) · [LinkedIn](https://www.linkedin.com/in/soriful-islam-shoaib/)

---

*Cafe de Fantastica Ltd is a fictional organisation. All scenarios are hypothetical and created to demonstrate applied knowledge of information governance principles.*
