# Decisions, Assumptions and Validation Log

This file separates current decisions from hypotheses that still require evidence.

## Decisions currently adopted

### Business model
- SecureOps 365 will be designed as a **Managed Digital Operations** business rather than a generic break/fix MSP.
- The core commercial engine is recurring managed service revenue.
- Paid diagnostics and remediation precede recurring management.
- Proprietary SaaS will not be built before repeated customer patterns are observed.

### Initial customer profile
- Primary size band: approximately **20–100 employees**.
- Expansion to approximately 150 employees where operational complexity remains suitable.
- Very small businesses are not the preferred starting segment.

### Initial vertical focus
- Professional services.
- Mining/METS contractors and suppliers.
- Construction / field-service businesses.
- Regionality is treated as an operating requirement rather than a standalone vertical.

### Service boundaries
- No direct safety-critical OT/SCADA/PLC engineering initially.
- MDR/SOC should be partner-delivered initially.
- Legal/regulatory interpretation should remain with qualified advisers.
- Formal assurance claims must match actual assessor competence.

### Technology direction
- Microsoft 365 / Entra / Intune / Defender form the preferred workplace/security baseline where appropriate.
- Use mature commercial PSA, RMM, documentation, backup and SOC platforms rather than building equivalents.

## Working commercial assumptions requiring validation

- SecureOps 365: approximately **$175/user/month**.
- SecureOps Assured: approximately **$225/user/month**.
- Operations Risk & Waste Review: approximately **$2,500–$4,500**.
- Onboarding/remediation: often **$7,500–$20,000**, depending on technical debt.
- Automation Sprint: approximately **$7,500–$25,000**.
- Managed-service gross-margin design target: **45–55% after standardisation**.
- A minimum monthly recurring commitment is likely necessary.

These are launch hypotheses, not validated market facts.

## Geographic assumptions

Current market-only view:
- Victoria/Melbourne is attractive for initial professional-services validation.
- Brisbane/Central Queensland and Newcastle/Hunter are attractive for mining/METS and field-business validation.
- Perth is commercially attractive but appears comparatively mature and competitive for the exact mining/cyber/MSP proposition.

Founder relationships and referral access may override this theoretical sequence.

## Questions that must be answered through validation

1. Will target customers pay for a diagnostic rather than demand a free audit?
2. Will 20–100 employee businesses accept $175–$225/user/month pricing?
3. Which buying trigger produces the shortest sales cycle?
4. Which vertical has the most repeatable pain?
5. What is the actual support load per managed user?
6. What is the true cost stack after PSA, RMM, backup, MDR/SOC, documentation, insurance and labour?
7. How much remediation is typically required before recurring support can begin?
8. Which partner channel generates qualified demand most efficiently?
9. Which customer evidence requests recur often enough to become a product feature?
10. Which automation patterns repeat across multiple customers?

## Software decision gate

Do not fund a proprietary operations platform until approximately 10–20 customers provide evidence that the same workflows, evidence requirements and reporting needs repeat often enough to justify product development.

Potential future software areas remain hypotheses:
- security evidence collection;
- identity and device posture;
- supplier-assurance packs;
- cyber-insurance evidence;
- licence optimisation;
- workflow/automation outcome measurement;
- AI-governance reporting;
- risk and improvement dashboards.

## Current status

**Status: Ready for structured customer validation.**

Next build items:
1. Detailed Operations Risk & Waste Review checklist and scoring model.
2. Live vendor cost stack.
3. First 100-account target list.
4. Partner prospect list.
5. Customer-facing one-page offer and discovery script.
6. Detailed financial workbook after vendor costs are confirmed.
