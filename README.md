# Available .VODKA One-Word Domains (12,737)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C737%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .vodka one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,737 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,737 domains · **Median ask:** $57.49 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-13  
**Canonical page:** `https://unique.domains/domains/tld/vodka`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/vodka?utm_source=github&utm_medium=referral&utm_campaign=repo_vodka_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./vodka.csv">CSV</a> / <a href="./vodka.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_vodka_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vodka_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .VODKA search](https://unique.domains/domains/tld/vodka?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_vodka_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .VODKA search](https://unique.domains/domains/tld/vodka?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_vodka_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vodka_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .VODKA one-word domain catalog.

### Files

- `vodka.csv` — public CSV extract (1,000 rows)
- `vodka.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/vodka-oneword-domains/main/vodka.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| travelers.vodka     | available | $32.49    | $32.49        | 58             | 61     | 9      | namesilo  |
| toomuch.vodka       | resell    | —         | —             | 78             | 11     | 8      | eNom, LLC |
| justin.vodka        | premium   | $100      | —             | 58             | 38     | 7      | name.com  |
| farmers.vodka       | available | $43.98    | —             | 54             | 59     | 7      | namecheap |
| Cats.vodka          | premium   | $56       | $35           | 59             | 33     | 4      | namecheap |
| keepthechange.vodka | available | $43.98    | —             | 46             | 59     | 15     | namecheap |
| Jim.vodka           | premium   | $56       | $35           | 78             | 28     | 3      | namecheap |
| skills.vodka        | available | $43.98    | —             | 58             | 47     | 6      | namecheap |
| trades.vodka        | premium   | $500      | —             | 71             | 26     | 6      | name.com  |
| lets.vodka          | available | $43.98    | —             | 77             | 39     | 4      | namecheap |
| sites.vodka         | premium   | $500      | —             | 53             | 26     | 5      | name.com  |
| events.vodka        | available | $43.98    | —             | 68             | 37     | 6      | namecheap |
| Keith.vodka         | premium   | $56       | $35           | 66             | 25     | 5      | namecheap |
| aliens.vodka        | available | $32.49    | $32.49        | 56             | 35     | 6      | namesilo  |
| VHS.vodka           | premium   | $56       | $35           | 71             | 20     | 3      | namecheap |
| etc.vodka           | available | $43.98    | —             | 58             | 34     | 3      | namecheap |
| travels.vodka       | premium   | $96       | $29.50        | 64             | 18     | 7      | namesilo  |
| teams.vodka         | available | $43.98    | —             | 62             | 32     | 5      | namecheap |
| ladies.vodka        | premium   | $500      | —             | 80             | 17     | 6      | name.com  |
| trends.vodka        | available | $43.98    | —             | 60             | 32     | 6      | namecheap |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,737 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/vodka?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_vodka_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/vodka?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_vodka_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vodka_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .vodka domains. The set ranges from concise, brandable words like veer.vodka and ribbon.vodka to more abstract or heavier terms such as complicate.vodka, atheist.vodka, and headoverheels.vodka. With 12,735 domains in the selection and a median ask of 57.49, the main task is filtering for commercial fit rather than chasing rare supply. Founders should favor names that are easy to say, remember, and defend as a brand. Investors should focus on names with cleaner resale narratives, broad use cases, and renewal economics that do not erode the entry price advantage of this extension.

- Prefer words that sound clean and distinct with .vodka
- Use median ask 57.49 as a baseline for value checks
- Watch for awkward meanings or narrow commercial appeal
- Check renewal cost before treating a low ask as a deal

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .VODKA One-Word Domains*. Version 2026-05-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .VODKA page](https://unique.domains/domains/tld/vodka?utm_source=github&utm_medium=referral&utm_campaign=repo_vodka_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_vodka_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vodka_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vodka_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
