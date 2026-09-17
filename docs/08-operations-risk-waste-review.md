# Operations Risk & Waste Review

## Purpose

This is the proposed first paid customer engagement for SecureOps 365.

It is designed to answer three management questions:

1. **Where could technology materially disrupt or expose the business?**
2. **Where is the business wasting money or operational effort?**
3. **Which repetitive work is worth automating?**

It is not intended to be a formal legal-compliance opinion, penetration test, Essential Eight certification or OT-security assessment.

## Commercial hypothesis

**Indicative fee:** $2,500–$4,500 ex GST.

Expected delivery window and actual engineering effort must be validated during the first three paid engagements.

## Review structure

### Domain 1 — Identity and access

Review:
- MFA coverage;
- privileged accounts;
- stale accounts;
- shared accounts;
- guest users;
- Conditional Access posture;
- joiner/mover/leaver process;
- emergency/break-glass access;
- service-account ownership;
- passwordless readiness where relevant.

Evidence examples:
- Entra user/export reports;
- role assignments;
- authentication-method reports;
- Conditional Access policies;
- HR/IT termination workflow.

### Domain 2 — Devices and endpoints

Review:
- authoritative device inventory;
- managed vs unmanaged devices;
- encryption;
- endpoint protection;
- OS support status;
- patching;
- local admin rights;
- mobile/BYOD controls;
- lost/stolen-device procedure;
- device retirement process.

### Domain 3 — Microsoft 365 and collaboration

Review:
- tenant baseline;
- Exchange/email security;
- SharePoint/OneDrive sharing;
- Teams external access;
- guest collaboration;
- retention requirements;
- risky forwarding rules;
- licence allocation;
- unused or duplicated licences.

### Domain 4 — Backup and recovery

Review:
- what is backed up;
- what is not backed up;
- Microsoft 365 backup assumptions;
- server/workload backup;
- immutable/offsite considerations where relevant;
- retention;
- last successful restore test;
- recovery ownership;
- recovery time expectations;
- dependency on individual staff knowledge.

### Domain 5 — Security operations

Review:
- endpoint detection/response;
- vulnerability-management process;
- security-alert ownership;
- phishing/security awareness;
- incident-response contacts;
- logging;
- cyber-insurance control requirements;
- supplier/customer security questionnaires;
- Essential Eight-oriented gaps where relevant.

### Domain 6 — Network and connectivity

Review:
- firewall/router ownership;
- firmware/support status;
- wireless configuration;
- guest-network separation;
- remote access;
- VPN use;
- internet dependency;
- backup connectivity;
- regional/site resilience;
- documentation of network assets.

### Domain 7 — Business applications and SaaS

Review:
- critical applications;
- system owner;
- licence count;
- SSO/MFA availability;
- unsupported applications;
- duplicated tools;
- orphaned accounts;
- integrations;
- vendor dependency;
- business continuity implications.

### Domain 8 — Operational resilience

Review:
- key-person dependency;
- device replacement process;
- spare equipment;
- outage procedures;
- site power risk;
- remote-work fallback;
- supplier escalation contacts;
- documented recovery priorities;
- critical business process dependencies.

### Domain 9 — Process waste and automation

Interview business owners and selected staff.

Ask:
- What do you copy and paste repeatedly?
- Which information is entered into more than one system?
- What spreadsheet controls an important process?
- Which report takes hours every week/month?
- What happens when a new customer starts?
- What happens when an employee starts or leaves?
- Which approvals are chased manually?
- Which email types recur frequently?
- Which documents are repeatedly created from templates?
- Where do staff wait for information rather than add value?

For each candidate process capture:
- staff involved;
- frequency;
- minutes/hours per occurrence;
- approximate loaded labour cost;
- error/rework rate where known;
- operational risk;
- systems involved;
- automation suitability;
- human approval requirements.

### Domain 10 — Regulatory / contractual evidence

Only assess implementation/evidence mechanics, not legal interpretation.

Possible areas:
- customer supplier-security questionnaires;
- cyber-insurance evidence;
- AML/CTF workflow requirements supplied by advisers;
- contractual access-control requirements;
- document retention requirements;
- industry/customer cyber requirements;
- policy acknowledgement evidence.

## Scoring model

Each control area receives two separate scores.

### Risk score

| Score | Meaning |
|---|---|
| 0 | Not applicable / no meaningful exposure identified |
| 1 | Well controlled; minor improvement only |
| 2 | Moderate weakness or unclear ownership |
| 3 | Material weakness requiring planned remediation |
| 4 | High-risk gap requiring priority remediation |
| 5 | Critical exposure or single point of failure requiring immediate action |

### Evidence confidence

| Score | Meaning |
|---|---|
| A | Verified directly through configuration/report/evidence |
| B | Documented but not technically verified |
| C | Based mainly on staff statement |
| D | Unknown / no reliable evidence available |

This prevents a customer from appearing secure merely because someone says a control exists.

Example:

**MFA: Risk 1 / Evidence A** = strong.

**Backups: Risk 2 / Evidence D** = potentially much more concerning because recovery has not been verified.

## Waste model

For identified technology waste record:

- product/service;
- quantity;
- monthly cost;
- actual usage;
- duplicate capability;
- contract constraint;
- recoverable monthly amount;
- recoverable annual amount.

Do not promise savings until licence terms and dependencies are verified.

## Automation opportunity calculation

Working estimate:

**Annual manual cost = people involved × time per occurrence × frequency × loaded hourly cost**

Then estimate:
- percentage realistically automatable;
- implementation cost;
- recurring platform/support cost;
- risk/complexity;
- approximate payback period.

Do not present speculative AI productivity as guaranteed savings.

## Final customer deliverable

The management report should contain:

### Page 1 — Executive summary
- overall business risk themes;
- urgent actions;
- estimated recoverable technology waste;
- strongest automation opportunities.

### Priority remediation table

| Priority | Finding | Business impact | Evidence | Recommended action |
|---|---|---|---|---|
| P1 | Critical/high risk | Immediate material exposure | Verified/uncertain | 0–30 days |
| P2 | Material weakness | Significant risk/cost | Evidence stated | 30–90 days |
| P3 | Improvement | Efficiency/governance | Evidence stated | 90–180 days |

### Technology waste
- licences;
- duplicated services;
- avoidable spend;
- unsupported/legacy cost.

### Automation shortlist
For each candidate:
- current annual manual effort;
- estimated automation potential;
- implementation complexity;
- expected payback range;
- recommended next step.

### 90-day roadmap
Separate into:
- Stabilise;
- Secure;
- Standardise;
- Automate.

### Recurring operating recommendation
State whether the customer appears best suited to:
- customer-managed remediation only;
- SecureOps 365;
- SecureOps Assured;
- RegulatedOps add-on;
- ContractReady Resources;
- FieldOps / Regional Resilience.

## Internal qualification rules

The review should also determine whether SecureOps should accept the customer.

Red flags:
- refuses MFA or essential security controls;
- expects unsupported systems to remain indefinitely;
- demands unlimited project work inside recurring fee;
- materially unsafe environment with no remediation budget;
- requires unsupported OT responsibility;
- adversarial relationship with current vendors or staff without a reasonable transition plan;
- refuses administrative access necessary to provide accountable service.

## Validation metrics for first three reviews

Record:
- hours spent in discovery;
- hours spent gathering evidence;
- hours spent analysing;
- hours spent writing report;
- customer price;
- delivery gross margin;
- remediation value identified;
- recurring service value proposed;
- customer objections;
- whether they converted;
- which findings repeated across customers.

After three paid reviews, revise this document based on real delivery data.
