# Available .FISH One-Word Domains (11,982)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C982%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .fish one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,982 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,982 domains · **Median ask:** $26.50 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-27  
**Canonical page:** `https://unique.domains/domains/tld/fish`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/fish?utm_source=github&utm_medium=referral&utm_campaign=repo_fish_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./fish.csv">CSV</a> / <a href="./fish.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fish_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fish_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .FISH search](https://unique.domains/domains/tld/fish?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fish_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .FISH search](https://unique.domains/domains/tld/fish?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fish_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fish_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .FISH one-word domain catalog.

### Files

- `fish.csv` — public CSV extract (1,000 rows)
- `fish.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/fish-oneword-domains/main/fish.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| shortcuts.fish   | available | $19.99    | —             | 48             | 41     | 10     | name.com         |
| tuna.fish        | resell    | —         | —             | 74             | 3      | 9      | GoDaddy.com, LLC |
| cars.fish        | premium   | $82.50    | —             | 66             | 47     | 4      | name.com         |
| tokens.fish      | available | $19.99    | —             | 51             | 36     | 6      | name.com         |
| events.fish      | premium   | $123.75   | —             | 68             | 37     | 6      | name.com         |
| teams.fish       | available | $19.99    | —             | 62             | 32     | 5      | name.com         |
| partners.fish    | premium   | $123.75   | —             | 61             | 31     | 8      | name.com         |
| spaces.fish      | available | $19.99    | —             | 54             | 30     | 6      | name.com         |
| letsgo.fish      | premium   | $1,000    | —             | 57             | 31     | 7      | name.com         |
| inspiration.fish | available | $19.99    | —             | 88             | 27     | 11     | name.com         |
| photos.fish      | premium   | $123.75   | —             | 54             | 28     | 6      | name.com         |
| doctors.fish     | available | $19.99    | —             | 56             | 26     | 7      | name.com         |
| systems.fish     | premium   | $82.50    | —             | 46             | 27     | 7      | name.com         |
| pops.fish        | available | $19.99    | —             | 74             | 24     | 4      | name.com         |
| loans.fish       | premium   | $118.80   | $118.80       | 58             | 24     | 5      | namesilo         |
| reports.fish     | available | $19.99    | —             | 58             | 24     | 7      | name.com         |
| coupons.fish     | premium   | $242      | $242          | 52             | 24     | 7      | namesilo         |
| echoes.fish      | available | $19.99    | —             | 56             | 24     | 6      | name.com         |
| watches.fish     | premium   | $82.50    | —             | 84             | 19     | 7      | name.com         |
| rekt.fish        | available | $19.99    | —             | 40             | 24     | 4      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,982 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/fish?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fish_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/fish?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fish_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fish_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .fish domains. The set ranges from broad dictionary words like yard.fish and news.fish to more expressive choices like profound.fish and hotshot.fish. For founders, the main question is whether the word is strong enough to offset the narrower recognition of .fish. For investors, the key check is whether the ask leaves room for resale despite limited mainstream liquidity. With a median ask of 26.50, price is accessible, but extension fit matters more than raw cost. Favor words that are easy to say, easy to recall, and clearly matched to fishing, seafood, aquatic content, or a deliberate brand angle.

- Prioritize simple words with clear meaning and recall
- Check whether the word fits .fish naturally or awkwardly
- Low ask can help, but niche TLD risk still matters
- Avoid words that may invite trademark conflicts

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FISH One-Word Domains*. Version 2026-05-27. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FISH page](https://unique.domains/domains/tld/fish?utm_source=github&utm_medium=referral&utm_campaign=repo_fish_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fish_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fish_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fish_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
