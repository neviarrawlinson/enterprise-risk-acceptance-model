# Tiered Risk Acceptance Model

This model balances operational agility with appropriate oversight. Not all risks require the same level of deliberation.

---

## Tier 1: Tactical / Short-Term Exception

**Use Case:**  
Operational constraints prevent immediate remediation (e.g., delaying a security patch during a live event or critical business window).

**Typical Duration:** 1–14 days  
**Approval Authority:** System Owner + Security Delegate  
**SLA for Decision:** 24–48 hours  

**Requirements:**
- Defined remediation date
- Compensating controls implemented
- Clear scope and justification
- Expiration date

This tier enables operational continuity while maintaining accountability.

---

## Tier 2: Standard Risk Acceptance

**Use Case:**  
Control gaps due to vendor limitations, technical debt, or temporary resource constraints.

**Typical Duration:** 30–180 days  
**Approval Authority:** Business Risk Owner + Security + Compliance (if applicable)  
**SLA for Decision:** 5–10 business days  

**Requirements:**
- Documented business impact
- Residual risk rating
- Mitigation roadmap
- Defined expiration and review cadence

---

## Tier 3: Material Risk Acceptance (Executive Visibility)

**Use Case:**  
High-impact risks affecting sensitive data, regulatory exposure, or large operational footprint.

**Typical Duration:** 90–365 days (with recurring review)  
**Approval Authority:** Executive Risk Owner (VP/SVP) + CISO or Risk Committee  
**SLA for Decision:** 10–15 business days  

**Requirements:**
- Formal impact analysis
- Compensating controls documented
- Executive-level acknowledgement
- Ongoing monitoring and review schedule

---

## Automatic Escalation Triggers

Escalate to Tier 3 when any of the following are present:

- Significant customer data exposure risk
- Regulatory or contractual liability
- Repeated renewals without remediation progress
- Active exploitation environment
- Enterprise-wide system impact
