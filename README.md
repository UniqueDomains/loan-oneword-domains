# Available .LOAN One-Word Domains (12,770)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C770%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .loan one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,770 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,770 domains · **Median ask:** $371.45 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
**Canonical page:** `https://unique.domains/domains/tld/loan`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/loan?utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./loan.csv">CSV</a> / <a href="./loan.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LOAN search](https://unique.domains/domains/tld/loan?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LOAN search](https://unique.domains/domains/tld/loan?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LOAN one-word domain catalog.

### Files

- `loan.csv` — public CSV extract (1,000 rows)
- `loan.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/loan-oneword-domains/main/loan.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar            |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------- |
| IsleofMan.loan   | available | $9.98     | —             | 62             | 91     | 11     | namecheap            |
| loans.loan       | resell    | —         | —             | 58             | 24     | 5      | Porkbun              |
| Chanel.loan      | premium   | $490      | $70           | 80             | 77     | 6      | namecheap            |
| prompts.loan     | available | $5.25     | $6.25         | 54             | 39     | 7      | namesilo             |
| rights.loan      | resell    | —         | —             | 50             | 19     | 6      | Dominet (HK) Limited |
| travelers.loan   | premium   | $437.50   | —             | 58             | 61     | 9      | name.com             |
| chem.loan        | available | $9.98     | —             | 74             | 24     | 4      | namecheap            |
| RedSox.loan      | premium   | $490      | $70           | 72             | 60     | 7      | namecheap            |
| whats.loan       | available | $5.25     | $6.25         | 58             | 24     | 5      | namesilo             |
| regions.loan     | premium   | $625      | —             | 64             | 59     | 7      | name.com             |
| products.loan    | available | $9.98     | —             | 60             | 23     | 8      | namecheap            |
| farmers.loan     | premium   | $6,250    | —             | 54             | 59     | 7      | name.com             |
| CapeCod.loan     | available | $9.98     | —             | 78             | 22     | 8      | namecheap            |
| Books.loan       | premium   | $7,000    | $140          | 52             | 49     | 5      | namecheap            |
| results.loan     | available | $9.98     | —             | 59             | 22     | 7      | namecheap            |
| jobs.loan        | premium   | $625      | —             | 79             | 42     | 4      | name.com             |
| restaurants.loan | available | $9.98     | —             | 57             | 21     | 11     | namecheap            |
| shortcuts.loan   | premium   | $437.50   | —             | 48             | 41     | 10     | name.com             |
| managed.loan     | available | $9.98     | —             | 58             | 20     | 7      | namecheap            |
| lets.loan        | premium   | $6,250    | —             | 77             | 39     | 4      | name.com             |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,770 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/loan?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/loan?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .loan domains. The extension gives immediate category relevance, but the word itself still determines whether a name feels credible, memorable, or too awkward for real lending use. Names like scene.loan, distance.loan, comic.loan, onboard.loan, and routine.loan show how varied this set is: some are broad and brandable, while others are indirect or harder to connect to finance. For founders, the key question is whether the word can carry trust in a sensitive category. For investors, the key question is whether the name has enough commercial clarity to support resale interest at a median ask of $371.45.

- Prefer words that sound credible in lending contexts
- Check if the keyword is direct, broad, or too abstract
- Use price discipline around the $371.45 median ask
- Treat weak finance fit as a demand and resale risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LOAN One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LOAN page](https://unique.domains/domains/tld/loan?utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
