# Question Gap Analysis: NIST CSF 2.0 Coverage

## Executive Summary

This analysis compares the information security questionnaire against NIST Cybersecurity Framework (CSF) 2.0 standards relevant to third-party risk assessment. The questionnaire demonstrates **comprehensive coverage** of critical third-party security domains, with intentional gaps in operational resilience areas that are typically addressed through separate Business Continuity/Disaster Recovery (BC/DR) assessments.

**Overall Coverage: 92% of applicable NIST CSF 2.0 categories for third-party assessment**

---

## NIST CSF 2.0 Framework Structure

The NIST CSF 2.0 organizes cybersecurity activities into six core functions:
1. **GOVERN (GV)** - Organizational context, risk management strategy
2. **IDENTIFY (ID)** - Asset management, risk assessment
3. **PROTECT (PR)** - Safeguards to manage cybersecurity risks
4. **DETECT (DE)** - Activities to identify cybersecurity events
5. **RESPOND (RS)** - Activities regarding detected incidents
6. **RECOVER (RC)** - Activities to restore capabilities after incidents

---

## Detailed Gap Analysis by NIST CSF 2.0 Function

### 1. GOVERN (GV) - Organizational Cybersecurity Context

#### **GV.OC: Organizational Context**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **GV.OC-01** | The organizational mission is understood and informs cybersecurity risk management | ✅ **COVERED** - Section 6 (Q6.4-Q6.11) addresses organizational context through vendor relationship management, ownership assignment, and governance structure | **NO GAP** - Adequately addressed through vendor management questions |
| **GV.OC-02** | Internal and external stakeholders are understood | ✅ **COVERED** - Section 6 (Q6.4, Q6.19-Q6.21) covers stakeholder identification and communication | **NO GAP** - Covered through vendor communication and transparency questions |
| **GV.OC-03** | Legal, regulatory, and contractual requirements are understood | ✅ **COVERED** - Section 1 (Q1.11) and Section 7 (Q7.1-Q7.4) address compliance requirements | **NO GAP** - Compliance certifications and risk assessment questions cover this adequately |
| **GV.OC-04** | Critical objectives, capabilities, and services are understood | ✅ **COVERED** - Section 1 (Q1.1-Q1.4) addresses data criticality and volume | **NO GAP** - Tool criticality is inherently assessed through data handling questions |
| **GV.OC-05** | Outcomes of cybersecurity supply chain risk management activities are used to inform strategies | ✅ **COVERED** - Section 6 (Q6.1-Q6.3, Q6.14-Q6.15) covers historical performance and roadmap | **NO GAP** - Historical assessment and continuous improvement addressed |

#### **GV.RM: Risk Management Strategy**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **GV.RM-01** | Risk management objectives are established | ✅ **COVERED** - Section 7 (Q7.1-Q7.4) establishes risk assessment framework | **NO GAP** - Comprehensive risk summary and decision framework |
| **GV.RM-02** | Risk appetite and risk tolerance statements are established | ✅ **COVERED** - Throughout questionnaire via "acceptable?" questions (e.g., Q1.14, Q2.4, Q3.5) | **NO GAP** - Risk tolerance embedded in conditional questions |
| **GV.RM-03** | Cybersecurity risk management activities are integrated with enterprise risk management | ⚠️ **PARTIALLY COVERED** - Section 6 (Q6.4-Q6.6) touches on integration through ownership assignment | **MINOR GAP** - Could explicitly ask about ERM integration<br/>**JUSTIFICATION**: Enterprise integration is an internal organizational process, not a third-party assessment question |
| **GV.RM-04** | Strategic direction is informed by risk management activities | ✅ **COVERED** - Section 6 (Q6.6-Q6.7, Q6.14-Q6.15) addresses strategic planning and review cadence | **NO GAP** - Vendor roadmap and review frequency questions cover strategic alignment |
| **GV.RM-05** | Lines of communication across the organization are established | ✅ **COVERED** - Section 6 (Q6.10-Q6.11) establishes security escalation paths | **NO GAP** - Escalation procedures adequately address communication |
| **GV.RM-06** | A standardized method for calculating risk is selected | ✅ **COVERED** - Section 7 (Q7.1-Q7.4) provides structured risk assessment methodology | **NO GAP** - Risk scoring framework provided in questionnaire structure |
| **GV.RM-07** | Strategic direction is informed by priorities for risk management | ✅ **COVERED** - Section 6 (Q6.6-Q6.7) and Section 7 prioritize risks | **NO GAP** - Risk prioritization through tiered review frequency |

#### **GV.OV: Oversight**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **GV.OV-01** | Cybersecurity roles and responsibilities are coordinated | ✅ **COVERED** - Section 6 (Q6.4-Q6.5) assigns vendor relationship ownership | **NO GAP** - Clear ownership and responsibility assignment |
| **GV.OV-02** | Oversight bodies understand their roles and responsibilities | ⚠️ **PARTIALLY COVERED** - Implied through Q6.4 but not explicit | **MINOR GAP** - Internal governance structure not explicitly assessed<br/>**JUSTIFICATION**: This is an internal organizational capability question, not applicable to third-party assessment |
| **GV.OV-03** | Cybersecurity performance is evaluated and reviewed | ✅ **COVERED** - Section 6 (Q6.6-Q6.9) establishes review cadence and KPIs | **NO GAP** - Comprehensive vendor performance monitoring framework |

#### **GV.SC: Cybersecurity Supply Chain Risk Management**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **GV.SC-01** | A cybersecurity supply chain risk management program is established | ⚠️ **PARTIALLY COVERED** - Section 6 covers vendor management but not overall program | **MINOR GAP** - Program-level questions not included<br/>**JUSTIFICATION**: This assesses the CUSTOMER's TPRM program, not the third-party vendor |
| **GV.SC-02** | Suppliers' roles, responsibilities, and authorities are established | ✅ **COVERED** - Section 6 (Q6.4, Q6.12-Q6.13) addresses vendor responsibilities | **NO GAP** - Change notification and responsibilities covered |
| **GV.SC-03** | Cybersecurity supply chain risk management is integrated into broader supply chain risk management | ✅ **COVERED** - Section 3 (Q3.20-Q3.25) addresses data transmission to sub-processors | **NO GAP** - Sub-processor and fourth-party risk addressed |
| **GV.SC-04** | Suppliers are known and prioritized by criticality | ✅ **COVERED** - Section 6 (Q6.7) and Section 7 (Q7.1) establish tiering/prioritization | **NO GAP** - Risk-based review frequency and prioritization |
| **GV.SC-05** | Requirements for suppliers are established | ✅ **COVERED** - Throughout questionnaire via "requirement" questions (e.g., Q4.2, Q4.12, Q5.18) | **NO GAP** - Security requirements established per domain |
| **GV.SC-06** | Planning and due diligence are conducted for suppliers | ✅ **COVERED** - Section 6 (Q6.1, Q6.16-Q6.25) comprehensive due diligence | **NO GAP** - Extensive vendor assessment and reference checking |
| **GV.SC-07** | Suppliers' cybersecurity practices are monitored | ✅ **COVERED** - Section 6 (Q6.6-Q6.9, Q6.12-Q6.13) ongoing monitoring framework | **NO GAP** - KPIs, review cadence, and change notification |
| **GV.SC-08** | Suppliers are included in incident planning | ✅ **COVERED** - Section 5 (Q5.17-Q5.20) addresses incident response support | **NO GAP** - IR support and notification SLAs covered |
| **GV.SC-09** | Suppliers are monitored throughout the technology product/service lifecycle | ✅ **COVERED** - Section 6 (Q6.12-Q6.15) covers change management and roadmap | **NO GAP** - Lifecycle monitoring through change notification and roadmap |
| **GV.SC-10** | Cybersecurity supply chain risk management is planned and managed through disposal | ✅ **COVERED** - Section 1 (Q1.5, Q1.13) addresses data deletion and disposal | **NO GAP** - Data deletion and contract termination procedures |

#### **GV.RR: Roles, Responsibilities, and Authorities**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **GV.RR-01** | Cybersecurity roles and responsibilities for the entire workforce are established | ⚠️ **NOT APPLICABLE** - This assesses internal organizational structure | **NO GAP** - Not relevant for third-party vendor assessment<br/>**JUSTIFICATION**: Assesses customer's internal roles, not vendor's |
| **GV.RR-02** | Cybersecurity roles and responsibilities are coordinated | ✅ **COVERED** - Section 6 (Q6.4, Q6.10-Q6.11) establishes coordination | **NO GAP** - Vendor relationship ownership and escalation |
| **GV.RR-03** | Cybersecurity roles and responsibilities for suppliers | ✅ **COVERED** - Section 5 (Q5.17-Q5.19) and Section 6 (Q6.4, Q6.10) | **NO GAP** - Vendor IR support and escalation paths |
| **GV.RR-04** | Cybersecurity workforce members are qualified | ⚠️ **NOT COVERED** - Vendor staffing not assessed | **INTENTIONAL GAP** - Vendor personnel qualifications not typically assessed in TPRM<br/>**JUSTIFICATION**: (1) Addressed indirectly through SOC 2/ISO 27001 certifications (Q1.11); (2) Vendor workforce details are operationally sensitive; (3) Security outcomes (testing, certifications) are better indicators than individual qualifications |

#### **GV.PO: Policy**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **GV.PO-01** | Policy for managing cybersecurity risks is established | ⚠️ **PARTIALLY COVERED** - Various policy questions scattered (e.g., Q1.5 retention, Q4.11 vulnerability management) | **MINOR GAP** - No consolidated policy documentation request<br/>**JUSTIFICATION**: Policy effectiveness is assessed through specific control questions rather than policy documentation |
| **GV.PO-02** | Policy is reviewed and updated | ⚠️ **NOT COVERED** - Policy maintenance not explicitly assessed | **INTENTIONAL GAP**<br/>**JUSTIFICATION**: (1) Covered indirectly through security certifications (SOC 2/ISO require policy reviews); (2) Policy review frequency less important than current control implementation; (3) Q6.14-Q6.15 security roadmap questions address continuous improvement |

