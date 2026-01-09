# Write-ups

This folder contains **sanitized SOC-style write-ups** that show how I think through alerts and incidents:

- what happened (summary),
- what evidence I used,
- how I triaged and validated,
- what I concluded (verdict),
- what I would do next (containment / remediation / prevention).

> Notes and raw screenshots live in my private repo.
> This public repo contains only **sanitized** write-ups and supporting images in `../images/`.

---

## How to read these write-ups

Each write-up follows a consistent structure:

- **Executive Summary**: 3–6 bullets (what happened + impact + verdict)
- **Environment / Context**: what the scenario is (lab/simulated SOC platform)
- **Evidence Collected**: artifacts and logs used
- **Triage & Analysis**: step-by-step reasoning and pivots
- **Findings**: key observations and what they mean
- **Verdict**: True Positive / False Positive / Benign / Suspicious
- **Recommendations**: what to tune, monitor, or improve
- **Appendix** (optional): query snippets used (KQL/SPL), IoC table
