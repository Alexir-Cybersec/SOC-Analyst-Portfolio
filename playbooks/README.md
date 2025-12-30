# Playbooks

This folder contains reusable **SOC playbooks** built from labs/simulated environments.
They are designed to be repeatable and ticket-ready.

## Current playbooks

- [Phishing Triage](phishing-triage.md)
- [Malware / Endpoint Triage](malware-endpoint-triage.md)

## Playbook structure

Each playbook follows this structure:

- Purpose
- Trigger examples
- Preconditions (logs/tools/data needed)
- Triage checklist
- Investigation workflow (pivots)
  - Pivot A — Account/User
  - Pivot B — Endpoint/Host
  - Pivot C — Network/Web
  - Pivot D — IOC enrichment
- Decision matrix (likely outcome + action)
- Containment actions
- Escalation guidance
- Ticket template
- Detection improvements

## Notes

- All content is sanitized and based on lab/simulated environments.

## Naming convention

`<topic>-triage.md`