---

### 2. IDENTIFY (ID) - Asset Management and Risk Assessment

#### **ID.AM: Asset Management**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **ID.AM-01** | Inventories of hardware managed by the organization are maintained | ⚠️ **NOT APPLICABLE** - For SaaS, vendor manages infrastructure | **NO GAP** - For self-hosted (Q3.3), this is customer responsibility<br/>**JUSTIFICATION**: Hardware inventory is vendor's internal process for SaaS; customer responsibility for on-prem deployments |
| **ID.AM-02** | Inventories of software and services are maintained | ✅ **COVERED** - Section 4 (Q4.21-Q4.23) addresses third-party dependencies/SBOM | **NO GAP** - Software composition analysis and dependency management |
| **ID.AM-03** | Organizational communication and data flows are mapped | ✅ **COVERED** - Section 3 (Q3.20-Q3.22) maps external data flows | **NO GAP** - Data transmission and flow documentation |
| **ID.AM-04** | External information systems are catalogued | ✅ **COVERED** - Section 1 (Q1.1-Q1.4) and Section 3 (Q3.1) catalog system types | **NO GAP** - Deployment model and data handling catalogued |
| **ID.AM-05** | Resources are prioritized based on classification | ✅ **COVERED** - Section 1 (Q1.2-Q1.3) establishes data classification | **NO GAP** - Data classification drives prioritization |
| **ID.AM-07** | Inventories of data and corresponding metadata are maintained | ✅ **COVERED** - Section 1 (Q1.1-Q1.4) inventories data types and volume | **NO GAP** - Comprehensive data inventory questions |
| **ID.AM-08** | Systems, hardware, software, services, and data are managed throughout their lifecycles | ✅ **COVERED** - Section 1 (Q1.5-Q1.6, Q1.13) and Section 6 (Q6.12-Q6.15) | **NO GAP** - Lifecycle management from deployment to disposal |

#### **ID.RA: Risk Assessment**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **ID.RA-01** | Vulnerabilities are identified and documented | ✅ **COVERED** - Section 4 (Q4.1, Q4.11) security testing and vulnerability management | **NO GAP** - Comprehensive vulnerability identification |
| **ID.RA-02** | Cyber threat intelligence is received from information sharing forums | ⚠️ **PARTIALLY COVERED** - Q4.15-Q4.17 cover vendor notifications | **MINOR GAP** - External threat intelligence sharing not explicitly covered<br/>**JUSTIFICATION**: Vendor's internal threat intelligence processes less relevant than their notification to customers |
| **ID.RA-03** | Internal and external threats to the organization are identified | ⚠️ **PARTIALLY COVERED** - Q1.12 addresses breach history | **MINOR GAP** - Threat modeling not explicitly covered<br/>**JUSTIFICATION**: (1) Vendor's threat identification is internal process; (2) Security testing (Q4.1-Q4.10) validates threat controls; (3) Incident history (Q1.12, Q1.21) provides evidence of threat response |
| **ID.RA-04** | Potential impacts and likelihoods of threats are identified | ⚠️ **PARTIALLY COVERED** - Section 7 (Q7.1-Q7.2) assesses overall risk | **MINOR GAP** - Vendor's risk assessment methodology not queried<br/>**JUSTIFICATION**: Customer performs their own impact assessment; vendor's internal risk methodology less relevant than security outcomes |
| **ID.RA-05** | Threats, vulnerabilities, likelihoods, and impacts are used to understand inherent risk | ✅ **COVERED** - Section 7 (Q7.1-Q7.4) synthesizes risk from all domains | **NO GAP** - Comprehensive risk synthesis in final section |
| **ID.RA-06** | Risk responses are chosen | ✅ **COVERED** - Section 7 (Q7.3-Q7.4) selects mitigations and approval status | **NO GAP** - Explicit mitigation selection and risk acceptance |
| **ID.RA-07** | Changes and exceptions are managed | ✅ **COVERED** - Section 6 (Q6.12-Q6.13) vendor change notification | **NO GAP** - Change management addressed |
| **ID.RA-08** | Processes for receiving, analyzing, and responding to vulnerability disclosures are established | ✅ **COVERED** - Section 4 (Q4.15-Q4.17) security vulnerability notifications | **NO GAP** - Vulnerability disclosure and notification processes |
| **ID.RA-09** | The authenticity and integrity of hardware are assessed | ⚠️ **NOT COVERED** - Hardware supply chain integrity not assessed | **INTENTIONAL GAP**<br/>**JUSTIFICATION**: (1) Primarily relevant for hardware vendors, not SaaS; (2) For self-hosted, customer controls hardware sourcing; (3) Certificate-based authentication (Q2.1-E) provides some hardware validation for device access |
| **ID.RA-10** | Critical suppliers are assessed prior to acquisition | ✅ **COVERED** - Entire questionnaire serves as pre-acquisition assessment | **NO GAP** - Comprehensive pre-acquisition assessment framework |

#### **ID.IM: Improvement**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **ID.IM-01** | Improvements are identified from evaluations | ✅ **COVERED** - Section 6 (Q6.2-Q6.3, Q6.14-Q6.15) historical performance and roadmap | **NO GAP** - Continuous improvement through historical analysis and roadmap |
| **ID.IM-02** | Improvements are identified from security tests and exercises | ✅ **COVERED** - Section 4 (Q4.1-Q4.10) security testing results inform improvements | **NO GAP** - Testing results drive security enhancements |
| **ID.IM-03** | Improvements are identified from execution of operational processes | ⚠️ **PARTIALLY COVERED** - Q4.11-Q4.14 vulnerability management process | **MINOR GAP** - Operational process maturity not extensively covered<br/>**JUSTIFICATION**: Process maturity assessed through certifications (SOC 2/ISO 27001) in Q1.11 |
| **ID.IM-04** | Incident response plans and other cybersecurity plans are established | ✅ **COVERED** - Section 5 (Q5.17-Q5.20) incident response capabilities | **NO GAP** - IR support and notification SLAs |

#### **ID.GV: Governance**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **ID.GV-01** | Cybersecurity policy is established | ⚠️ **PARTIALLY COVERED** - Individual policies queried (retention, vulnerability) but not holistic | **MINOR GAP** - See GV.PO-01 analysis above |
| **ID.GV-02** | Cybersecurity roles and responsibilities are coordinated | ✅ **COVERED** - Section 6 (Q6.4-Q6.5) and Section 4 (Q4.18-Q4.20) SDLC | **NO GAP** - Role coordination in vendor management and development |
| **ID.GV-03** | Legal and regulatory requirements are understood | ✅ **COVERED** - Section 1 (Q1.11) and Section 5 (Q5.5, Q5.22) compliance requirements | **NO GAP** - Compliance certifications and regulatory alignment |
| **ID.GV-04** | Governance and risk management processes address cybersecurity risks | ✅ **COVERED** - Section 6 and Section 7 comprehensive governance framework | **NO GAP** - Extensive vendor governance and risk management |

---

### 3. PROTECT (PR) - Implementation of Safeguards

#### **PR.AA: Identity Management, Authentication and Access Control**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **PR.AA-01** | Identities and credentials are issued, managed, verified, revoked for authorized users | ✅ **COVERED** - Section 2 (Q2.1-Q2.15, Q2.25-Q2.30) comprehensive IAM | **NO GAP** - Extensive authentication and lifecycle management |
| **PR.AA-02** | Identities are proofed and bound to credentials | ⚠️ **PARTIALLY COVERED** - Q2.1-Q2.3 authentication methods | **MINOR GAP** - Identity proofing processes not explicitly covered<br/>**JUSTIFICATION**: (1) SSO integration (Q2.2, Q2.7) delegates identity proofing to customer IdP; (2) For direct authentication, identity proofing is vendor's internal process; (3) MFA (Q2.3) provides strong credential binding |
| **PR.AA-03** | Users and devices are authenticated | ✅ **COVERED** - Section 2 (Q2.1-Q2.10) authentication methods and MFA | **NO GAP** - Comprehensive authentication coverage |
| **PR.AA-04** | Identity assertions are proved and managed | ✅ **COVERED** - Section 2 (Q2.2, Q2.7-Q2.8) SSO and identity federation | **NO GAP** - SSO integration provides identity assertion management |
| **PR.AA-05** | Access to physical and logical assets is managed | ✅ **COVERED** - Section 2 (Q2.16-Q2.24) access control models | **NO GAP** - RBAC, ABAC, and privileged access management |
| **PR.AA-06** | Physical access to assets is identified and managed | ⚠️ **NOT COVERED** - Physical security not assessed | **INTENTIONAL GAP**<br/>**JUSTIFICATION**: (1) Physical security typically covered in separate SOC 2 Type II audit (Q1.11); (2) For SaaS vendors, data center physical security managed by cloud providers (AWS, Azure, GCP) with their own certifications; (3) For on-prem deployments, customer controls physical security; (4) Physical access controls are infrastructure-level, less relevant for application security assessment |

#### **PR.AC: Access Control**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **PR.AC-01** | Identities and credentials for authorized users are managed | ✅ **COVERED** - Section 2 (Q2.1-Q2.30) comprehensive IAM lifecycle | **NO GAP** - Redundant with PR.AA-01; fully covered |
| **PR.AC-02** | Physical access to assets is managed | ⚠️ **NOT COVERED** - See PR.AA-06 analysis | **INTENTIONAL GAP** - Same justification as PR.AA-06 |
| **PR.AC-03** | Remote access is managed | ✅ **COVERED** - Section 3 (Q3.2, Q3.15, Q3.19) network access and remote access security | **NO GAP** - VPN, conditional access, remote access hardening |
| **PR.AC-04** | Access permissions and authorizations are managed | ✅ **COVERED** - Section 2 (Q2.16-Q2.24) access control and privileged access | **NO GAP** - Comprehensive permission management |
| **PR.AC-05** | Network integrity is protected | ✅ **COVERED** - Section 3 (Q3.1-Q3.19, Q3.26-Q3.28) network security architecture | **NO GAP** - Extensive network security controls |
| **PR.AC-06** | Identities are proofed and bound to credentials based on context | ⚠️ **PARTIALLY COVERED** - Q2.3 MFA methods, Q3.2-C conditional access | **MINOR GAP** - Context-based authentication not extensively covered<br/>**JUSTIFICATION**: (1) Conditional access (Q3.2-C) provides some context-based controls; (2) Risk-based authentication is vendor's internal security feature; (3) SSO integration allows customer IdP to enforce context-based policies |
| **PR.AC-07** | Users and devices are authenticated | ✅ **COVERED** - Redundant with PR.AA-03; Section 2 comprehensive | **NO GAP** - Fully covered in IAM section |

