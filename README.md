# Available .LOAN One-Word Domains (5,622,443)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-9%2C798%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-5%2C622%2C443%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .loan one-word domains from Unique Domains.

> **Important:** this repository is a **public 9,798-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **5,622,443 domains** on the canonical page below.

**Last updated:** 2026-04-09  
**Canonical page:** `https://unique.domains/domains/tld/loan`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/loan?utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_open_search"><b>Open live .LOAN search</b></a> ·
  <a href="https://unique.domains/domains/tld/loan?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_create_radar"><b>Create .LOAN Radar</b></a> ·
  <a href="https://unique.domains/domains/tld/loan?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_start_project"><b>Start a naming Project</b></a> ·
  <a href="./loan.csv"><b>Download CSV</b></a> ·
  <a href="./loan.json"><b>Download JSON</b></a> ·
  <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_methodology"><b>Methodology</b></a> ·
  <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_api_docs"><b>API docs</b></a>
</p>

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LOAN one-word domain catalog.

### Files

- `loan.csv` — public CSV extract (9,798 rows)
- `loan.json` — public JSON extract (9,798 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract
- `assets/chart-demand-buckets.png` — generated demand-buckets chart

### Use this repo to

- inspect a public sample
- download CSV or JSON
- cite the dataset
- understand the fields and scoring inputs

### Use the live page to

- keep the exact search context
- search the full .LOAN catalog
- filter by price, demand, status, spelling risk, and fit
- save the exact search as a Radar
- turn the search into a founder Project

## 📊 Snapshot of the live .LOAN catalog

![Demand buckets across the live search](./assets/chart-demand-buckets.png)

**Why this chart:** it gives a fast overview of the live search composition using the same preview payload that supplies the README counts.

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/loan-oneword-domains/main/loan.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | purchase_price | renewal_price | attractiveness | demand | length | registrar   |
| --------------- | --------- | -------------- | ------------- | -------------- | ------ | ------ | ----------- |
| unify.loan      | available | $9.98          | —             | 72             | 38     | 5      | namecheap   |
| taiwan.loan     | resell    | —              | —             | 66             | 92     | 6      | Porkbun     |
| converse.loan   | premium   | $437.50        | $62.50        | 64             | 73     | 8      | name.com    |
| nimble.loan     | available | $9.98          | —             | 94             | 33     | 6      | namecheap   |
| line.loan       | resell    | —              | —             | 74             | 65     | 4      | Dynadot Inc |
| nationwide.loan | premium   | $6,250         | $125          | 76             | 66     | 10     | name.com    |
| trinity.loan    | available | $9.98          | —             | 72             | 31     | 7      | namecheap   |
| home.loan       | resell    | —              | —             | 100            | 62     | 4      | eNom, LLC   |
| power.loan      | premium   | $6,500         | $130          | 98             | 64     | 5      | namecheap   |
| curative.loan   | available | $9.98          | —             | 92             | 27     | 8      | namecheap   |
| arm.loan        | resell    | —              | —             | 86             | 53     | 3      | Porkbun     |
| seventeen.loan  | premium   | $437.50        | $62.50        | 84             | 62     | 9      | name.com    |
| goods.loan      | available | $9.98          | —             | 64             | 26     | 5      | namecheap   |
| moon.loan       | resell    | —              | —             | 70             | 52     | 4      | Porkbun     |
| cloud.loan      | premium   | $6,500         | $130          | 70             | 59     | 5      | namecheap   |
| drink.loan      | available | $9.98          | —             | 100            | 25     | 5      | namecheap   |
| sun.loan        | resell    | —              | —             | 78             | 45     | 3      | Dynadot Inc |
| ace.loan        | premium   | $625           | $81.25        | 88             | 57     | 3      | name.com    |
| production.loan | available | $9.98          | —             | 70             | 25     | 10     | namecheap   |
| rise.loan       | resell    | —              | —             | 62             | 45     | 4      | Dynadot Inc |

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- The live product contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LOAN One-Word Domains*. Version 2026-04-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LOAN page](https://unique.domains/domains/tld/loan?utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_loan_oneword_domains&utm_content=related_pricing)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `hello@unique.domains`
