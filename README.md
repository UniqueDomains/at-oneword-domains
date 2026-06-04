# Available .AT One-Word Domains (73,825)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-73%2C825%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .at one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **73,825 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 73,825 domains · **Median ask:** $14.56 · **High-demand under $2,500:** 0

**Last updated:** 2026-06-04  
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

- `at.csv` — public CSV extract (1,000 rows)
- `at.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/at-oneword-domains/main/at.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                     |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------------------- |
| oakland.at    | available | $18.99    | —             | 66             | 20     | 7      | name.com                                                      |
| Foods.at      | resell    | —         | —             | 56             | 92     | 5      | InterNexum GmbH ( https://nic.at/registrar/659 )              |
| humble.at     | premium   | —         | —             | 70             | 98     | 6      | —                                                             |
| protocols.at  | available | $11.99    | $11.99        | —              | 17     | 9      | namesilo                                                      |
| why.at        | resell    | —         | —             | 118            | 84     | 3      | Internet Service Fuchs KG ( https://nic.at/registrar/20 )     |
| brazil.at     | premium   | —         | —             | 66             | 96     | 6      | —                                                             |
| boxoffice.at  | available | $18.99    | —             | 74             | 14     | 10     | name.com                                                      |
| resident.at   | resell    | —         | —             | 76             | 84     | 8      | Realtime Register B.V. ( https://nic.at/registrar/423 )       |
| authority.at  | premium   | —         | —             | 60             | 96     | 9      | —                                                             |
| lower.at      | available | $18.99    | —             | 64             | 14     | 5      | name.com                                                      |
| creditcard.at | resell    | —         | —             | 68             | 80     | 11     | InterNetX GmbH ( https://nic.at/registrar/80 )                |
| trademark.at  | premium   | —         | —             | 104            | 92     | 9      | —                                                             |
| curtain.at    | available | $18.99    | —             | 92             | 12     | 7      | name.com                                                      |
| filmed.at     | resell    | —         | —             | 66             | 80     | 6      | EWBCD GmbH ( https://nic.at/registrar/750 )                   |
| saudi.at      | premium   | —         | —             | 94             | 92     | 5      | —                                                             |
| addition.at   | available | $11.99    | $11.99        | 70             | 11     | 8      | namesilo                                                      |
| SaintLucia.at | resell    | —         | —             | —              | 80     | 11     | DomainQuadrat Marketing GmbH ( https://nic.at/registrar/581 ) |
| Xanadu.at     | premium   | —         | —             | 74             | 92     | 6      | —                                                             |
| forget.at     | available | $11.99    | $11.99        | 54             | 10     | 6      | namesilo                                                      |
| belly.at      | resell    | —         | —             | 88             | 76     | 5      | Dynadot INC ( https://nic.at/registrar/650 )                  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 73,825 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/at?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/at?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is defined by one constraint: the domains use the .at extension. The result is a broad set of single-word .at names ranging from dictionary-style terms such as answer.at and concentrate.at to more expressive options like boogaloo.at and shinny.at. For founders, the main question is whether a name is clear, memorable, and easy to defend as a brand. For investors, the focus is whether the ask leaves room for resale and whether the word has broad commercial use. With a median ask of 18.44 across 73,826 domains, pricing starts as a useful filter, but the stronger differentiator is word quality.

- Favor words that are easy to say, spell, and recall
- Check whether the ask fits the word's commercial breadth
- Prefer terms with clear meaning over awkward variations
- Review trademark exposure before treating a name as ownable

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .AT One-Word Domains*. Version 2026-06-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .AT page](https://unique.domains/domains/tld/at?utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_at_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