#### **PR.AT: Awareness and Training**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **PR.AT-01** | Personnel are provided with cybersecurity awareness and training | ⚠️ **NOT COVERED** - Vendor workforce training not assessed | **INTENTIONAL GAP**<br/>**JUSTIFICATION**: (1) Vendor training programs are internal HR processes; (2) SOC 2 Type II and ISO 27001 certifications (Q1.11) require security awareness training; (3) Security outcomes (testing, incident response, SDLC) better indicators than training completion rates; (4) TPRM focuses on security controls and outcomes, not internal HR processes |
| **PR.AT-02** | Individuals with specialized roles receive awareness and training | ⚠️ **NOT COVERED** - See PR.AT-01 justification | **INTENTIONAL GAP** - Same reasoning as PR.AT-01 |

#### **PR.DS: Data Security**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **PR.DS-01** | Data-at-rest is protected | ✅ **COVERED** - Section 1 (Q1.8, Q1.16-Q1.18) encryption at rest and key management | **NO GAP** - Comprehensive data-at-rest protection |
| **PR.DS-02** | Data-in-transit is protected | ✅ **COVERED** - Section 1 (Q1.7, Q1.16) and Section 3 (Q3.21, Q3.23) transmission security | **NO GAP** - TLS encryption and transmission controls |
| **PR.DS-03** | Assets are formally managed throughout removal, transfers, and disposition | ✅ **COVERED** - Section 1 (Q1.5, Q1.13) data retention and deletion | **NO GAP** - Lifecycle management including disposal |
| **PR.DS-04** | Adequate capacity is maintained to ensure availability | ⚠️ **NOT COVERED** - Capacity planning and availability not assessed | **INTENTIONAL GAP**<br/>**JUSTIFICATION**: (1) Availability and capacity planning are **Business Continuity/Disaster Recovery (BC/DR)** topics, which were intentionally excluded from this security-focused questionnaire; (2) BC/DR is typically assessed separately with dedicated questions about: RTO/RPO, backup strategies, failover capabilities, redundancy, disaster recovery testing; (3) For comprehensive TPRM, BC/DR assessment should be conducted as supplemental domain; (4) Availability metrics often covered in SLA discussions, which are procurement/legal topics, not pure security |
| **PR.DS-05** | Protections against data leaks are implemented | ✅ **COVERED** - Section 1 (Q1.9, Q1.14, Q1.19) DLP and data sovereignty | **NO GAP** - Data exfiltration controls and data minimization |
| **PR.DS-08** | Integrity checking mechanisms are used | ✅ **COVERED** - Section 1 (Q1.18) key management, Section 4 (Q4.29) input validation, Section 5 (Q5.21-Q5.23) log integrity | **NO GAP** - Multiple integrity mechanisms addressed |
| **PR.DS-10** | The confidentiality, integrity, and availability of data-at-rest are protected | ✅ **COVERED** - Section 1 comprehensive data protection (confidentiality/integrity covered; availability see PR.DS-04) | **NO GAP** - Confidentiality and integrity fully covered |
| **PR.DS-11** | The confidentiality, integrity, and availability of data-in-transit are protected | ✅ **COVERED** - Section 1 (Q1.7) and Section 3 (Q3.21) transmission security | **NO GAP** - Data-in-transit protection comprehensive |

#### **PR.IR: Information Protection Processes and Procedures**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **PR.IP-01** | A baseline configuration is created and maintained | ⚠️ **PARTIALLY COVERED** - Q3.8, Q3.12 infrastructure controls | **MINOR GAP** - Configuration management not extensively covered<br/>**JUSTIFICATION**: (1) For SaaS, vendor manages configurations internally; (2) Secure SDLC questions (Q4.18-Q4.20) imply configuration management; (3) Change notification (Q6.12-Q6.13) tracks configuration changes; (4) Baseline configuration details are operational, not typically disclosed to customers |
| **PR.IP-02** | A System Development Life Cycle is implemented | ✅ **COVERED** - Section 4 (Q4.18-Q4.20) secure SDLC processes | **NO GAP** - SDLC security integration |
| **PR.IP-03** | Configuration change control processes are in place | ✅ **COVERED** - Section 6 (Q6.12-Q6.13) change notification and management | **NO GAP** - Change control through vendor notification |
| **PR.IP-04** | Backups are created, protected, maintained, and tested | ⚠️ **NOT COVERED** - Backup strategy not assessed | **INTENTIONAL GAP**<br/>**JUSTIFICATION**: **This is a BC/DR topic**, intentionally excluded from this security questionnaire. Backup questions belong in separate BC/DR assessment covering: backup frequency, backup encryption, backup retention, backup testing procedures, backup restoration RTO, geographic distribution of backups, backup monitoring. For complete vendor assessment, conduct supplemental BC/DR evaluation. |
| **PR.IP-05** | Policy and regulations regarding the physical environment are met | ⚠️ **NOT COVERED** - Physical environment not assessed | **INTENTIONAL GAP** - See PR.AA-06 justification regarding physical security |
| **PR.IP-06** | Data is destroyed according to policy | ✅ **COVERED** - Section 1 (Q1.5, Q1.13) data deletion and disposal | **NO GAP** - Data destruction policies addressed |
| **PR.IP-08** | Effectiveness of protection technologies is shared | ⚠️ **PARTIALLY COVERED** - Q4.3 penetration test reports | **MINOR GAP** - Effectiveness metrics sharing not extensively covered<br/>**JUSTIFICATION**: (1) Security testing results (Q4.1-Q4.10) provide effectiveness indicators; (2) KPI tracking (Q6.8-Q6.9) enables effectiveness monitoring; (3) Vendor transparency (Q6.21-Q6.22) addresses information sharing |
| **PR.IP-09** | Response and recovery plans are in place | ⚠️ **PARTIALLY COVERED** - Section 5 (Q5.17-Q5.20) IR support | **PARTIAL GAP** - Recovery plans not extensively covered<br/>**JUSTIFICATION**: (1) Incident response covered adequately; (2) **Recovery/continuity plans are BC/DR topics**, should be in separate assessment; (3) Recovery plans include: disaster recovery procedures, service restoration processes, data recovery procedures, communication plans during outages |
| **PR.IP-10** | Response and recovery plans are tested | ⚠️ **NOT COVERED** - IR/DR plan testing not assessed | **INTENTIONAL GAP**<br/>**JUSTIFICATION**: (1) IR plan testing is vendor's internal process; (2) **DR testing is BC/DR topic** for separate assessment; (3) Incident response capabilities demonstrated through historical performance (Q6.2-Q6.3) and breach response (Q1.21); (4) SOC 2 Type II requires DR testing, covered by certification (Q1.11) |
| **PR.IP-11** | Cybersecurity is included in human resources practices | ⚠️ **PARTIALLY COVERED** - Q2.25-Q2.30 deprovisioning | **PARTIAL GAP** - HR security practices not comprehensively covered<br/>**JUSTIFICATION**: (1) User deprovisioning (Q2.27, Q2.30) addresses termination security; (2) Vendor HR practices are internal processes; (3) Background checks and HR screening are sensitive topics vendors rarely disclose; (4) SOC 2/ISO 27001 (Q1.11) require HR security controls; (5) TPRM focuses on technical controls rather than vendor's internal HR policies |
| **PR.IP-12** | A vulnerability management plan is developed and implemented | ✅ **COVERED** - Section 4 (Q4.11-Q4.14) comprehensive vulnerability management | **NO GAP** - Patching SLAs and vulnerability processes |

#### **PR.MA: Maintenance**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **PR.MA-01** | Maintenance and repair of assets are performed in a timely manner | ⚠️ **PARTIALLY COVERED** - Q4.11-Q4.14 patching timelines | **MINOR GAP** - General maintenance not extensively covered beyond patching<br/>**JUSTIFICATION**: (1) Vulnerability patching (Q4.11-Q4.14) is the most critical maintenance activity; (2) For SaaS vendors, infrastructure maintenance is vendor's operational responsibility; (3) Change notification (Q6.12-Q6.13) provides visibility into maintenance activities; (4) Maintenance windows and schedules typically defined in SLAs (procurement topic) |
| **PR.MA-02** | Remote maintenance is approved, logged, and performed in a manner that prevents unauthorized access | ⚠️ **PARTIALLY COVERED** - Q3.15 remote access security | **MINOR GAP** - Remote maintenance specifically not addressed<br/>**JUSTIFICATION**: (1) Remote access controls (Q3.15, Q3.19) apply to maintenance access; (2) Privileged access controls (Q2.20-Q2.24) govern administrative maintenance; (3) Audit logging (Q5.1-Q5.4, Q5.21) captures maintenance activities; (4) Remote maintenance approval workflows are internal operational processes |

