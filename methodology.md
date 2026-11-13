# Risk Assessment Methodology

**Framework:** NIST SP 800-30 Rev. 1 — Guide for Conducting Risk Assessments  
**System:** ShopCore (fictional e-commerce web application)

---

## Process Overview

This risk register was built using the four-step process from NIST SP 800-30:

1. **Prepare** — Define the system, its boundaries, data types, and users
2. **Conduct** — Identify threat sources, threat events, and vulnerabilities; then score likelihood and impact
3. **Communicate** — Document findings in the risk register
4. **Maintain** — Assign ownership and track treatment status

---

## Threat Identification

Threats were identified using NIST 800-30 Appendix D (Threat Sources) and Appendix E (Threat Events). Categories covered:

- **Adversarial** — External attackers, malicious insiders, compromised third parties
- **Accidental** — Human errors, misconfigurations, unintentional data exposure
- **Structural** — Hardware/software failures, dependency failures
- **Environmental** — Power outages, natural disasters

---

## Vulnerability Identification

Vulnerabilities were mapped using NIST 800-30 Appendix F (Vulnerabilities and Predisposing Conditions). Each vulnerability was linked to the specific threat it enables.

---

## Likelihood Scoring (1–5)

| Score | Label | Definition |
|---|---|---|
| 1 | Very Low | Event is highly unlikely; strong controls in place |
| 2 | Low | Event is unlikely; some controls exist |
| 3 | Moderate | Event could occur; partial controls |
| 4 | High | Event is likely; weak or missing controls |
| 5 | Very High | Event is almost certain; no effective controls |

---

## Impact Scoring (1–5)

| Score | Label | Definition |
|---|---|---|
| 1 | Very Low | Negligible effect on operations or data |
| 2 | Low | Minor disruption, no data loss |
| 3 | Moderate | Significant disruption, limited data exposure |
| 4 | High | Major disruption, significant data breach |
| 5 | Very High | Catastrophic — severe financial, legal, or reputational damage |

---

## Risk Score Calculation

> **Risk Score = Likelihood × Impact**

Maximum possible score: 25

| Score Range | Risk Level |
|---|---|
| 1–5 | Low |
| 6–12 | Medium |
| 13–19 | High |
| 20–25 | Critical |

---

## Treatment Types

| Type | Meaning |
|---|---|
| **Mitigate** | Implement a control to reduce likelihood or impact |
| **Accept** | Acknowledge the risk; no action taken (usually Low risks) |
| **Transfer** | Shift risk to a third party (e.g., insurance, vendor contract) |
| **Avoid** | Eliminate the activity that creates the risk |

---

## References

- NIST SP 800-30 Rev. 1: https://csrc.nist.gov/publications/detail/sp/800-30/rev-1/final
- NIST SP 800-53 Rev. 5 (control reference): https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final
