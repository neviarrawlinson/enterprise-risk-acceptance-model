# Risk Scoring Methodology

This model distinguishes between inherent risk and residual risk to support structured, defensible risk acceptance decisions.
---

## 1. Inherent Risk

Inherent risk represents the level of risk before controls are applied.

### Formula

Inherent Risk = Likelihood × Impact

---
## 2. Likelihood Scale (1–5)

1 – Rare  
2 – Unlikely  
3 – Possible  
4 – Likely  
5 – Almost Certain  

---
## 3. Impact Scale (1–5)

1 – Negligible  
2 – Minor  
3 – Moderate  
4 – Significant  
5 – Severe / Material  

Impact considers:

- Financial loss
- Regulatory exposure
- Customer data impact
- Reputational damage
- Operational disruption
  
---
## 4. Control Effectiveness Rating

High – Controls strongly mitigate risk  
Moderate – Controls partially mitigate risk  
Low – Controls provide limited mitigation  

---

## 5. Residual Risk Determination

Residual Risk = Inherent Risk adjusted by Control Effectiveness

Example logic:

- High effectiveness: Reduce risk by 50%
- Moderate effectiveness: Reduce by 25%
- Low effectiveness: Minimal reduction

Residual Risk must be documented before risk acceptance.

---

## 6. Tier Mapping Logic

Residual Risk Score Range:

1–6 → Tier 1  
7–14 → Tier 2  
15–25 → Tier 3  

Tier classification determines approval routing and SLA.

---

## Guiding Principle

Risk scoring must be:

- Consistent
- Defensible
- Transparent
- Repeatable