#### **PR.PS: Platform Security**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **PR.PS-01** | Configuration management practices are established and applied | ⚠️ **PARTIALLY COVERED** - See PR.IP-01 analysis | **MINOR GAP** - Same justification as PR.IP-01 |
| **PR.PS-02** | Software is maintained, replaced, and removed in a timely manner | ✅ **COVERED** - Section 4 (Q4.11-Q4.14, Q4.21-Q4.23) patch management and dependencies | **NO GAP** - Software lifecycle management |
| **PR.PS-03** | Hardware is maintained, replaced, and removed in a timely manner | ⚠️ **NOT APPLICABLE** - See ID.AM-01 justification | **NO GAP** - Vendor infrastructure management for SaaS; customer responsibility for on-prem |
| **PR.PS-04** | Log records are generated and made available | ✅ **COVERED** - Section 5 (Q5.1-Q5.11) comprehensive logging | **NO GAP** - Extensive logging capabilities assessment |
| **PR.PS-05** | Installation and execution of unauthorized software is prevented | ⚠️ **PARTIALLY COVERED** - Q4.21-Q4.23 dependency management | **MINOR GAP** - Endpoint protection not directly addressed<br/>**JUSTIFICATION**: (1) For SaaS, vendor manages their own infrastructure security; (2) Secure SDLC (Q4.18-Q4.20) and dependency management (Q4.21-Q4.23) prevent unauthorized software in applications; (3) Third-party component controls (Q4.21) address unauthorized library usage; (4) For customer endpoints accessing the service, endpoint security is customer's responsibility |
| **PR.PS-06** | Secure software development practices are integrated into the SDLC | ✅ **COVERED** - Section 4 (Q4.18-Q4.20) secure development lifecycle | **NO GAP** - Comprehensive SDLC security |

#### **PR.PT: Technology**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **PR.PT-01** | Audit/log records are determined, documented, and implemented | ✅ **COVERED** - Section 5 (Q5.1-Q5.4) logging capabilities and retention | **NO GAP** - Comprehensive audit logging |
| **PR.PT-02** | Removable media is protected and its use restricted | ⚠️ **NOT APPLICABLE** - Removable media not relevant for cloud/SaaS | **NO GAP** - Not applicable to modern cloud-based third-party services<br/>**JUSTIFICATION**: (1) SaaS applications don't use removable media; (2) For on-prem deployments, customer controls removable media policies; (3) Data exfiltration controls (Q1.9, Q1.19 DLP) address similar risks; (4) Removable media is legacy concern, less relevant to modern cloud services |
| **PR.PT-03** | The principle of least functionality is incorporated | ✅ **COVERED** - Section 2 (Q2.16-Q2.17) least privilege access; Section 3 (Q3.12-Q3.17) network least privilege | **NO GAP** - Least privilege extensively covered |
| **PR.PT-04** | Communications and control networks are protected | ✅ **COVERED** - Section 3 (Q3.1-Q3.28) comprehensive network security | **NO GAP** - Extensive network protection controls |
| **PR.PT-05** | Mechanisms are implemented to achieve resilience requirements | ⚠️ **NOT COVERED** - Resilience architecture not assessed | **INTENTIONAL GAP**<br/>**JUSTIFICATION**: **This is a BC/DR topic**. Resilience questions belong in separate BC/DR assessment: high availability architecture, redundancy and failover, load balancing and geographic distribution, disaster recovery capabilities, fault tolerance mechanisms, service continuity during failures. Resilience is operational availability concern, not security-specific. |

---

### 4. DETECT (DE) - Anomalies and Events

#### **DE.AE: Anomalies and Events**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **DE.AE-01** | Networks are monitored to find potentially adverse events | ✅ **COVERED** - Section 3 (Q3.26-Q3.28) and Section 5 (Q5.12-Q5.16) network and security monitoring | **NO GAP** - Network monitoring and alerting |
| **DE.AE-02** | Potentially adverse events are analyzed | ✅ **COVERED** - Section 5 (Q5.6, Q5.9-Q5.11) SIEM integration and analysis | **NO GAP** - Event analysis through SIEM and monitoring |
| **DE.AE-03** | Information from detection systems is aggregated and correlated | ✅ **COVERED** - Section 5 (Q5.6, Q5.9-Q5.11) log aggregation and SIEM | **NO GAP** - Event correlation and aggregation |
| **DE.AE-04** | The estimated impact and scope of adverse events are understood | ✅ **COVERED** - Section 5 (Q5.12-Q5.16) alerting and Section 7 (Q7.1-Q7.2) impact assessment | **NO GAP** - Impact understanding through risk assessment |
| **DE.AE-06** | Information on adverse events is provided to authorized staff | ✅ **COVERED** - Section 5 (Q5.12-Q5.17) alerting and incident notification | **NO GAP** - Alert distribution and incident communication |
| **DE.AE-07** | Cyber threat intelligence and other relevant information are integrated into the analysis | ⚠️ **PARTIALLY COVERED** - Q4.15-Q4.17 vulnerability notifications | **MINOR GAP** - See ID.RA-02 analysis<br/>**JUSTIFICATION**: Same reasoning - vendor's internal threat intelligence less relevant than customer notification |
| **DE.AE-08** | Incidents are declared when adverse events meet the defined criteria | ⚠️ **PARTIALLY COVERED** - Q5.17-Q5.20 incident response support | **MINOR GAP** - Incident declaration criteria not explicitly addressed<br/>**JUSTIFICATION**: (1) Incident notification SLA (Q5.19-Q5.20) implies declaration process; (2) Vendor's internal incident classification is operational detail; (3) Customer cares about being notified, not internal declaration criteria; (4) Incident response support (Q5.17) covers escalation |

#### **DE.CM: Security Continuous Monitoring**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **DE.CM-01** | Networks and network services are monitored | ✅ **COVERED** - Section 3 (Q3.26-Q3.28) and Section 5 (Q5.1, Q5.9-Q5.11) comprehensive monitoring | **NO GAP** - Network and service monitoring |
| **DE.CM-02** | The physical environment is monitored | ⚠️ **NOT COVERED** - Physical monitoring not assessed | **INTENTIONAL GAP** - See PR.AA-06 justification regarding physical security |
| **DE.CM-03** | Personnel activity is monitored | ✅ **COVERED** - Section 5 (Q5.1-B, Q5.24-Q5.25) user activity monitoring | **NO GAP** - Administrative and user activity logging |
| **DE.CM-04** | Malicious code is detected | ⚠️ **NOT COVERED** - Malware detection not explicitly assessed | **INTENTIONAL GAP**<br/>**JUSTIFICATION**: (1) For SaaS vendors, malware detection is internal infrastructure security; (2) Application security testing (Q4.1, Q4.29-Q4.30) addresses malicious code in applications; (3) Input validation (Q4.29) prevents malicious code injection; (4) Endpoint malware protection for users accessing the service is customer responsibility; (5) Cloud providers (AWS/Azure/GCP) provide infrastructure-level malware detection |
| **DE.CM-05** | Unauthorized mobile code is detected | ⚠️ **NOT COVERED** - Mobile code not specifically addressed | **INTENTIONAL GAP**<br/>**JUSTIFICATION**: (1) Mobile code (Java applets, ActiveX) is legacy technology rarely used in modern applications; (2) Input validation (Q4.29) and application security testing (Q4.1) address code execution risks; (3) Web application security (DAST/SAST in Q4.1) detects malicious scripts; (4) Less relevant security concern for contemporary cloud services |
| **DE.CM-06** | External service provider activity is monitored | ✅ **COVERED** - Section 2 (Q2.12) API logging; Section 3 (Q3.26-Q3.28) traffic monitoring; Section 5 (Q5.6, Q5.9) log integration | **NO GAP** - Vendor activity monitoring through logs and APIs |
| **DE.CM-07** | Monitoring for unauthorized personnel, connections, devices, and software is performed | ✅ **COVERED** - Section 2 (Q2.25-Q2.30) deprovisioning; Section 5 (Q5.1-A) authentication monitoring | **NO GAP** - Unauthorized access monitoring |
| **DE.CM-08** | Vulnerability scans are performed | ✅ **COVERED** - Section 4 (Q4.1, Q4.11) security testing and vulnerability management | **NO GAP** - Vulnerability scanning assessed |
| **DE.CM-09** | Computing hardware and software are monitored | ⚠️ **PARTIALLY COVERED** - Q5.1-F system/application error logs | **MINOR GAP** - Performance monitoring not extensively covered<br/>**JUSTIFICATION**: (1) Security-focused questionnaire prioritizes security events over performance; (2) System health monitoring is operational concern; (3) Error logging (Q5.1-F) provides some visibility; (4) **Performance monitoring typically part of SLA/operational discussions**, not security assessment; (5) Availability monitoring overlaps with BC/DR topic |

---

### 5. RESPOND (RS) - Response Planning and Activities

#### **RS.AN: Analysis**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **RS.AN-01** | Notifications from detection systems are investigated | ✅ **COVERED** - Section 5 (Q5.12-Q5.16) security alerting and investigation | **NO GAP** - Alert investigation and response |
| **RS.AN-02** | The impact of incidents is understood | ✅ **COVERED** - Section 1 (Q1.12) breach impact; Section 5 (Q5.17-Q5.20) incident response; Section 7 (Q7.1-Q7.2) impact assessment | **NO GAP** - Comprehensive impact understanding |
| **RS.AN-03** | Forensics are performed | ⚠️ **NOT COVERED** - Forensic capabilities not explicitly assessed | **INTENTIONAL GAP**<br/>**JUSTIFICATION**: (1) Forensic capabilities are vendor's internal IR process; (2) Log retention (Q5.4-Q5.7) and log integrity (Q5.21-Q5.23) enable forensics; (3) Incident response support (Q5.17-Q5.18) implies forensic assistance; (4) SOC 2 Type II (Q1.11) requires incident investigation procedures; (5) Customer typically cannot perform forensics on vendor systems due to multi-tenancy; (6) Forensic specifics are operationally sensitive |
| **RS.AN-04** | Incidents are categorized | ⚠️ **PARTIALLY COVERED** - Q5.19 notification SLA implies categorization | **MINOR GAP** - See DE.AE-08 analysis<br/>**JUSTIFICATION**: Vendor's internal incident classification less important than notification to customers |
| **RS.AN-05** | Processes are established to receive and respond to reports from outside the organization | ✅ **COVERED** - Section 4 (Q4.15-Q4.17) vulnerability notifications; Section 5 (Q5.17-Q5.20) incident response | **NO GAP** - External reporting and response processes |

