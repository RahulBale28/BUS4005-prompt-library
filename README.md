# BUS4005 — Assessment 1: AI Prompt Library
## Healthcare Workflow Automation — Public Acute-Care Hospital

This repository contains the iterative prompt development portfolio for BUS4005 Assessment 1.
Each prompt folder contains three version files (v1.0 → v1.1 → v1.2) documenting the
full prompt text and the changes made at each iteration.

---

## Prompt Index

| # | Prompt | Workflow Area |
|---|--------|--------------|
| 01 | Patient Appointment Reminder | Outpatient Scheduling |
| 02 | Clinical Handover Summary | Nursing Handover |
| 03 | Medication Discharge Instructions | Discharge Planning |
| 04 | GP Referral Letter | Specialist Referral |
| 05 | Staff Incident Report Narrative | Clinical Governance |
| 06 | Patient Satisfaction Survey Response | Patient Experience |
| 07 | Job Posting — Clinical Roles | HR Recruitment |
| 08 | Internal Policy Summary for Staff | Policy & Compliance |
| 09 | Training Needs Gap Analysis | L&D / Workforce |
| 10 | Media/PR Statement — Clinical Incident | Communications & Risk |

---

## How to Read This Repo

Each prompt folder (`prompts/prompt-XX-name/`) contains:
- `v1.0.md` — Initial raw draft
- `v1.1.md` — First iteration with structural improvements
- `v1.2.md` — Final polished version used in the assessment report

The commit history of this repository serves as the version log.

---

## Prompting Frameworks Used

- **RACE** (Role, Action, Context, Execute) — applied to all 10 prompts
- **Constraint-first design** — word limits, prohibited phrases, reading level targets
- **Escalation triggers** — keyword-based flags for human review routing
- **Exclusion rules** — 'do not infer' instructions for clinical safety
