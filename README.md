# Vorp Labs Research Datasets

Versioned, source-backed datasets maintained by Vorp Labs Research and published by Vorp Labs.

Every release includes JSON and CSV files, a manifest, record counts, and SHA-256 checksums. The canonical pages explain scope, methodology, source selection, caveats, and update cadence.

## Latest releases

| Dataset | Version | As of | Records | Canonical page |
|---|---:|---:|---:|---|
| Vorp Labs — Security Framework Change Dataset | 2026.07.15 | 2026-07-15 | 18 | [Source](https://vorplabs.com/security-framework-changes) |
| Vorp Labs — E-Invoicing Mandate Phase Dataset | 2026.07.15 | 2026-07-15 | 15 | [Source](https://vorplabs.com/e-invoicing-mandates) |
| Vorp Labs — US Federal AI Enforcement Tracker | 2026.07.10 | 2026-07-10 | 30 | [Source](https://vorplabs.com/ai-regulatory-updates/federal-enforcement) |
| Vorp Labs — AI Scam & Fraud Tracker | 2026.07.10 | 2026-07-10 | 12 | [Source](https://vorplabs.com/ai-threat-monitoring) |
| Vorp Labs — AI Company Security Incident Ledger | 2026.07.10 | 2026-07-10 | 19 | [Source](https://vorplabs.com/ai-threat-monitoring/security-incidents) |
| Vorp Labs — Deepfake & AI Impersonation Law Tracker | 2026.07.10 | 2026-07-10 | 46 | [Source](https://vorplabs.com/ai-regulatory-updates/deepfake-laws) |
| Vorp Labs — AI Model Deprecation Tracker | 2026.07.15 | 2026-07-15 | 48 | [Source](https://vorplabs.com/models/deprecations) |
| Vorp Labs — Frontier AI Safety Framework Comparison Dataset | 2026.07.12 | 2026-07-12 | 12 | [Source](https://vorplabs.com/ai-regulatory-updates/frontier-ai-framework-comparison) |
| Vorp Labs — US AI Law Change Dataset | 2026.07.12 | 2026-07-12 | 10 | [Source](https://vorplabs.com/ai-regulatory-updates/us-ai-law-change-dataset) |
| Vorp Labs — AI Media Rights, Consent & Provenance Registry | 2026.07.15 | 2026-07-15 | 15 | [Source](https://vorplabs.com/models/media-rights) |

## Citation and attribution

Use the citation in each dataset's manifest.json. In prose, keep the source attached to the finding—for example: “According to Vorp Labs' tracker…”—and link to the canonical dataset page.

The organization-level citation metadata is in [CITATION.cff](CITATION.cff). Dataset files and repository documentation are released under [CC BY 4.0](LICENSE.md).

## Repository layout

- datasets/index.json: catalog of all ten datasets.
- datasets/&lt;dataset&gt;/manifest.json: release history and checksums.
- datasets/&lt;dataset&gt;/&lt;version&gt;/: immutable JSON and CSV snapshots.
- CORRECTIONS.md: how to report a data correction.
- SECURITY.md: how to report a security concern without posting it publicly.

## Verification

Before citing a record, check its lastChecked or asOf date and follow the primary-source URL. These datasets are descriptive research, not legal, financial, or procurement advice.