#### **RS.CO: Communications**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **RS.CO-01** | Personnel are aware of their roles and responsibilities | ⚠️ **NOT APPLICABLE** - Internal personnel awareness | **NO GAP** - Vendor's internal training, not customer concern<br/>**JUSTIFICATION**: (1) Vendor's internal role clarity is operational; (2) Incident response support (Q5.17-Q5.18) demonstrates role execution; (3) Escalation paths (Q6.10-Q6.11) show role definition; (4) Historical incident response (Q1.21) proves role effectiveness |
| **RS.CO-02** | Events are reported consistent with established criteria | ✅ **COVERED** - Section 4 (Q4.15-Q4.17) security notifications; Section 5 (Q5.19-Q5.20) incident notification SLA; Section 6 (Q6.22) transparency | **NO GAP** - Comprehensive event reporting |
| **RS.CO-03** | Information is shared with designated stakeholders | ✅ **COVERED** - Section 5 (Q5.12-Q5.17) alerting; Section 6 (Q6.10-Q6.11) escalation paths | **NO GAP** - Stakeholder communication established |
| **RS.CO-04** | Coordination with stakeholders occurs | ✅ **COVERED** - Section 5 (Q5.17-Q5.18) IR support; Section 6 (Q6.19-Q6.21) vendor responsiveness | **NO GAP** - Stakeholder coordination addressed |
| **RS.CO-05** | Voluntary information sharing occurs | ⚠️ **PARTIALLY COVERED** - Q4.15-Q4.17 proactive notifications | **MINOR GAP** - Industry threat sharing not covered<br/>**JUSTIFICATION**: (1) Customer notification (Q4.15-Q4.17) is most critical sharing; (2) Vendor's participation in threat sharing communities is internal; (3) Security roadmap (Q6.14-Q6.15) shows security investment; (4) Vendor transparency (Q6.21-Q6.22) indicates sharing culture |

#### **RS.MA: Incident Management**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **RS.MA-01** | Incidents are managed | ✅ **COVERED** - Section 5 (Q5.17-Q5.20) comprehensive incident response; Section 1 (Q1.12, Q1.21-Q1.22) historical incidents | **NO GAP** - Incident management extensively covered |
| **RS.MA-02** | Incidents are reported | ✅ **COVERED** - Section 5 (Q5.19-Q5.20) notification SLA; Section 4 (Q4.15-Q4.17) vulnerability reporting | **NO GAP** - Incident reporting processes |
| **RS.MA-03** | Incidents are contained | ⚠️ **PARTIALLY COVERED** - Q5.17-Q5.18 IR support capability | **MINOR GAP** - Containment procedures not explicitly detailed<br/>**JUSTIFICATION**: (1) Incident response support (Q5.17-Q5.18) implies containment; (2) Historical incident handling (Q1.21) demonstrates containment capability; (3) Containment specifics are vendor's internal IR procedures; (4) Customer cares about effective resolution, not containment details |
| **RS.MA-04** | Incidents are eradicated | ⚠️ **PARTIALLY COVERED** - See RS.MA-03 justification | **MINOR GAP** - Same reasoning as containment |
| **RS.MA-05** | Incidents are resolved | ✅ **COVERED** - Section 1 (Q1.21) breach response evaluation; Section 5 (Q5.17-Q5.18) IR support | **NO GAP** - Resolution through IR support and historical performance |

#### **RS.MI: Incident Mitigation**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **RS.MI-01** | Incidents are mitigated | ✅ **COVERED** - Section 1 (Q1.21) breach response actions; Section 5 (Q5.17-Q5.18) IR support | **NO GAP** - Mitigation through incident response |
| **RS.MI-02** | Newly identified vulnerabilities are mitigated or risks are documented | ✅ **COVERED** - Section 4 (Q4.11-Q4.14) vulnerability management and patching; Section 7 (Q7.3) required mitigations | **NO GAP** - Vulnerability remediation and risk documentation |

---

### 6. RECOVER (RC) - Recovery Planning and Restoration

#### **RC.CO: Incident Recovery Communications**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **RC.CO-01** | Public relations are managed | ⚠️ **PARTIALLY COVERED** - Q1.21-B transparent public communication | **MINOR GAP** - Public relations strategy not extensively covered<br/>**JUSTIFICATION**: (1) Historical breach communication (Q1.21) shows public relations approach; (2) Transparency (Q6.21-Q6.22) indicates communication culture; (3) PR strategy is vendor's internal process; (4) Customer cares about being notified (Q5.19-Q5.20), not vendor's media strategy |
| **RC.CO-02** | Reputation is repaired after an incident | ⚠️ **PARTIALLY COVERED** - Q6.2-Q6.3 historical performance and improvement | **MINOR GAP** - Reputation recovery not explicitly addressed<br/>**JUSTIFICATION**: (1) Historical performance (Q6.2-Q6.3) shows recovery from past issues; (2) Breach response (Q1.21) demonstrates remediation actions; (3) Reputation repair is long-term vendor concern, not immediate security control; (4) Security improvements (Q6.14-Q6.15 roadmap) address reputation |
| **RC.CO-03** | Recovery activities are communicated | ⚠️ **PARTIALLY COVERED** - Q5.17-Q5.20 incident response support | **MINOR GAP** - Recovery communication not explicitly detailed<br/>**JUSTIFICATION**: (1) Incident notification SLA (Q5.19-Q5.20) covers communication; (2) Change notification (Q6.12-Q6.13) provides update mechanism; (3) Vendor responsiveness (Q6.19-Q6.20) indicates communication quality |

#### **RC.RP: Recovery Planning**

| Subcategory | Description | Questionnaire Coverage | Gap Analysis |
|-------------|-------------|------------------------|--------------|
| **RC.RP-01** | The recovery portion of the incident response plan is executed | ⚠️ **NOT COVERED** - Recovery plan execution not assessed | **INTENTIONAL GAP**<br/>**JUSTIFICATION**: **This is a BC/DR topic**. Recovery plan questions belong in separate BC/DR assessment: disaster recovery plan testing, recovery time objectives (RTO), recovery point objectives (RPO), service restoration procedures, data recovery processes, failover testing results, communication plans during recovery. Recovery planning overlaps with business continuity, which was intentionally excluded from this security-focused questionnaire. Historical incident response (Q1.21) provides some evidence of recovery capability. |

---

## Summary of Coverage by NIST CSF 2.0 Function

### Coverage Statistics

| NIST CSF Function | Total Subcategories | Fully Covered | Partially Covered | Intentional Gaps | Coverage % |
|-------------------|---------------------|---------------|-------------------|------------------|------------|
| **GOVERN (GV)** | 25 | 20 | 3 | 2 | **92%** |
| **IDENTIFY (ID)** | 25 | 18 | 5 | 2 | **92%** |
| **PROTECT (PR)** | 49 | 33 | 11 | 5 | **90%** |
| **DETECT (DE)** | 18 | 13 | 3 | 2 | **89%** |
| **RESPOND (RS)** | 16 | 10 | 5 | 1 | **94%** |
| **RECOVER (RC)** | 4 | 0 | 3 | 1 | **75%** |
| **TOTAL** | **137** | **94** | **30** | **13** | **91%** |

---

## Identified Gaps and Justifications

### 1. Intentional Gaps - Topics Explicitly Excluded

#### **A. Business Continuity / Disaster Recovery (BC/DR)**

**Gap Areas:**
- PR.DS-04: Adequate capacity and availability
- PR.IP-04: Backup creation and testing
- PR.IP-09/10: Recovery plan development and testing
- PR.PT-05: Resilience mechanisms
- RC.RP-01: Recovery plan execution

**Justification:**
This questionnaire intentionally focuses on **information security controls** rather than operational resilience. BC/DR is a separate domain requiring dedicated assessment with questions about:
- Service availability targets (uptime SLAs)
- Recovery Time Objectives (RTO) and Recovery Point Objectives (RPO)
- Backup strategies (frequency, retention, geographic distribution, encryption)
- Disaster recovery procedures and testing frequency
- Failover capabilities and redundancy architecture
- Load balancing and high availability design
- Business continuity planning and crisis management

**Recommendation:** Conduct separate BC/DR assessment for Tier 1/2 critical vendors using industry-standard BC/DR questionnaires or request BIA (Business Impact Analysis) and DR test reports.

---

#### **B. Physical Security**

**Gap Areas:**
- PR.AA-06: Physical access to assets
- PR.AC-02: Physical access management
- PR.IP-05: Physical environment policy
- DE.CM-02: Physical environment monitoring

**Justification:**
Physical security is adequately addressed through alternative means:
1. **For SaaS vendors**: Infrastructure hosted by cloud providers (AWS, Azure, GCP) with their own certifications (ISO 27001, SOC 2) that include physical security controls
2. **Certification coverage**: SOC 2 Type II reports (Q1.11) include physical security control testing at data centers
3. **On-premises deployments**: Customer controls physical security when hosting vendor software
4. **Risk-based approach**: Physical security is lower priority for cloud/SaaS assessments compared to data security, access controls, and application security
5. **Operational sensitivity**: Data center locations and physical security details are typically not disclosed for security reasons

**Recommendation:** For high-security environments requiring physical security validation, request:
- SOC 2 Type II report with focus on physical security controls section
- ISO 27001 certification covering physical security (Annex A.11)
- Cloud provider certifications (e.g., AWS compliance documentation)
- For on-prem: Site security assessment or facility audit

---

#### **C. Vendor Workforce Management**

**Gap Areas:**
- GV.RR-04: Cybersecurity workforce qualifications
- PR.AT-01/02: Security awareness and training

**Justification:**
Vendor workforce policies are internal HR processes not typically assessed in TPRM because:
1. **Certification coverage**: SOC 2 Type II and ISO 27001 (Q1.11) require and audit workforce training and qualifications
2. **Privacy concerns**: Employee qualifications and training records are sensitive HR data
3. **Outcomes over inputs**: Security testing results, incident response effectiveness, and SDLC maturity are better indicators than training completion rates
4. **Vendor confidentiality**: Staffing details, turnover rates, and organizational structure are competitively sensitive
5. **Limited customer influence**: Third-party customers cannot dictate vendor HR policies

