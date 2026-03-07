<div align="center">

<img src="./certprep-logo.svg" alt="CertPrep" width="160"/>

# CertPrep

**Learn. Build. Certify.**

Open-source certification prep labs for GitHub, cloud & DevOps exams —
structured by domain weight, built for engineers who learn by doing.

[![GitHub followers](https://img.shields.io/github/followers/certprep?style=flat&color=f97316&labelColor=0f172a)](https://github.com/certprep)
[![License: MIT](https://img.shields.io/badge/License-MIT-f97316?style=flat&labelColor=0f172a)](https://github.com/certprep/.github/blob/main/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-f97316?style=flat&labelColor=0f172a)](https://github.com/certprep/.github/blob/main/CONTRIBUTING.md)

</div>

---

## What is CertPrep?

CertPrep is a community-driven collection of certification prep repositories.
Each repo maps to a specific exam and contains:

- **Domain-weighted study notes** — proportional depth to exam weighting
- **Hands-on demo labs** — step-by-step exercises with real CLI/API commands
- **Practice questions** — collapsible answers with explanation of *why*
- **Quick-reference cheat sheets** — printable, exam-day ready
- **Exam metadata** — objectives, glossary, domain weights, study time guides

No paywalls. No fluff. Just structured, open content.

---

## Certification Tracks

| Repo | Exam | Domain Focus | Status |
|------|------|-------------|--------|
| [GH_100_Cert_Prep](https://github.com/certprep/GH_100_Cert_Prep) | GH-100: GitHub Administration | Enterprise, Identity, Actions, Security | ✅ Available |
| [GH_500_Cert_Prep](https://github.com/certprep/GH_500_Cert_Prep) | GH-500: GitHub Advanced Security | Secret Scanning, Dependabot, CodeQL | ✅ Available |
| [AI-102_Cert_Prep](https://github.com/certprep/AI-102_Cert_Prep) | AI-102: Designing & Implementing Azure AI | Azure AI Services, NLP, Vision, Knowledge Mining | ✅ Available |

> More tracks coming. Have a cert you want covered? [Start a discussion →](https://github.com/orgs/certprep/discussions)

---

## How Content is Structured

Every CertPrep repo follows the same layout so you always know where to look:

```
├── README.md               # Exam overview, quick start, study plan
├── CONTRIBUTING.md         # Contribution guidelines
├── QUICK-REFERENCE.md      # Printable cheat sheet
├── exam-metadata/          # Objectives, domain weights, glossary
├── docs/                   # One deep-dive study doc per domain
├── demos/                  # Numbered hands-on lab sequences
└── scripts/                # Automation patterns and API utilities
```

---

## Study Philosophy

> **Domain weight = study time.**
> If a domain is 36% of the exam, it gets ~36% of the content depth.

All docs include:
- Conceptual explanations tied to official exam objectives
- Real CLI commands and API examples
- Common exam gotchas and misunderstandings
- Practice questions with collapsed answers (test yourself first)

---

## Contributing

CertPrep is open to contributions from anyone preparing for or who has passed these exams.

### What you can contribute

- **Found outdated content?** Open an issue in the relevant repo.
- **Want to add a practice question?** Follow the [question format](https://github.com/certprep/.github/blob/main/CONTRIBUTING.md#practice-question-format) and submit a PR.
- **Have a better explanation?** PRs for clarity improvements are always welcome.
- **Passed an exam and want to add a new track?** [Start a discussion →](https://github.com/orgs/certprep/discussions)

### Contribution workflow

1. **Fork** the repo you want to improve
2. **Create a branch**: `git checkout -b fix/brief-description`
3. **Make your changes** following the content standards
4. **Open a PR** with a clear description of what changed and why

All contribution standards — question format, markdown style, accuracy requirements, and more — are documented in [CONTRIBUTING.md](https://github.com/certprep/.github/blob/main/CONTRIBUTING.md).

---

## Content Freshness

All repos include a **Last Updated** date and the **exam version** they cover.
Certifications evolve — if you spot drift from the current objectives,
please flag it with a GitHub issue in the relevant repo.

---

<div align="center">

Built by practitioners, for practitioners.
Maintained by the community.

</div>
