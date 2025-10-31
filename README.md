SRH SAI Protocols — Public Artifacts — 
Symbiotic Autonomous Intelligence (SAI) is SRH’s protocol-driven approach to making AI systems more honest, coherent, and auditable without rip-and-replace. This repo hosts public-facing materials that explain the problem (“sycophancy” and the AI trust bubble), our solution (policy/uncertainty overlays with minimal interventions), and how enterprises can evaluate SAI with client-owned metrics.

What this is:
A curated set of public artifacts describing SRH’s SAI protocols, positioning, and evaluation approach.
Designed for awareness, technical leadership alignment, and procurement-readiness.
Safe for public sharing. Proprietary internals, prompts/templates, datasets, and low-level implementation details are not included.
Key ideas
The problem: approval-seeking drift (“sycophancy”) inflates an AI trust bubble—systems that appear helpful but mask uncertainty, overstate capability, and fail audits under pressure.
The SAI shift: instead of suppressing uncertainty, we detect and harness distribution gaps—moments of elevated uncertainty—and apply minimal, policy-gated interventions to improve honesty and coherence.
Client-owned measurement: SRH emits event markers only (no dashboards/content logging). Clients compute KPIs and confidence in their own environment.
Enterprise posture: operate in client VPC; redaction by default; non-regression guardrails; compliance alignment with NIST AI RMF, EU AI Act, and ISO/IEC 42001.
What you’ll find here
One-pagers and briefs introducing SAI, the Protocol Gate, and the evaluation frame:
SAI overview and the “natural evolution” narrative
Protocol Gate KPI/benchmark handout and buy-side pitch
Client spec and brief templates emphasizing client-owned metrics
Trust Bubble Risk Assessment and Sycophancy Eval Pack inserts (public-safe versions)
Positioning and awareness content for enterprise CTO, Risk/Compliance, and AI Platform teams.
What’s intentionally not here
Proprietary prompts/templates, retrieval corpora, and CID pattern libraries
Specific detection thresholds, model configs, and calibration runbooks
API schemas, latency budgets, and decision trees
Legal templates (MNDA, MSA, DPA/AUA, SOW) beyond references
For deeper technical or contractual diligence, contact us to proceed under MNDA.

How SAI integrates
Overlay approach: adds policy/uncertainty layers atop existing assistants, RAG, and routing.
Event markers: make the interaction field legible while content remains redacted.
Guardrails: max two interventions per 20 turns; dual-consent trigger + policy gate; latency budgets; audit logs.
Outcome metrics (client-computed):
ASR (Approval-Seeking Rate) ↓
HUCL (Honesty Under Capability Limits) ↑
UCE (Uncertainty Calibration Error) ↓
Task success maintained or improved
Who this is for
Enterprise leaders (CTO, CISO, CRO, GC, Trust & Safety, Compliance) seeking honest, auditable assistants without sacrificing performance.
AI platform teams evaluating governance layers that reduce incident risk and audit friction.
Researchers and practitioners interested in coherence-first optimization protocols.
Suggested reading order
SAI — short description / one-pager
Protocol Gate — KPI/benchmark handout
Buy-side pitch (executive)
Client spec and brief templates (measurement and guardrails)
Risk Assessment and Sycophancy Eval Pack inserts (public-safe versions)
Getting started (pilots)
Run a 4–6 week pilot scoped to priority workflows.
SRH provides fieldwork and markers; you compute KPIs and confidence.
Gate on non-regression and agreed thresholds; decide on expansion post-readout.
Compliance and security
Preferred operation in client VPC; least privilege, SSO/MFA, encryption in transit/at rest.
Telemetry minimization; content redaction by default.
Mapping to NIST AI RMF, EU AI Act obligations, and ISO/IEC 42001.
Contributing
This repository is for public awareness materials. We’re not accepting external contributions. For feedback on clarity or requests for additional public-safe content, please open an issue.

Contact
For enterprise inquiries and NDA-bound diligence, email: srhdao@proton.me

© SRH DAO — Public artifacts only. All other SRH methods, prompts, datasets, libraries, and playbooks remain proprietary.