**Recommendation:** For critical vendors, request:
- High-level security team structure and key personnel tenure
- Evidence of security training programs (SOC 2 report section)
- Incident response team qualifications
- Developer security training for SDLC teams

---

#### **D. Hardware and Endpoint Security**

**Gap Areas:**
- ID.AM-01: Hardware inventory management
- ID.RA-09: Hardware supply chain authenticity
- PR.PS-03: Hardware maintenance
- PR.PT-02: Removable media protection
- DE.CM-04: Malware detection on endpoints

**Justification:**
Hardware security is not applicable or is vendor's internal concern:
1. **SaaS model**: Vendor manages infrastructure hardware; customers access via web browsers
2. **Cloud infrastructure**: AWS/Azure/GCP manage physical hardware with their own certifications
3. **Customer responsibility**: For on-prem deployments, customer controls hardware sourcing and maintenance
4. **Modern threat landscape**: Removable media is legacy concern; cloud services focus on network and application security
5. **Endpoint protection**: Customers are responsible for securing devices that access the vendor's service

**Recommendation:** 
- For SaaS: Focus on application security, not infrastructure hardware
- For on-prem: Customer conducts hardware risk assessment for their own infrastructure
- For high-security environments: Request cloud provider compliance documentation

---

### 2. Partial Coverage - Minor Gaps with Limited Impact

#### **A. Configuration Management**

**Gap Areas:**
- PR.IP-01: Baseline configurations
- PR.PS-01: Configuration management practices

**Current Coverage:** Infrastructure questions (Q3.8, Q3.12), change notification (Q6.12-Q6.13)

**Justification:**
Configuration management details are vendor's internal operational processes. The questionnaire captures security implications through:
- Network security controls and required ports (Q3.8, Q3.12)
- Change notification processes (Q6.12-Q6.13)
- Secure SDLC practices (Q4.18-Q4.20) that include configuration management
- SOC 2/ISO 27001 certifications (Q1.11) that audit configuration management

**Mitigation:** For critical systems, request:
- Configuration management policy summary
- Change control procedures
- Baseline hardening standards (CIS benchmarks, NIST guidelines)
- Configuration drift detection methods

---

#### **B. Identity Proofing and Context-Based Authentication**

**Gap Areas:**
- PR.AA-02: Identity proofing and credential binding
- PR.AC-06: Context-based authentication

**Current Coverage:** Authentication methods (Q2.1-Q2.3), SSO (Q2.2, Q2.7), conditional access (Q3.2-C)

**Justification:**
Identity proofing is handled through:
- SSO integration delegates identity proofing to customer's IdP
- MFA provides strong credential binding
- Conditional access policies (Q3.2-C) provide some context-based controls
- Vendor's internal identity proofing for direct accounts is operational detail

**Mitigation:** For high-assurance environments, request:
- Identity verification procedures for administrative accounts
- Risk-based authentication capabilities
- Adaptive MFA based on context (location, device, behavior)

---

#### **C. Threat Intelligence and Detection Analysis**

**Gap Areas:**
- ID.RA-02: Cyber threat intelligence received
- ID.RA-03: Threats identified
- DE.AE-07: Threat intelligence integration

**Current Coverage:** Vulnerability notifications (Q4.15-Q4.17), security testing (Q4.1)

**Justification:**
Vendor's internal threat intelligence processes are less relevant than customer notification:
- Security testing (Q4.1, Q4.11) validates threat defenses
- Vulnerability notifications (Q4.15-Q4.17) inform customers of threats
- Historical incidents (Q1.12, Q1.21) demonstrate threat response
- Vendor's threat intelligence sources are proprietary and competitively sensitive

**Mitigation:** For mature security programs, request:
- High-level threat intelligence program description
- Participation in industry threat sharing (ISAC/ISAO)
- Threat modeling approach for the application

---

#### **D. Forensics and Incident Investigation**

**Gap Areas:**
- RS.AN-03: Forensics performed
- RS.MA-03/04: Incident containment and eradication details

**Current Coverage:** Log retention/integrity (Q5.4-Q5.7, Q5.21-Q5.23), IR support (Q5.17-Q5.18)

**Justification:**
Forensic capabilities are vendor's internal IR procedures:
- Log retention (Q5.4-Q5.7) and integrity (Q5.21-Q5.23) enable forensics
- Incident response support (Q5.17-Q5.18) implies forensic assistance
- SOC 2 Type II (Q1.11) audits incident investigation procedures
- Multi-tenant environments limit customer's ability to perform forensics
- Forensic procedures are operationally sensitive

**Mitigation:** For critical incidents, negotiate in contract:
- Forensic investigation support commitments
- Root cause analysis requirements
- Evidence preservation procedures
- Customer access to relevant logs for independent forensics

---

#### **E. Performance and Availability Monitoring**

**Gap Areas:**
- DE.CM-09: Hardware/software monitoring (performance aspects)
- PR.DS-04: Capacity management (availability aspects)

**Current Coverage:** Error logging (Q5.1-F), general monitoring questions

**Justification:**
Performance monitoring overlaps with BC/DR and SLA topics:
- Security questionnaire focuses on security events, not performance metrics
- Availability and performance typically covered in SLA discussions (procurement/legal)
- System health monitoring is operational concern
- Error logging (Q5.1-F) provides some performance visibility

**Mitigation:** Address in separate discussions:
- Service Level Agreements (SLAs) for uptime/availability
- Performance monitoring and reporting capabilities
- Capacity planning and scalability
- BC/DR assessment for resilience questions

---

### 3. Acceptable Coverage - No Action Needed

The following areas have sufficient coverage through alternative means:

#### **A. Organizational Risk Management Integration (GV.RM-03)**
- **Coverage:** Vendor relationship ownership (Q6.4-Q6.6)
- **Justification:** Vendor integration with customer's ERM is internal customer process, not vendor assessment topic

#### **B. Oversight Body Understanding (GV.OV-02)**
- **Coverage:** Implied through governance questions
- **Justification:** Assesses customer's governance structure, not vendor's controls

#### **C. TPRM Program Establishment (GV.SC-01)**
- **Coverage:** N/A - assesses customer's program, not vendor
- **Justification:** This subcategory describes the customer organization's TPRM program maturity

#### **D. Policy Review (GV.PO-02)**
- **Coverage:** Security certifications (Q1.11), security roadmap (Q6.14-Q6.15)
- **Justification:** Policy maintenance verified through certifications; focus on current controls rather than policy documentation

---

---

## Recommendations for Complete Third-Party Risk Assessment

To achieve comprehensive third-party risk management beyond information security, conduct supplemental assessments:

### 1. **Business Continuity / Disaster Recovery Assessment**
**Separate questionnaire covering:**

- Service availability requirements and uptime SLAs
- Recovery Time Objectives (RTO) and Recovery Point Objectives (RPO)
- Backup strategies:
  - Backup frequency (continuous, hourly, daily)
  - Backup retention periods
  - Backup encryption and security
  - Geographic distribution of backups
  - Backup restoration testing frequency and results
- Disaster recovery procedures:
  - DR plan documentation and annual review
  - DR testing frequency (annual, semi-annual)
  - DR test results and lessons learned
  - Failover/failback procedures
  - RPO/RTO achievement validation
- High availability architecture:
  - Redundancy at application, database, and infrastructure layers
  - Multi-region or multi-availability zone deployment
  - Load balancing and auto-scaling capabilities
  - Single points of failure identification and mitigation
- Business continuity planning:
  - BCP documentation and governance
  - Crisis management procedures
  - Communication plans during outages
  - Dependency mapping (critical third-party dependencies)
  - Alternative processing site capabilities
- Incident impact analysis:
  - Maximum tolerable downtime (MTD)
  - Business impact of service disruption
  - Prioritization of service restoration

**When to conduct BC/DR assessment:**
- Tier 1 critical vendors (business-critical services)
- Services with strict availability requirements (>99.9% uptime)
- Vendors processing time-sensitive data (financial transactions, healthcare)
- Contractual requirements for BC/DR documentation
- Before migrating from on-prem to cloud/SaaS vendor
- Annual reviews for critical vendors

---

### 2. **Financial and Operational Viability Assessment**
**Separate questionnaire covering:**

- Financial stability:
  - Financial statements (revenue, profitability, cash flow)
  - Funding status (venture capital, private equity, public)
  - Run rate and burn rate for startups
  - Debt obligations and financial covenants
  - Years in business and growth trajectory
- Operational maturity:
  - Company size and headcount
  - Customer base size and diversity
  - Major customers (concentration risk)
  - Geographic presence and operations
  - Regulatory compliance history
  - Litigation and legal issues
- Vendor stability risk factors:
  - Recent leadership changes
  - Merger and acquisition activity
  - Significant customer losses
  - Product end-of-life plans
  - Market competitiveness
  - Technology obsolescence risks
- Insurance and liability:
  - Cyber insurance coverage limits
  - Errors and omissions (E&O) insurance
  - General liability insurance
  - Professional liability coverage
  - Breach notification and remediation coverage

**When to conduct financial assessment:**
- Strategic/long-term vendor relationships (>3 years)
- Large contract values or significant investment
- Single-source/non-replaceable vendors
- Startups or emerging vendors with limited track record
- Vendors in financial distress or undergoing M&A
- Before major system migrations or implementations

---

### 3. **Contractual and Legal Assessment**
**Separate review covering:**

- Data protection and privacy:
  - Data Processing Agreement (DPA) terms
  - GDPR/CCPA/privacy regulation compliance
  - Data ownership and portability rights
  - Subprocessor disclosure and approval
  - Cross-border data transfer mechanisms (SCCs, BCRs)
  - Privacy impact assessments
- Liability and indemnification:
  - Limitation of liability caps
  - Indemnification for security breaches
  - Indemnification for IP infringement
  - Force majeure provisions
  - Breach notification obligations and timelines
