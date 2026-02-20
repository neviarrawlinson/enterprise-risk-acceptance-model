# Tiered Risk Acceptance Model

This model balances operational agility with appropriate oversight. Not all risks require the same level of deliberation.

---

## Tier 1: Tactical / Short-Term Exception

**Use Case:**  
Operational constraint prevents immediate remediation (e.g., delaying a security patch during a live production window).

**Typical Duration:** 1–14 days  
**Approval Authority:** System Owner + Security Delegate  
**Decision SLA:** 24–48 hours  

**Requirements:**
- Defined remediation date
- Compensating controls implemented
- Clear scope and justification
- Expiration date

---

## Tier 2: Standard Risk Acceptance

**Use Case:**  
Control gaps due to vendor limitations, technical debt, or temporary constraints.

**Typical Duration:** 30–180 days  
**Approval Authority:** Business Risk Owner + Security + Compliance (if applicable)  
**Decision SLA:** 5–10 business days  

**Requirements:**
- Documented business impact
- Residual risk rating
- Mitigation roadmap
- Expiration and review cadence

---

## Tier 3: Material Risk Acceptance (Executive Visibility)

**Use Case:**  
High-impact risks affecting sensitive data, regulatory exposure, or enterprise-wide systems.

**Typical Duration:** 90–365 days (with recurring review)  
**Approval Authority:** Executive Risk Owner (VP/SVP) + CISO or Risk Committee  
**Decision SLA:** 10–15 business days  

**Requirements:**
- Formal impact analysis
- Compensating controls documented
- Executive-level acknowledgement
- Ongoing monitoring
