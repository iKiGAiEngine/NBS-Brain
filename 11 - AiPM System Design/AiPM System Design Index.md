---
type: index
status: active
owner: AiPM Product Owner
review_cycle: monthly
classification: internal-framework
---

# AiPM System Design Index

AiPM is the operational execution layer for approved NBS processes and business rules.

Every feature requirement should link to:

- the business problem and desired outcome
- governing process and business rules
- users, permissions, and accountable owner
- required inputs, outputs, and source-of-truth records
- normal workflow and exception paths
- approvals, audit history, and notifications
- failure handling, backups, and manual fallback
- acceptance criteria and success measures

## Design Rule

Do not automate an unclear or unapproved process. AiPM should reduce duplicate work, make commitments visible, surface exceptions, and preserve human approval at appropriate boundaries.