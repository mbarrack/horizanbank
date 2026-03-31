# Horizon Bank Architecture Estate — Dummy Data
Generated: March 2026  |  Purpose: Architecture as Data PoC

## Bank context
- **Horizon Bank** — fictional Australian bank
- **Coastal Bank** — retail brand (replaces any NP references)
- **Summit Bank** — second brand (replaces any GB references)
- **ADA members**: Chris Chandran (CTO/Chair), Priya Nair (CISO), Blake Nguyen (Head Tech Delivery), Casey McQuaid (Head Data), Taylor Barker (Head Enterprise Services), Drew Hartley (Head Platforms)

## Tables

| File | Records | Description |
|---|---|---|
| solutions.json | 15 | Core solution records |
| technology_stack.json | 19 | Technology components per solution |
| approved_components.json | 20 | Approved component registry |
| capabilities.json | 14 | Business capability hierarchy L1/L2 |
| governance_status.json | 10 | ADA approval status per solution |
| lifecycle_flags.json | 12 | ITPHA health scores and findings |
| decision_log.json | 10 | Architecture decisions with rationale |
| target_state_architecture.json | 5 | Domain-level target state |
| roadmap_initiatives.json | 8 | Roadmap with wave, cost, status |
| estate_master.json | all | All tables in one file |

## Key solutions

| ID | Solution | Status | Notes |
|---|---|---|---|
| SOL001 | Horizon Serviceability Engine | Approved — Live | Replaced Excel BSC (SOL014) |
| SOL002 | Horizon Open Banking CDR Platform | Approved — Transitioning | ACCC compliance |
| SOL003 | Architecture as Data Platform | Draft | This project |
| SOL004 | Broker Portal New Experience | Submitted | Replacing SOL015 |
| SOL005 | Enterprise Data Hub | Approved — Live | Snowflake + ADF |
| SOL006 | Customer Identity Platform | Approved — Live | Entra External ID |
| SOL007 | Payments Modernisation NPP | Draft | RBA mandate |
| SOL008 | Fraud Detection AI Engine | Conditionally Approved | AI guardrails pending |
| SOL009 | Oracle Siebel CRM | Retiring Jun 2026 | EOL — migrating to SOL010 |
| SOL010 | Salesforce CRM | Approved — Transitioning | Replacing SOL009 |
| SOL011 | IBM DataPower Gateway | Retiring Sep 2026 | EOL — migrating to APIM |
| SOL012 | Core Banking Temenos Transact | Approved — Stale 171 months | Cloud assessment overdue |
