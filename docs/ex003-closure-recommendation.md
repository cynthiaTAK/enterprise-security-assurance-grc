# EX-003 — Closure recommendation (simulated)

**Finding:** Delayed account deactivation and missing failure alert  
**Control area:** User access termination / automated offboarding  
**Decision:** **Recommend closure; final approval pending**

## Background
A fictional former contractor's account remained active for 12 days after termination. Two post-termination logins were investigated. One was attributed to automated synchronization; the other was later classified as unauthorized. The investigation did not identify sensitive data access within the reviewed logs.

## Initial control test
Five simulated offboarding tests were executed. Four passed. One account remained active six hours beyond the required timeframe; no failure alert was generated. Observed sample pass rate: **4/5 = 80%**. The failure and missing alert were documented as deficiencies.

## Remediation and retest
The exercise describes an automation fix and new failure alerting. Ten subsequent disablement tests reportedly passed and a simulated failure reportedly generated an alert acknowledged by Security Operations. At the final review stage, the scenario stipulates that GRC validated the supporting logs, change approval, root-cause analysis, completed investigation and risk-owner review.

## Closure assessment
- Technical remediation evidence: **Validated in the simulated final-review scenario**.
- Historical finding and initial failed test: **Retained**.
- Risk-owner review: **Completed in the simulated final-review scenario**.
- Designated closure approver's decision: **Pending**.
- **Finding status: Open — Pending Final Approval**.

## Remaining action
Obtain and retain the authorized closure decision, decision date, approver identity/role and approval evidence reference. Only then change EX-003's status to Closed. Evaluate historical SOC 2 implications separately and seek approval for any customer-facing statement.
