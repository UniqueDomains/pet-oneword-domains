# Available .PET One-Word Domains (11,668)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C668%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .pet one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,668 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,668 domains · **Median ask:** $60.76 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-09  
**Canonical page:** `https://unique.domains/domains/tld/pet`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/pet?utm_source=github&utm_medium=referral&utm_campaign=repo_pet_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./pet.csv">CSV</a> / <a href="./pet.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_pet_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_pet_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .PET search](https://unique.domains/domains/tld/pet?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_pet_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .PET search](https://unique.domains/domains/tld/pet?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_pet_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_pet_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .PET one-word domain catalog.

### Files

- `pet.csv` — public CSV extract (1,000 rows)
- `pet.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/pet-oneword-domains/main/pet.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| shortcuts.pet    | available | $19.99    | —             | 48             | 41     | 10     | name.com         |
| coins.pet        | resell    | —         | —             | 56             | 41     | 5      | Dynadot Inc      |
| regions.pet      | premium   | $1,250    | —             | 64             | 59     | 7      | name.com         |
| prompts.pet      | available | $19.99    | —             | 54             | 39     | 7      | name.com         |
| tips.pet         | resell    | —         | —             | 80             | 26     | 4      | GoDaddy.com, LLC |
| Books.pet        | premium   | $3,500    | $3,500        | 52             | 49     | 5      | namecheap        |
| trends.pet       | available | $19.99    | —             | 60             | 32     | 6      | name.com         |
| registration.pet | resell    | —         | —             | 75             | 19     | 12     | IONOS SE         |
| photos.pet       | premium   | $3,125    | —             | 54             | 28     | 6      | name.com         |
| William.pet      | available | $35.98    | —             | 74             | 31     | 7      | namecheap        |
| sites.pet        | premium   | $1,250    | —             | 53             | 26     | 5      | name.com         |
| popup.pet        | available | $19.99    | —             | 84             | 29     | 6      | name.com         |
| blogs.pet        | premium   | $1,107    | $1,107        | 52             | 21     | 5      | namesilo         |
| quotes.pet       | available | $19.99    | —             | 58             | 29     | 6      | name.com         |
| pictures.pet     | premium   | $3,125    | —             | 82             | 17     | 8      | name.com         |
| systems.pet      | available | $19.99    | —             | 46             | 27     | 7      | name.com         |
| states.pet       | premium   | $1,250    | —             | 70             | 16     | 6      | name.com         |
| Keith.pet        | available | $35.98    | —             | 66             | 25     | 5      | namecheap        |
| shows.pet        | premium   | $1,250    | —             | 66             | 16     | 5      | name.com         |
| veterans.pet     | available | $19.99    | —             | 56             | 23     | 8      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,668 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/pet?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_pet_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/pet?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_pet_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_pet_oneword_domains&utm_content=related_pricing)

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

This selection is entirely .pet domains, which makes the naming signal explicit from the extension itself. The set ranges from short words like ace.pet and room.pet to longer or more literal terms like hockeyplayer.pet and definition.pet. That creates a wide spread in memorability, flexibility, and likely buyer appeal. For founders, the strongest options are usually concise, easy to say, and broad enough to fit a pet brand without boxing it in. For investors, quality tends to concentrate in short dictionary words with clean spelling and straightforward commercial use. Median ask is 60.76, so the first screen is whether the word quality justifies the price and any ongoing renewal commitment.

- Short .pet names tend to be easier to remember and compare
- Check whether the word fits pets naturally or feels forced
- Avoid obvious trademark terms unless rights are clearly clean
- Use median ask 60.76 as a baseline for value judgment

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PET One-Word Domains*. Version 2026-05-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PET page](https://unique.domains/domains/tld/pet?utm_source=github&utm_medium=referral&utm_campaign=repo_pet_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_pet_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_pet_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_pet_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
