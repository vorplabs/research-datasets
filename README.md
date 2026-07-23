# Vorp Labs Research Datasets

Versioned, source-backed datasets maintained by Vorp Labs Research and published by Vorp Labs.

Every immutable release includes JSON and CSV files. Its manifest records the version, as-of date, record count, byte count, and SHA-256 checksum. The canonical Vorp page remains the source of truth for scope, methodology, caveats, corrections, and update cadence.

## Latest releases

| Dataset | Version | As of | Records | Source |
|---|---:|---:|---:|---|
| Government AI Readiness Tracker | 2026.07.21 | 2026-07-20 | 8 | [Canonical page](https://vorplabs.com/ai-regulatory-updates/government-ai-readiness) |
| US state and European government AI readiness comparison | 2026.07.21 | 2026-07-20 | 20 | [Canonical page](https://vorplabs.com/ai-regulatory-updates/government-ai-readiness/us-eu-comparison) |
| Security Framework Change Dataset | 2026.07.17 | 2026-07-15 | 18 | [Canonical page](https://vorplabs.com/security-framework-changes) |
| E-Invoicing Mandate Phase Dataset | 2026.07.17 | 2026-07-15 | 15 | [Canonical page](https://vorplabs.com/e-invoicing-mandates) |
| US Federal AI Enforcement Tracker | 2026.07.19 | 2026-07-18 | 42 | [Canonical page](https://vorplabs.com/ai-regulatory-updates/federal-enforcement) |
| AI Hallucination Court Sanctions Tracker | 2026.07.20 | 2026-07-19 | 10 | [Canonical page](https://vorplabs.com/ai-regulatory-updates/ai-hallucination-sanctions) |
| US State AG AI Enforcement Tracker | 2026.07.19 | 2026-07-18 | 9 | [Canonical page](https://vorplabs.com/ai-regulatory-updates/state-ag-enforcement) |
| AI Scam & Fraud Tracker | 2026.07.17 | 2026-07-10 | 12 | [Canonical page](https://vorplabs.com/ai-threat-monitoring) |
| AI Company Security Incident Ledger | 2026.07.17 | 2026-07-10 | 19 | [Canonical page](https://vorplabs.com/ai-threat-monitoring/security-incidents) |
| Deepfake & AI Impersonation Law Tracker | 2026.07.23 | 2026-07-22 | 44 | [Canonical page](https://vorplabs.com/ai-regulatory-updates/deepfake-laws) |
| AI Model Deprecation Tracker | 2026.07.17 | 2026-07-15 | 48 | [Canonical page](https://vorplabs.com/models/deprecations) |
| Frontier AI Safety Framework Comparison Dataset | 2026.07.17 | 2026-07-12 | 12 | [Canonical page](https://vorplabs.com/ai-regulatory-updates/frontier-ai-framework-comparison) |
| US AI Law Change Dataset | 2026.07.18 | 2026-07-17 | 12 | [Canonical page](https://vorplabs.com/ai-regulatory-updates/us-ai-law-change-dataset) |
| AI Media Rights, Consent & Provenance Registry | 2026.07.17 | 2026-07-15 | 15 | [Canonical page](https://vorplabs.com/models/media-rights) |
| US Public-Sector AI Procurement Clause and Policy Inventory | 2026.07.21 | 2026-07-21 | 20 | [Canonical page](https://vorplabs.com/ai-regulatory-updates/us-ai-procurement) |
| AI Agent Liability, Insurance, and Attestation Tracker | 2026.07.21 | 2026-07-21 | 28 | [Canonical page](https://vorplabs.com/ai-agent-liability) |
| AI Insurance Exclusions Evidence Ledger | 2026.07.22 | 2026-07-22 | 12 | [Canonical page](https://vorplabs.com/ai-insurance-exclusions) |

## Citation and attribution

Use the citation in each dataset manifest and preserve the release version or as-of date. In prose, credit Vorp Labs Research and link to the canonical dataset page.

Organization-level citation metadata is in [CITATION.cff](CITATION.cff). Dataset files and original repository documentation are released under [CC BY 4.0](LICENSE.md).

## Repository layout

- `datasets/index.json`: catalog of all 17 datasets.
- `datasets/<dataset>/manifest.json`: release history, citations, and checksums.
- `datasets/<dataset>/<version>/`: immutable JSON and CSV snapshots.
- `PUBLICATION-MANIFEST.json`: checksums for the complete generated mirror.
- `CORRECTIONS.md`: source-backed correction process.

## Verification

Before relying on a record, check its source URL and last-checked or as-of date. These datasets are descriptive research, not legal, financial, or procurement advice.
