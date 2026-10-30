# 01 - Scope and Methodology

> Fictional case study. Organization: Al-Nakheel Digital Pay (simulated).

## 1. Objective

Measure the organization's current cybersecurity posture against NCA ECC-2:2024, identify gaps, and produce a prioritized remediation roadmap that leadership can fund and track.

## 2. Scope

| In scope | Out of scope |
|---|---|
| Corporate IT, payment platform (cloud-hosted), one colocation DC | Customer-owned devices |
| All employees and contractors with system access | Sector-specific frameworks (e.g. SAMA CSF), noted for follow-up |
| Critical third parties hosting or processing company data | Full technical penetration test (sampled evidence only) |

## 3. Approach

1. **Kick-off and scoping:** confirm scope, stakeholders, and evidence owners.
2. **Evidence request:** issue the request list (workbook sheet `Evidence Request`).
3. **Review and interviews:** review documents; simulate interviews with CISO, IT, HR, Legal, and Procurement.
4. **Sampled technical verification:** spot-check configurations (e.g. MFA coverage, patch status, log retention).
5. **Scoring:** rate each control area using the maturity scale below.
6. **Gap rating and roadmap:** derive priority from maturity gap and control criticality.
7. **Reporting:** executive summary plus technical findings.

## 4. Maturity scale

| Score | Level | Meaning |
|---|---|---|
| 0 | Non-existent | No control or documentation |
| 1 | Initial / ad hoc | Informal, person-dependent, undocumented |
| 2 | Documented | Policy or procedure exists but is not consistently implemented |
| 3 | Implemented | Implemented and operating, evidence available |
| 4 | Measured | Monitored with KPIs, reviewed periodically |
| 5 | Optimized | Continuously improved, automated where feasible |

**Target score:** 3 for most control areas; 4 for areas flagged critical. Targets are set in the workbook and can be changed.

## 5. Gap priority

Priority is computed in the workbook:

`Gap = Target - Current` (never below 0)
`Priority score = Gap x Criticality weight (1-3)`

| Priority score | Rating |
|---|---|
| 0 | Compliant |
| 1-2 | Low |
| 3-4 | Medium |
| 5-6 | High |
| 7+ | Critical |

## 6. Assumptions and limitations

- All evidence and findings are simulated.
- Control wording and numbering must be checked against the official NCA ECC-2:2024 publication.
- Crosswalk mappings are indicative, not one-to-one.
