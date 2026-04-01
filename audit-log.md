# Master Audit Log — All 10 Prompts

| Prompt | Version | Change Made | Observed Effect | Lesson Learned |
|--------|---------|-------------|-----------------|----------------|
| 01 Appointment Reminder | v1.0 | Initial draft — no structure or constraints | Generic, inconsistent; omitted appointment time | Need role assignment and structured output |
| 01 Appointment Reminder | v1.1 | Added RACE role, variables, word limit, confirmation link | Professional and consistent; tone still generic | Need empathetic tone and clear action instructions |
| 01 Appointment Reminder | v1.2 | Added empathetic tone, room detail, exclusion rules, clearer CTA | Consistent, warm, actionable — editing time cut to <30s | Explicit exclusion constraints prevent sensitive data leakage |
| 02 Clinical Handover | v1.0 | Unstructured, no clinical framework | Narrative paragraphs; missed clinical categories | Need recognised structured format (ISBAR) |
| 02 Clinical Handover | v1.1 | Added nurse role, ISBAR structure, data variable | ISBAR present; Recommendation section too vague | Each ISBAR section needs explicit sub-prompts |
| 02 Clinical Handover | v1.2 | Added section formatting, URGENT flagging, no-inference rule | Clinically structured, safe — blank fields clearly marked | 'Do not infer' is critical in clinical settings |
| 03 Discharge Instructions | v1.0 | No specificity or audience definition | Generic; clinical terminology not patient-facing | Must specify audience (patient) and literacy level |
| 03 Discharge Instructions | v1.1 | Added pharmacist role, medication variable, plain-language | Better tone; no structure; safety warnings missing | Need explicit structure and safety warning inclusion |
| 03 Discharge Instructions | v1.2 | Added reading level, per-medication structure, warnings, constraints | Patient-safe, consistent, reviewable in <90 seconds | Reading level instruction significantly reduces clinical jargon |
| 04 GP Referral Letter | v1.0 | Unstructured initial draft | Generic; no clinical history or consistent form | Referral letters need structured clinical sections |
| 04 GP Referral Letter | v1.1 | Added GP role, patient IDs, specialist type, key sections | Improved structure; history section inconsistent | Ambiguous section instructions produce inconsistent depth |
| 04 GP Referral Letter | v1.2 | Full template, URGENT flagging, no diagnostic speculation | GP review time reduced from ~12 min to <2 min | 'Do not speculate on diagnosis' essential for clinical safety |
| 05 Incident Report | v1.0 | No context, structure, or constraints | Casual tone; blame language; inappropriate | Incident reports need strict factual, legally appropriate language |
| 05 Incident Report | v1.1 | Added role, factual language, anonymisation, blame exclusion | Better tone; no chronological structure or corrective actions | Need explicit chronological and corrective action structure |
| 05 Incident Report | v1.2 | Three-section structure, neutral language substitutions, no-inference | Legally appropriate, consistently structured | Specific substitute vocabulary improves legal appropriateness |
| 06 Patient Satisfaction | v1.0 | Minimal prompt, no role or constraints | Generic 'thank you' — no specific acknowledgement | Must require specific acknowledgement of stated concern |
| 06 Patient Satisfaction | v1.1 | Added role, empathy, word limit, acknowledgement | Better but formulaic; no action pathway | Prohibit formulaic phrases; require clear next-step |
| 06 Patient Satisfaction | v1.2 | Specific acknowledgement, prohibited phrases, escalation keywords | Significantly more personal; escalation flag caught 3 at-risk cases | Escalation keyword triggers are a low-cost safety mechanism |
| 07 Job Posting | v1.0 | No specificity | Generic; no qualifications or organisational context | Job ads need specific role details and compliance requirements |
| 07 Job Posting | v1.1 | Added HR role, AHPRA, inclusion statement, tone | More complete; salary/award missing; no structured format | Need structured format and salary band for compliance |
| 07 Job Posting | v1.2 | Full structure, AHPRA type, salary band, prohibited words | HR review reduced from 50 min to <10 min | Prohibited word lists enforce brand and professional register |
| 08 Policy Summary | v1.0 | No structure or audience specification | Shorter version of doc — technical language retained | Summarisation without constraints reproduces source language |
| 08 Policy Summary | v1.1 | Added plain-language, word limit, action highlighting | Better readability; actions buried; legislative items paraphrased | Must-do actions need separation; legislative items cannot be paraphrased |
| 08 Policy Summary | v1.2 | Version tracking, verbatim legislative rule, reading level | Zero policy omissions; approved for automated distribution | Verbatim instruction is non-negotiable for regulatory content |
| 09 Gap Analysis | v1.0 | Unstructured, no constraints | Named individual staff — privacy violation risk | Aggregate-only reporting must be explicitly required |
| 09 Gap Analysis | v1.1 | Added role, department aggregation, individual ID prohibition | Department-level correct; no prioritisation or confidence | Gap analysis needs prioritisation logic and confidence rating |
| 09 Gap Analysis | v1.2 | Added prioritisation, confidence rating, timeline, exec summary | Implemented as standard quarterly deliverable | Confidence ratings increase credibility for management audiences |
| 10 Media Statement | v1.0 | No specificity or constraints | Included liability language and commitments — unusable legally | Legal language constraints non-negotiable in crisis communications |
| 10 Media Statement | v1.1 | Added role, event variable, liability instruction, empathy | Better tone; no investigation framing; no attribution | Media statements need structural requirements and speaker attribution |
| 10 Media Statement | v1.2 | Exact structural template, death flag, prohibited words, spokesperson | Legal review reduced from 4 rounds to 1.5; statement in 90 min | In crisis communications, AI value is speed of first draft |
