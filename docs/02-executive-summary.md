# 02 - Executive Summary

> Fictional case study: Al-Nakheel Digital Pay, a simulated Riyadh-based fintech. All findings and scores are simulated.

## Purpose
This assessment measured Al-Nakheel Digital Pay's cybersecurity posture against the NCA Essential Cybersecurity Controls (ECC-2:2024) across 4 domains, 28 subdomains and 108 main controls, with a crosswalk to ISO 27001:2022 and NIST CSF 2.0.

## Overall result
- Current average maturity is **2.21 out of 5**, against a target of **3.32**. The average gap is 1.11 points.
- **8** of 28 subdomains are rated Critical or High, **5** Medium, **8** Low, and **7** already meet target.
- **Strongest areas:** policies, endpoint and system protection, cryptography, physical security, and HR and awareness basics.
- **Weakest areas:** third-party risk, cloud security, monitoring and incident response, and cyber-resilient business continuity.

| Domain | Subdomains | Avg current | Avg target | Avg gap |
|---|---|---|---|---|
| 1 Governance | 10 | 2.30 | 3.10 | 0.80 |
| 2 Defense | 15 | 2.27 | 3.33 | 1.07 |
| 3 Resilience | 1 | 2.00 | 4.00 | 2.00 |
| 4 Third-Party and Cloud | 2 | 1.50 | 4.00 | 2.50 |

## Top 5 priorities
| # | Area | Why it matters | Recommended action |
|---|---|---|---|
| 1 | 4-1 Third-Party Cybersecurity (Critical) | Vendors handle payment and customer data with no tiering, due diligence or contract clauses. | Tier the top 20 vendors in 30 days; assess tier-1 vendors and add security clauses within 180 days. |
| 2 | 4-2 Cloud Computing and Hosting | Shared responsibility is undocumented and cloud posture is not monitored. | Document the shared-responsibility matrix and deploy cloud posture monitoring within 90 days. |
| 3 | 3-1 Business Continuity | Cyber-recovery scenarios and recovery targets have never been tested. | Run a cyber-recovery test and validate RTO and RPO within 180 days. |
| 4 | 2-13 Incident and Threat Management | An incident response plan exists but has never been exercised. | Update the plan and run a tabletop exercise within 90 days. |
| 5 | 2-12 Logs and Monitoring | Logging is partial and there is no 24/7 monitoring. | Onboard cloud and endpoint logs to a SIEM in 90 days; move to a managed SOC within a year. |

## Roadmap at a glance
- **30 days:** quick wins (MFA for privileged accounts, a restore test, vendor tiering, CISO reporting line).
- **90 days:** foundations (risk methodology, SIEM onboarding, incident exercise, patch SLAs, cloud posture monitoring).
- **180 days:** maturity (data classification, secure development gates, cyber-recovery test, vendor assessments).
- **365 days:** sustain (24/7 monitoring, independent compliance audit, asset inventory automation).

## Decisions requested from leadership
1. Approve moving the CISO reporting line out of IT.
2. Fund the SIEM and managed SOC and the cloud posture monitoring initiatives.
3. Mandate security due diligence in procurement for all tier-1 vendors.

## Basis and limitations
Simulated evidence and sampled verification only. Crosswalk mappings to ISO 27001:2022 and NIST CSF 2.0 are indicative. Control numbering follows the official NCA ECC-2:2024 document and should be verified before citing.