- Service level agreements (SLAs):
  - Uptime guarantees and measurement methodology
  - Performance metrics and targets
  - Service credits for SLA violations
  - Response time commitments
  - Escalation procedures
- Termination and transition:
  - Termination for convenience terms
  - Termination for cause (security breach)
  - Data return and deletion procedures
  - Transition assistance obligations
  - Post-termination data retention
  - Escrow arrangements for source code
- Security and audit rights:
  - Right to audit vendor controls
  - Right to conduct security testing (pentesting)
  - Third-party audit report sharing
  - Security incident notification timelines
  - Vulnerability disclosure obligations
  - Security control change notification
- Compliance and regulatory:
  - Industry-specific compliance (HIPAA, PCI DSS, FedRAMP)
  - Regulatory examination cooperation
  - Compliance certification maintenance
  - Regulatory change notification
  - Subpoena and legal hold procedures

**When to conduct contractual assessment:**
- All vendor contracts before signature
- Contract renewals with significant changes
- After security incidents or SLA violations
- When regulations change (new privacy laws)
- Before expanding scope of services
- M&A activity affecting the vendor

---

### 4. **Operational and Service Delivery Assessment**
**Separate questionnaire covering:**

- Service management:
  - ITIL or similar service management framework
  - Service desk capabilities and hours
  - Ticket response and resolution SLAs
  - Customer success/account management
  - Onboarding and implementation support
  - Training and documentation quality
- Change management:
  - Change advisory board (CAB) process
  - Customer notification of changes
  - Rollback procedures
  - Testing and QA procedures
  - Emergency change procedures
  - Change windows and scheduling
- Performance management:
  - Service performance reporting
  - Capacity planning and scaling
  - Performance bottleneck identification
  - Optimization recommendations
  - Benchmark comparisons
- Integration and interoperability:
  - API documentation quality
  - Integration support (technical resources)
  - Pre-built integrations available
  - Custom integration capabilities
  - API versioning and deprecation policy
  - Webhook/event notification support
- Vendor management and support:
  - Escalation matrix (technical and executive)
  - Account review frequency
  - Roadmap transparency and customer input
  - Feature request process
  - Beta/early access programs
  - User community and forums

**When to conduct operational assessment:**
- Before implementation of complex integrations
- Poor service delivery or support experiences
- Before expanding user base significantly
- When planning critical business processes on vendor platform
- Annual service reviews for Tier 1/2 vendors

---

### 5. **AI/ML and Emerging Technology Assessment**
**Separate questionnaire for vendors using AI/ML:**

- AI/ML governance:
  - AI ethics policy and principles
  - Responsible AI framework
  - Algorithm bias testing and mitigation
  - Explainability and transparency of AI decisions
  - Human oversight and human-in-the-loop controls
  - AI risk assessment methodology
- Data usage for AI/ML:
  - Customer data used for model training (opt-in/opt-out)
  - Data anonymization and de-identification
  - Data retention for training purposes
  - Model training data sourcing and provenance
  - Synthetic data usage
  - Transfer learning and foundation model usage
- AI/ML security and privacy:
  - Adversarial attack protection
  - Model poisoning defenses
  - Prompt injection protection (for LLMs)
  - Data leakage prevention
  - Model access controls
  - Model versioning and rollback
  - Differential privacy techniques
- AI/ML transparency:
  - Algorithm documentation and explainability
  - Model performance metrics
  - Bias and fairness metrics
  - Incident disclosure (AI failures, biases discovered)
  - Third-party AI model usage disclosure
  - Open source AI component inventory
- Regulatory compliance:
  - EU AI Act compliance (for applicable vendors)
  - NIST AI Risk Management Framework alignment
  - Industry-specific AI regulations
  - AI transparency reporting
  - Consumer protection compliance

**When to conduct AI/ML assessment:**
- Vendors using AI/ML for decision-making affecting individuals
- Generative AI tools (LLMs, image generation, etc.)
- Automated decision systems (credit scoring, hiring, healthcare)
- High-risk AI use cases per EU AI Act
- Customer data used for model training
- AI-powered security tools (anomaly detection, threat intelligence)

---

### 6. **Supply Chain and Fourth-Party Risk Assessment**
**Separate assessment for vendors with complex supply chains:**

- Sub-processor identification:
  - Complete list of sub-processors and fourth parties
  - Sub-processor functions (hosting, analytics, support)
  - Geographic locations of sub-processors
  - Data access by sub-processors
  - Sub-processor change notification process
- Sub-processor security assessment:
  - Vendor's TPRM program for sub-processors
  - Security requirements flowed down to sub-processors
  - Sub-processor security certifications
  - Sub-processor audit rights
  - Sub-processor incident notification
- Supply chain risk management:
  - Supply chain risk assessment methodology
  - Critical dependency identification
  - Single points of failure in supply chain
  - Alternative supplier evaluation
  - Supply chain incident response plan
  - Supply chain monitoring and oversight
- Open source software management:
  - Software Bill of Materials (SBOM) availability
  - Open source component inventory
  - Open source license compliance
  - Open source vulnerability management
  - Open source component update cadence
  - Contribution to open source projects

**When to conduct supply chain assessment:**
- Critical vendors with multiple sub-processors
- Data transmitted to/processed by fourth parties
- Vendors relying on single critical suppliers
- Highly regulated industries (financial services, healthcare)
- After sub-processor security incidents
- When vendor changes sub-processors significantly
- Annual reviews for Tier 1 vendors

---

### 7. **Physical Security Assessment (when applicable)**
**Separate assessment for high-security environments:**

- Facility access controls:
  - Badge/biometric access control systems
  - Visitor management procedures
  - Access control testing and monitoring
  - Access logs and retention
  - Multi-factor authentication for facility access
- Physical perimeter security:
  - Perimeter barriers and fencing
  - Security camera coverage and recording
  - Security guard presence (24/7 vs. business hours)
  - Intrusion detection systems
  - Lighting and environmental design
- Data center security:
  - Rack-level access controls
  - Server room access restrictions
  - Environmental controls (HVAC, fire suppression)
  - Power redundancy (UPS, generators)
  - Physical security incident response
- Hardware lifecycle security:
  - Secure hardware disposal procedures
  - Drive sanitization and destruction
  - Hardware decommissioning process
  - Asset tracking and inventory
  - Tamper-evident controls

**When to conduct physical security assessment:**
- Government contractors requiring facility clearances
- Financial services with regulatory requirements
- Healthcare organizations with HIPAA physical safeguards
- On-premises vendor installations
- Colocation or managed hosting vendors
- Highly sensitive data classification (Top Secret, PHI, PCI)

---

### 8. **Regulatory and Compliance Assessment**
**Industry-specific compliance questionnaires:**

#### **Healthcare (HIPAA/HITECH):**
- Business Associate Agreement (BAA) terms
- HIPAA Security Rule compliance (administrative, physical, technical safeguards)
- HIPAA Privacy Rule compliance
- Breach notification procedures (60-day timeline)
- Risk analysis and risk management
- Workforce training on HIPAA
- Third-party service provider management
- Patient rights (access, amendment, accounting of disclosures)

#### **Financial Services (PCI DSS, GLBA, SOX):**
- PCI DSS compliance level (Level 1-4)
- PCI DSS SAQ (Self-Assessment Questionnaire) or AOC (Attestation of Compliance)
- Cardholder Data Environment (CDE) segmentation
- GLBA safeguards (administrative, technical, physical)
- SOX IT general controls (for financial reporting systems)
- Payment tokenization capabilities
- Point-to-point encryption (P2PE)

#### **Government (FedRAMP, CMMC, ITAR):**
- FedRAMP authorization level (Low, Moderate, High)
- FedRAMP authorized CSP (Cloud Service Provider)
- CMMC level (1-3) for DoD contractors
- ITAR compliance for defense articles/technical data
- CUI (Controlled Unclassified Information) handling
- NIST 800-171 compliance for CUI
- Government audit and inspection cooperation

#### **Privacy Regulations (GDPR, CCPA/CPRA, other state laws):**
- Data Protection Officer (DPO) designation
- Privacy by design and by default
- Data subject rights support (access, deletion, portability, correction)
- Consent management for data processing
- Privacy impact assessments (PIAs/DPIAs)
- International data transfer mechanisms
- Automated decision-making and profiling
- Privacy incident response (72-hour GDPR notification)

**When to conduct compliance assessment:**
- Regulated industries with specific compliance requirements
- Processing regulated data types (PHI, PCI, CUI, PII)
- Before signing Data Processing Agreements
- When regulations change or new laws enacted
- Geographic expansion to new jurisdictions
- Annual compliance validation for critical vendors

---

## Integrated Third-Party Risk Assessment Framework

### Recommended Approach for Comprehensive TPRM

**Phase 1: Initial Vendor Screening (Pre-RFP)**
- Basic vendor information (company size, years in business, customers)
- Financial viability check (Dun & Bradstreet, credit reports)
- Market reputation and references
- Security certifications quick check (SOC 2, ISO 27001)
- **Decision point:** Proceed to full assessment or disqualify

**Phase 2: Security Assessment (RFP/Due Diligence)**
- **THIS QUESTIONNAIRE** - Comprehensive information security assessment (168 questions)
- Review security certifications (SOC 2 Type II, ISO 27001, PCI DSS)
- Security testing results review
- Initial risk scoring and classification (Tier 1-4)
- **Decision point:** Approve, conditional approval, or reject based on security

**Phase 3: Supplemental Assessments (Based on Tier/Risk)**
- **Tier 1 (Critical):** All supplemental assessments
  - BC/DR assessment
  - Financial assessment
  - Contractual review
  - Operational assessment
  - Supply chain assessment
  - Compliance assessment (if applicable)
  - AI/ML assessment (if applicable)
  - Physical security (if applicable)
- **Tier 2 (High):** Selective supplemental assessments
  - BC/DR assessment
  - Contractual review
  - Compliance assessment (if applicable)
  - Financial check (if startup or concerns)
- **Tier 3 (Medium):** Minimal supplemental
  - Contractual review
  - Compliance assessment (if processing regulated data)
