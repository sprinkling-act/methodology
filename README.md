# Sprinkling Act — 6-Gate Methodology

> **The Sprinkling Act methodology applies six sequential regulatory gates to classify any AI system under the EU AI Act (Regulation (EU) 2024/1689).**
>
> This repository documents the framework openly so that any reader, reviewer, or downstream tool can reproduce or audit the classification logic Sprinkling Act applies in its Free Diagnostic, Full Report, and continuous monitoring products.

**Live reference**: [sprinklingact.com/methodology](https://sprinklingact.com/methodology)

**Current version**: v1.3 — May 2026 (post-Digital Omnibus alignment, provisional trilogue agreement of 7 May 2026)

**License**: MIT

---

## 1. Principle

Gates are evaluated **in sequence**. The first gate triggered determines the final classification. Lower gates are not evaluated once a higher gate has been triggered. Gates are **irreversible**: a Prohibited Practice at Gate 01 ends the assessment immediately, and no later score can override a legal violation.

This sequential structure mirrors the architecture of the AI Act itself: prohibitions (Article 5) supersede high-risk classification, which supersedes transparency, which supersedes baseline GPAI obligations.

---

## 2. The 6 Gates

### Gate 01 — Article 5 — Prohibited Practices → PROHIBITED

If any practice falls under Article 5 (subliminal manipulation, social scoring, real-time remote biometric identification in public spaces, exploitation of vulnerabilities, untargeted scraping of facial images, emotion recognition in workplace or education, biometric categorisation of sensitive attributes), the assessment stops immediately. No score is assigned. The system cannot be deployed legally in the European Union.

**Examples**:
- Emotion recognition in workplaces without explicit consent
- Real-time facial recognition in public spaces outside narrow exceptions
- Untargeted scraping of facial images from the internet or CCTV (Art. 5§1(e))
- AI that manipulates users through subliminal techniques

### Gate 02 — Article 6(1) — Safety Component of a Regulated Product → HIGH RISK

AI systems that are safety components of products covered by Union harmonisation legislation (Annex I), including machinery, medical devices, civil aviation, motor vehicles, marine equipment, and which must undergo third-party conformity assessment.

**Medical AI fast-track**: if the AI system is a medical device under MDR Class IIa or above, it is automatically classified as high-risk under AI Act Art. 6(1). No further classification analysis is required; the MDR class determines the AI Act exposure.

**Examples**:
- AI in medical diagnostic devices (MDR / IVDR)
- AI in automotive safety systems
- AI in civil aviation control systems

### Gate 03 — Article 6(2) + Annex III — High-Risk Sector → HIGH RISK

AI systems listed in Annex III across eight domains. This is where most enterprise AI systems are classified. The Article 6(3) exception (narrow procedural task, no significant harm) may apply but requires documented justification.

**Examples**:
- CV screening and recruitment tools
- Credit scoring and insurance pricing
- Student assessment and academic evaluation

### Gate 04 — Article 51 + 55 — GPAI with Systemic Risk → HIGH RISK

General Purpose AI models trained with more than 10²⁵ FLOPs are classified as systemic risk models. Additional obligations apply: adversarial testing, incident reporting without undue delay (Art. 55(1)(c)), cybersecurity measures, energy consumption reporting.

**Examples**:
- GPT-4, Claude 3 Opus, Gemini Ultra
- Llama 3 405B and equivalent scale models
- Custom-trained foundation models exceeding the compute threshold

### Gate 05 — Article 50 — Transparency Obligations → LIMITED RISK

AI systems that interact with humans or generate content must disclose their AI nature. Chatbots must identify themselves at the start of each interaction. AI-generated synthetic media must be labelled.

**Examples**:
- Customer service chatbots
- AI writing assistants
- Synthetic media and deepfake generation

### Gate 06 — Article 53 — GPAI Standard Obligations → LIMITED RISK

GPAI model providers (not systemic risk) must maintain technical documentation, publish training data summaries, comply with EU copyright law, and provide downstream providers with necessary compliance information.

**Examples**:
- Open-source foundation models below 10²⁵ FLOPs
- Specialised language models for specific domains
- Multimodal models used in downstream products

---

## 3. Scoring legend (Full Report)

| Score band | Classification | Note |
|---|---|---|
| 85/100 | High Risk (Safety Component) | Full Art. 9-15 obligations. Third-party conformity assessment required. |
| 75–90/100 | High Risk (Annex III) | Full Art. 9-15 obligations. Registration in EU database required. Score is domain-weighted (Art. 6(2)). |
| 35/100 | Limited Risk (GPAI / Transparency) | Art. 50 or Art. 53 obligations. Disclosure requirements apply. |
| 10/100 | Minimal Risk | No mandatory obligations beyond Art. 4 AI literacy. Voluntary code of conduct recommended. |

---

## 4. Interpretation engine

The EU AI Act requires contextual interpretation. Article 5 prohibited practices are clear for some cases, ambiguous for others. Article 6 high-risk classification depends on context of use, not just on technology. Article 51 GPAI systemic risk thresholds are still being operationalised by the AI Office.

Sprinkling Act does not resolve ambiguity. It **flags ambiguity explicitly** and recommends legal counsel for edge cases.

Sprinkling Act is an operational tool, not a legal opinion. It produces the structured, article-mapped artefact your lawyer, regulator, or investor needs as a starting point. It names the boundary a classification triggers: Art. 9-15 (including the Art. 15 accuracy and robustness burden), Annex IV technical documentation, and Art. 72 post-market monitoring. It does not produce those artefacts; substantive demonstration is the responsibility of the downstream chain (your lawyer, auditor, or notified body). We delimit the obligations; we do not discharge them.

---

## 5. Cross-references to international standards

### NIST AI RMF 1.0 (NIST AI 100-1, 2023)

The four NIST functions (Govern, Map, Measure, Manage) mirror the lifecycle approach embedded in the gates. Gate evaluation (Map), scoring with obligations (Measure), and ongoing regulatory monitoring (Manage) follow the same iterative logic. The Sprinkling Act methodology addresses the Map and Measure functions; operational Govern and Manage remain the responsibility of the assessed organisation.

### ISO/IEC 42001:2023 — AI Management Systems

ISO 42001 requires organisations to establish risk assessment processes (Clause 6), operational controls (Clause 8), and performance evaluation (Clause 9). The 6-gate assessment produces the risk classification and obligation mapping that feeds into an ISO 42001-compliant AI Management System. The assessment does not replace an AIMS. It provides the regulatory input that an AIMS requires.

---

## 6. Version history

### v1.3 — May 2026

Post-Digital Omnibus alignment (provisional trilogue agreement of 7 May 2026, subject to formal adoption by the co-legislators).

- Annex III standalone high-risk binding date updated **2 August 2026 → 2 December 2027** (EP enumeration: biometrics, critical infrastructure, education, employment, law enforcement, border management; non-exhaustive).
- Annex I product-embedded safety components binding date updated **2 August 2027 → 2 August 2028**.
- Article 50 transparency unchanged (**2 August 2026 baseline preserved**).
- GenAI watermarking advanced **2 February 2027 → 2 December 2026**.
- Safety-component definition narrowed: AI functions that only assist users or optimise performance no longer automatically face high-risk obligations, if their failure or malfunction does not create health or safety risks.
- Art. 5§1(i) added (provisional, applicable 2 December 2026 pending formal adoption): prohibition of AI systems generating CSAM/NCII content, three-branch architecture (designed-for / placed-without-safeguards / deployer-use).
- Art. 50§1-§4 obligations enriched with explicit application timeline (2 August 2026 new systems · 2 December 2026 transitional for §2 watermarking + §4 deepfake disclosure on systems already on EU market).
- Sleeper segments mapped: PWD × §4 employment platforms, CRA × AI Act IoT-AI.

### v1.2 — April 2026

Initial public release aligned with the original AI Act calendar (Regulation (EU) 2024/1689, Official Journal L of 12 July 2024).

---

## 7. Related Sprinkling Act publications (Zenodo)

| Publication | Date | DOI |
|---|---|---|
| EU AI Act Readiness Report | April 2026 | [10.5281/zenodo.19671328](https://doi.org/10.5281/zenodo.19671328) |
| Annex A — The Deployer Multiplier | May 2026 | [10.5281/zenodo.20042174](https://doi.org/10.5281/zenodo.20042174) |
| Discussion Paper — Third Structural Pole | May 2026 | [10.5281/zenodo.20343243](https://doi.org/10.5281/zenodo.20343243) |

OpenTimestamps cryptographic proofs for the above PDFs: [sprinkling-act/timestamps](https://github.com/sprinkling-act/timestamps).

---

## 8. What this repository is NOT

- Not a software library to assess your AI system automatically. It is a **documented framework** that humans (and downstream tools) can apply.
- Not a legal opinion. It is a classification artefact, not an interpretation of the law.
- Not affiliated with any AI vendor, regulator, or certification body. Sprinkling Act is a private independent assessment authority registered in Belgium (BCE BE 1034.962.482), not a notified body within the meaning of Regulation (EU) 2024/1689.

For the full position statement, see [sprinklingact.com/clarity](https://sprinklingact.com/clarity).

---

## 9. License

This methodology framework is released under the **MIT License**. You are free to reproduce, adapt, and apply it, subject to attribution.

If you build a tool or service on top of this framework, attribution to Sprinkling Act (Brussels, Belgium · BCE BE 1034.962.482) is required.

---

## 10. Contributing

This repository is currently maintained by Sprinkling Act (Lamar B. Shucrani, Founder, ORCID [0009-0002-5093-8550](https://orcid.org/0009-0002-5093-8550)).

For substantive issues (regulatory interpretation, post-Omnibus updates, gate logic edge cases), please open a GitHub Issue with a precise statement of the concern and any supporting reference.

For typos, formatting, or non-substantive corrections, pull requests are welcome.

---

*Maintained by Sprinkling Act · Brussels, Belgium · [sprinklingact.com](https://sprinklingact.com)*
