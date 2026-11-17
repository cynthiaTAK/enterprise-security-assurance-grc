# Enterprise Security Assurance & GRC Operations

**Independent cybersecurity GRC portfolio project | Fictional enterprise simulation | November 2026**

An evidence-driven simulation of a security assurance program for **Northstar Digital Services**, a fictional organization. This project demonstrates how a GRC analyst can coordinate customer security questionnaires, maintain an audit evidence register, document access control exceptions, track corrective actions, and prepare closure recommendations without overstating what the evidence proves.

> **Scope and authenticity:** Every organization, customer, account, ticket, investigation, approval scenario, and record here is fictional or simulated. This is a learning portfolio, not evidence of employment, a completed external audit, a SOC 2 certification, or real-world incident response. No customer data or production credentials are included.

## Project at a glance

| Workstream | Sample deliverable | Demonstrated skill |
|---|---|---|
| Customer assurance | `data/questionnaire_register.csv` | Evidence-backed responses and disclosure approval |
| SOC 2 readiness | `data/soc2_evidence_register.csv` | Evidence requests, control mapping and gaps |
| Access governance | `data/exception_register.csv` | Risk and exception lifecycle |
| Corrective control testing | `data/offboarding_tests.csv` | Test results, failed control handling and retesting |
| Remediation | `data/remediation_plan.csv` | Owner assignment and validation criteria |
| Finding closure | `docs/ex003-closure-recommendation.md` | Separation of evidence validation and authorized approval |

## Case study: EX-003 — contractor offboarding

1. A simulated quarterly access review identified a former contractor account left active for **12 days** after termination.
2. Simulated investigation identified **two post-termination login events**, including one later classified as unauthorized. No sensitive data access was identified **within the reviewed logs**; this does not establish that none occurred.
3. An initial automated offboarding test passed **4 of 5** cases (**80% observed sample pass rate**). One account exceeded the disablement deadline by six hours, and the failure generated no alert.
4. Following simulated remediation, IAM reported **10 of 10** passing disablement tests and a successful failure-alert test. The exercise later stipulated that supporting logs, approvals, investigation records, and risk review had been validated.
5. **EX-003 remains open pending final authorized closure approval.** Later retesting does not erase the original deficiency or prove operating effectiveness across a historical SOC 2 audit period.

## Other connected scenarios

- **SA-001 / Q-002:** Customer Cedar Health asks whether access permissions are reviewed periodically. A policy and quarterly report exist, but the response remains **pending Security/GRC approval**.
- **EX-001 / RA-001:** MFA evidence gaps and a narrowly scoped risk acceptance for two non-interactive service accounts; risk acceptance does not automatically resolve evidence gaps.
- **EX-002 / EV-003:** Excessive administrator permissions on a service account; simulated least-privilege remediation and owner approval supported a separate closure decision.

## Repository structure

```text
enterprise-security-assurance-grc/
├── README.md
├── LICENSE
├── .gitignore
├── data/
│   ├── questionnaire_register.csv
│   ├── soc2_evidence_register.csv
│   ├── exception_register.csv
│   ├── offboarding_tests.csv
│   └── remediation_plan.csv
├── docs/
│   ├── methodology-and-limitations.md
│   ├── ex003-closure-recommendation.md
│   ├── customer-response-draft.md
│   ├── interview-walkthrough.md
│   └── publishing-guide.md
└── templates/
    └── evidence-review-template.md
```

## Methodology

**Intake → identify control and owner → request evidence → evaluate completeness and scope → document exceptions → coordinate remediation → validate corrective evidence → obtain authorized approval → retain the audit trail.**

SOC 2 Trust Services Criteria references in this repository are **illustrative learning mappings** and not an auditor-approved control matrix. The test counts are simulated examples, not statistically representative audit samples. See [methodology and limitations](docs/methodology-and-limitations.md).

## Skills demonstrated

Governance, Risk & Compliance (GRC) · Customer Security Assurance · SOC 2 Evidence Coordination · Identity and Access Management (IAM) · User Access Reviews · Control Testing · Audit Documentation · Risk & Exception Tracking · Remediation Validation · Security Operations Coordination · Excel / CSV Tracking

## How to review

Start with [the EX-003 closure recommendation](docs/ex003-closure-recommendation.md), then review the [offboarding test data](data/offboarding_tests.csv), [remediation plan](data/remediation_plan.csv), and [customer questionnaire draft](docs/customer-response-draft.md). The [interview walkthrough](docs/interview-walkthrough.md) summarizes the project for recruiters and hiring managers.

## Author

Independent portfolio project. Optional: add your GitHub profile link and contact information after reviewing what you want to publish publicly.