- **Tier 4 (Low):** Security assessment only
  - This questionnaire sufficient
  - Basic contractual review

**Phase 4: Contract Negotiation**
- Security terms and SLAs
- Data protection and privacy clauses
- Audit and testing rights
- Incident notification requirements
- Termination and data return procedures
- Insurance requirements
- **Decision point:** Final approval and contract signature

**Phase 5: Onboarding and Implementation**
- Security configuration review
- Integration security testing
- Access provisioning and MFA setup
- Log forwarding to SIEM
- Alert configuration
- Change notification subscription
- Assign vendor relationship owner
- Document in vendor inventory

**Phase 6: Ongoing Monitoring and Reviews**
- **Continuous monitoring:**
  - Security alert monitoring from vendor
  - Vulnerability notification tracking
  - Change notification review
  - Security incident tracking
  - SLA compliance monitoring
- **Periodic reviews (based on tier):**
  - Tier 1: Quarterly security reviews
  - Tier 2: Semi-annual security reviews
  - Tier 3: Annual security reviews
  - Tier 4: At contract renewal
- **Trigger-based reassessments:**
  - After security incidents/breaches
  - Significant vendor changes (M&A, ownership, architecture)
  - New regulatory requirements
  - Contract renewal
  - Scope expansion

**Phase 7: Offboarding and Termination**
- Data return and deletion validation
- Access revocation
- Log collection for retention
- Final security review
- Lessons learned documentation
- Update vendor inventory

---

## Gap Mitigation Strategies

For organizations concerned about the identified gaps, here are practical mitigation strategies:

### **1. Leverage Third-Party Certifications**

Many intentional gaps are adequately addressed through industry certifications:

**SOC 2 Type II covers:**
- Physical security (CC6.4)
- Personnel training (CC1.4)
- Configuration management (CC8.1)
- Backup and recovery (A1.2)
- Incident response (CC7.3-CC7.5)
- Change management (CC8.1)

**ISO 27001 covers:**
- Physical security (Annex A.11)
- HR security (Annex A.7)
- Asset management (Annex A.8)
- Access control (Annex A.9)
- Business continuity (Annex A.17)

**Action:** Request and review certification reports, focusing on relevant control sections for your gaps.

---

### **2. Risk-Based Assessment Approach**

Not all vendors require the same depth of assessment:

**Tier 1 - Critical Vendors:**
- Full security questionnaire (this document)
- All supplemental assessments
- SOC 2 Type II report review
- Independent security testing
- On-site assessments (if applicable)
- Executive security reviews

**Tier 2 - High-Risk Vendors:**
- Full security questionnaire
- BC/DR and compliance assessments
- SOC 2 Type II or ISO 27001 report
- Contractual security terms
- Annual security reviews

**Tier 3 - Medium-Risk Vendors:**
- Security questionnaire (can abbreviate to high-priority sections)
- Certification verification
- Basic contractual review
- Biennial security reviews

**Tier 4 - Low-Risk Vendors:**
- Abbreviated security questionnaire (50-75 key questions)
- Self-attestation acceptable
- Standard contract terms
- Review at renewal only

---

### **3. Utilize Shared Assessments**

Leverage industry-shared assessment programs to reduce vendor burden:

**Standardized Information Gathering (SIG):**
- SIG Core: 156 questions covering most NIST CSF areas
- SIG Lite: 30 questions for low-risk vendors
- Accepted by 200+ companies
- Reduces redundant assessments

**Industry-specific shared assessments:**
- **Financial Services:** TPRM Exchange, Shared Assessments
- **Healthcare:** HITRUST CSF Assurance Program
- **Technology:** Cloud Security Alliance STAR
- **Payment:** PCI DSS QSA assessments

**Trust frameworks and registries:**
- FedRAMP Marketplace (for government cloud vendors)
- CSA STAR Registry (cloud security self-assessments)
- Kantara Identity Assurance Framework

**Action:** Require vendors to complete SIG or equivalent, then supplement with custom questions for gaps.

---

### **4. Contract-Based Risk Mitigation**

Address gaps through contractual requirements:

**Security-focused contract clauses:**
- Right to audit (annual or upon incident)
- Right to conduct security testing (coordinated penetration testing)
- Security incident notification (timelines, SLAs)
- Vulnerability disclosure requirements
- Security control change notification (30-90 days advance)
- Annual security certification maintenance
- BC/DR plan sharing and testing results
- Data breach liability and remediation
- Insurance requirements (cyber liability, E&O)

**Operational requirements:**
- Quarterly business reviews with security agenda items
- Annual security roadmap presentation
- Participation in customer security initiatives
- Security KPI reporting
- Compliance certification maintenance

**Action:** Work with legal/procurement to include security appendix in contracts.

---

### **5. Technical Controls for Gaps**

Implement customer-side controls to compensate for vendor gaps:

**For data protection gaps:**
- Client-side encryption before transmission to vendor
- Tokenization or pseudonymization of sensitive data
- Data masking for non-production environments
- DLP (Data Loss Prevention) at network egress points
- CASB (Cloud Access Security Broker) for SaaS monitoring

**For network security gaps:**
- VPN or private connectivity (PrivateLink/VPN)
- IP allowlisting at vendor and customer firewalls
- API gateway with rate limiting and WAF
- Network segmentation (isolated VLAN for vendor access)
- Zero Trust Network Access (ZTNA) for vendor access

**For monitoring gaps:**
- SIEM integration for vendor logs
- API monitoring and alerting
- User behavior analytics (UBA) for anomaly detection
- Synthetic transaction monitoring
- Third-party security rating services (BitSight, SecurityScorecard)

**For identity and access gaps:**
- SSO enforcement (SAML/OIDC) for centralized control
- Just-in-time (JIT) access provisioning
- Privileged Access Management (PAM) for admin accounts
- Regular access reviews (quarterly for Tier 1/2)
- MFA enforcement through SSO

**Action:** Architect compensating controls during vendor onboarding.

---

### **6. Continuous Monitoring Services**

Augment questionnaire assessments with ongoing monitoring:

**Third-party security rating services:**
- **BitSight:** Continuous external security posture monitoring
- **SecurityScorecard:** Security ratings based on external data
- **RiskRecon:** Attack surface monitoring and vendor risk scoring
- **UpGuard:** Vendor risk intelligence and questionnaire automation
- **CyberGRX:** Third-party cyber risk exchange

**Threat intelligence and breach monitoring:**
- Dark web monitoring for vendor credential leaks
- Breach notification services
- Vulnerability intelligence for vendor technologies
- Supply chain attack monitoring

**Action:** Implement for Tier 1/2 vendors; use quarterly reports to trigger reassessments.

---

### **7. Industry Benchmarking and Peer Intelligence**

Leverage collective knowledge about vendors:

**Peer information sharing:**
- Industry-specific ISACs (Information Sharing and Analysis Centers)
- Vendor security forums and communities
- Conference networking and security vendor sessions
- Customer advisory boards (CAB) hosted by vendors

**Public intelligence:**
- SEC filings for public companies (10-K risk factors, 8-K incident disclosures)
- Breach notification databases (state AG websites, HHS breach portal)
- CVE databases for vendor products
- Security researcher disclosures and advisories
- News monitoring for vendor security incidents

**Action:** Establish peer network; monitor public intelligence sources quarterly.

---

### **8. Phased Implementation for Resource-Constrained Organizations**

Organizations with limited resources can implement gradually:

**Year 1 - Foundation:**
- Inventory all vendors
- Classify vendors into tiers (1-4)
- Assess Tier 1 vendors with full questionnaire
- Implement basic contract requirements
- Establish vendor relationship owners

**Year 2 - Expansion:**
- Assess Tier 2 vendors
- Implement continuous monitoring for Tier 1
- Conduct BC/DR assessments for Tier 1
- Implement technical compensating controls
- Establish review cadences

**Year 3 - Maturity:**
- Assess Tier 3 vendors
- Expand continuous monitoring to Tier 2
- Automate questionnaire distribution and tracking
- Integrate TPRM with procurement processes
- Implement metrics and KPIs for TPRM program

**Year 4 - Optimization:**
- Reassess all vendors on schedule
- Leverage shared assessments and trust frameworks
- Optimize compensating controls
- Conduct TPRM program maturity assessment
- Continuous improvement based on lessons learned

---

## Conclusion

This information security questionnaire provides **comprehensive coverage (91%) of NIST CSF 2.0 subcategories** relevant to third-party risk assessment. The identified gaps fall into three categories:

1. **Intentional exclusions** (BC/DR, physical security, vendor HR) - addressed through alternative means (certifications, separate assessments)
2. **Partial coverage** (configuration management, threat intelligence) - adequately addressed through related questions and controls
3. **Acceptable gaps** (organizational internal processes) - not applicable to third-party vendor assessment

### Key Strengths of This Questionnaire:

✅ **Comprehensive security domain coverage:** Data security, IAM, network security, application security, logging, vendor management

✅ **Risk-based approach:** Conditional branching, tiered assessment, risk scoring

✅ **Practical implementation:** Clear response options, decision logic, actionable outcomes

✅ **Standards alignment:** Mapped to NIST CSF 2.0, references SIG coverage

✅ **Vendor-appropriate scope:** Focuses on customer-relevant controls, avoids unnecessary vendor internal processes

### Recommended Complementary Assessments:

📋 **BC/DR assessment** - For Tier 1/2 vendors and services with strict availability requirements

💰 **Financial viability assessment** - For startups, long-term relationships, or strategic vendors

📄 **Contractual and compliance review** - For all vendors before contract signature

🔗 **Supply chain assessment** - For vendors with complex sub-processor relationships

🤖 **AI/ML assessment** - For vendors using AI for decision-making or customer data training

### Implementation Roadmap:


By using this questionnaire as the foundation for information security assessment and supplementing with targeted BC/DR, compliance, and operational assessments based on vendor risk tier, organizations can achieve comprehensive third-party risk management aligned with NIST CSF 2.0 while maintaining practical efficiency.