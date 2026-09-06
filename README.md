# Available .ARCHI One-Word Domains (20,686)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-20%2C686%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .archi one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **20,686 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 20,686 domains · **Median ask:** $21.48 · **High-demand under $2,500:** 3

**Last updated:** 2026-09-06
**Canonical page:** `https://unique.domains/domains/tld/archi`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/archi?utm_source=github&utm_medium=referral&utm_campaign=repo_archi_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./archi.csv">CSV</a> / <a href="./archi.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_archi_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_archi_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .ARCHI search](https://unique.domains/domains/tld/archi?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_archi_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .ARCHI search](https://unique.domains/domains/tld/archi?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_archi_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_archi_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .ARCHI one-word domain catalog.

### Files

- `archi.csv`, public CSV extract (1,000 rows)
- `archi.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/archi-oneword-domains/main/archi.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| out.archi         | available | $24.99    | —             | high           | low    | 3      | name.com        |
| off.archi         | available | $24.99    | —             | high           | low    | 3      | name.com        |
| add.archi         | available | $24.99    | —             | high           | low    | 3      | name.com        |
| marketplace.archi | resell    | —         | —             | high           | medium | 11     | NameCheap, Inc. |
| flat.archi        | premium   | $123.75   | $123.75       | high           | low    | 4      | name.com        |
| BJP.archi         | available | $24.99    | —             | medium         | low    | 3      | name.com        |
| roman.archi       | premium   | $118.80   | $118.80       | high           | low    | 5      | namesilo        |
| bum.archi         | available | $14.98    | $132.98       | low            | low    | 3      | namecheap       |
| center.archi      | premium   | $118.80   | $118.80       | high           | low    | 6      | namesilo        |
| clv.archi         | available | $14.98    | $132.98       | low            | low    | 3      | namecheap       |
| baroque.archi     | premium   | $118.80   | $118.80       | medium         | low    | 7      | namesilo        |
| cot.archi         | available | $24.99    | —             | high           | low    | 3      | name.com        |
| kingdom.archi     | premium   | $1,875    | —             | high           | low    | 7      | name.com        |
| cup.archi         | available | $14.98    | $132.98       | medium         | low    | 3      | namecheap       |
| dad.archi         | available | $24.99    | —             | high           | low    | 3      | name.com        |
| day.archi         | available | $24.99    | —             | high           | low    | 3      | name.com        |
| dye.archi         | available | $24.99    | —             | medium         | low    | 3      | name.com        |
| eye.archi         | available | $24.99    | —             | medium         | low    | 3      | name.com        |
| fee.archi         | available | $24.99    | —             | high           | low    | 3      | name.com        |
| fog.archi         | available | $24.99    | —             | high           | low    | 3      | name.com        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 20,686 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 3 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/archi?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_archi_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/archi?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_archi_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_archi_oneword_domains&utm_content=related_pricing)

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

This list of one-word .archi domains includes 12,575 names, with 12,507 currently available and a small number in premium or resell status. Median ask sits at $26.39, and the vast majority price under $500, making this a low-cost entry point for architecture-themed one-word domains. Demand skews low across most of the set, with only 14 names reaching high or top-tier demand tiers.

- 12,575 one-word .archi domains, 12,507 available now
- Median ask $26.39; 11,466 domains priced under $500
- 9,648 domains carry a modern naming style
- 658 domains flagged launch-ready for immediate use

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ARCHI One-Word Domains*. Version 2026-09-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ARCHI page](https://unique.domains/domains/tld/archi?utm_source=github&utm_medium=referral&utm_campaign=repo_archi_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_archi_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_archi_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_archi_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
