# Available .AT One-Word Domains (76,148)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-76%2C148%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .at one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **76,148 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 76,148 domains · **Median ask:** $13.84 · **High-demand under $2,500:** 19

**Last updated:** 2026-08-14
**Canonical page:** `https://unique.domains/domains/tld/at`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/at?utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./at.csv">CSV</a> / <a href="./at.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .AT search](https://unique.domains/domains/tld/at?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .AT search](https://unique.domains/domains/tld/at?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .AT one-word domain catalog.

### Files

- `at.csv`, public CSV extract (1,000 rows)
- `at.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/at-oneword-domains/main/at.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| --------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| psych.at  | available | —         | —             | high           | high   | 5      | —                                                         |
| agog.at   | available | $18.99    | $18.99        | medium         | low    | 4      | name.com                                                  |
| why.at    | resell    | —         | —             | high           | high   | 3      | Internet Service Fuchs KG ( https://nic.at/registrar/20 ) |
| drawn.at  | available | $18.99    | $18.99        | medium         | low    | 5      | name.com                                                  |
| hurt.at   | resell    | —         | —             | medium         | low    | 4      | EWBCD GmbH ( https://nic.at/registrar/750 )               |
| lower.at  | available | $18.99    | —             | medium         | low    | 5      | name.com                                                  |
| rice.at   | resell    | —         | —             | high           | low    | 4      | Dynadot INC ( https://nic.at/registrar/650 )              |
| swell.at  | available | $11.99    | $11.99        | medium         | low    | 5      | namesilo                                                  |
| belly.at  | resell    | —         | —             | high           | high   | 5      | Dynadot INC ( https://nic.at/registrar/650 )              |
| became.at | available | $11.99    | $11.99        | medium         | low    | 6      | namesilo                                                  |
| fatal.at  | resell    | —         | —             | high           | low    | 5      | RegistryGate GmbH ( https://nic.at/registrar/228 )        |
| boiled.at | available | $11.99    | $11.99        | medium         | low    | 6      | namesilo                                                  |
| Foods.at  | resell    | —         | —             | medium         | high   | 5      | InterNexum GmbH ( https://nic.at/registrar/659 )          |
| bowing.at | available | $11.99    | $11.99        | medium         | medium | 6      | namesilo                                                  |
| filmed.at | resell    | —         | —             | medium         | high   | 6      | EWBCD GmbH ( https://nic.at/registrar/750 )               |
| choppy.at | available | $18.99    | $18.99        | medium         | low    | 6      | name.com                                                  |
| retire.at | resell    | —         | —             | high           | low    | 6      | EWBCD GmbH ( https://nic.at/registrar/750 )               |
| forget.at | available | $11.99    | $11.99        | medium         | low    | 6      | namesilo                                                  |
| window.at | resell    | —         | —             | high           | low    | 6      | Domainers Registrar AG ( https://nic.at/registrar/668 )   |
| myson.at  | available | $11.99    | $11.99        | high           | low    | 6      | namesilo                                                  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 76,148 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 19 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/at?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/at?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list covers one-word .at domains that are currently available, spanning short, everyday words like out.at, half.at, and beauty.at. With 74,023 names and a median ask near $14, the selection skews toward accessible pricing while still including higher-demand names worth closer evaluation.

- 74,023 available one-word .at domains, updated daily
- Median ask around $14 across the full set
- Most names fall in the high-demand (70-84) bucket
- Real examples: transparency.at, christmas.at, sorry.at

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .AT One-Word Domains*. Version 2026-08-14. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .AT page](https://unique.domains/domains/tld/at?utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
