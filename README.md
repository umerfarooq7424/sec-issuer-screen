# SEC Issuer Financial Screen

> Memory-conscious screening of the SEC filings archive: 3.9 million numerical facts scanned, 1,905 manufacturing issuers selected, and three screening ratios calculated for 1,376 issuers (72.2%) — with coverage reported before any financial interpretation.

## Headline result

**Coverage must precede interpretation.** The run scanned **3,905,397 numerical facts** from the SEC 2026 Q3 filing archive across **1,946 eligible 10-K / 10-Q filings**, selected **1,905 manufacturing issuers**, and retained 8,899 candidate facts. All three screening ratios were calculable for **1,376 of 1,905 issuers (72.2%)**. Missing or quarantined facts stay visible — they are never replaced with zero.

## How it works

- Chunked Python processing of the SEC archive (built for memory limits, not brute force)
- Explicit scope filters and one-filing-per-issuer selection
- Duplicate and value controls; 3 accession/tag groups quarantined with reasons
- Staleness flagging: 9 issuers with reporting periods over 180 days old
- Coverage reporting as a first-class output, ahead of any ratio table

## Contents

- `reports/Task3_SEC_Issuer_Screen_Report.pdf` — the full retrospective report: method, controls, coverage tables, and results

This screen produces a starting point for company-level review. It is not a credit rating or an investment recommendation.

## Data source

SEC EDGAR filing archive (public).

## Author

**Umer Farooq** — Economic & Climate Risk Analyst · [LinkedIn](https://www.linkedin.com/in/umer-farooq-gojra/) · [GitHub](https://github.com/umerfarooq7424)

## License

MIT — see LICENSE.
