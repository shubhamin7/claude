# AI capex credit watch — 2026-11-25

**TRIPWIRE FIRED: #1 (neocloud credit stress), continuing and re-widening.** CRWV's 2032 notes yield 15.48% (11/23 close), up ~127bp WoW. At the 11/24 intraday low they yielded ~16.65%. That is +360–480bp versus ~11.6–11.9% in late September. #3 (Nvidia DSO) stays fired from last week; there is no new quarterly data.

## A1. Credit proxies

| Name | Metric | This week | Prior (11-18 log) | WoW | Source |
|---|---|---|---|---|---|
| CRWV | 9.625% 2032 YTW | **15.48%** @ 78.424 (11/23) | ~14.21% @ 82.50 | **+127bp** | [Bond Terminal](https://bondterminal.com/issuers/coreweave-inc), my calculation reproduces it (15.49%) |
| CRWV | 9.625% 2032, 11/24 low | 74.9 (−4.6pts intraday) → ~16.65% (my calc) | — | — | [Bloomberg 11/24](https://bloomberg.com/news/articles/2026-11-24/coreweave-bonds-hit-all-time-lows-erasing-nvidia-fueled-gains): record low since the June 2026 launch |
| CRWV | Other unsecured notes (11/23) | 9.25% 2030 15.25%; 9% 2031 15.67%; 9.75% 2031 15.61% | 14.2–14.8% (11/12) | ≈ +100bp | Bond Terminal. The 9.75% 2031 was >17% on 11/24 ([Superpower Daily](https://superpowerdaily.com/posts/coreweave-falls-13-as-ai-debt-worries-deepen-after-huang-s-return) citing Bloomberg) |
| CRWV | Spread vs UST | ~1,072bp (11/23); ~1,193bp at the 11/24 low | ~937bp | +135bp | My derivation, not a published spread: YTW minus the interpolated 5y/7y UST (4.76% / 4.72%), from [Treasury.gov](https://home.treasury.gov/resource-center/data-chart-center/interest-rates/TextView?type=daily_treasury_yield_curve&field_tdr_date_value=2026) |
| CRWV | 5y CDS | >1,200bp on 11/24, +8.5% d/d | NA (peak 1,289bp 11/5) | — | Bloomberg via Superpower Daily, third-party reported |
| CRWV | Short interest | 87.47M sh (11/13 settlement), DTC 1.15. About **26.6%** of float (derived) | 74.21M (10/30) ≈ 22.6% | ↑ | [Nasdaq](https://www.nasdaq.com/market-activity/stocks/crwv/short-interest). The float denominator is implied from FINRA 10/15 (21.25%), so the % is a derivation |
| NBIS | YTW / spread | NA (converts only) | NA | — | — |
| NBIS | Short interest | 54.72M sh (11/13), DTC 1.72. About **23.9%** of float (derived) | 50.94M (10/30) = 22.27% | ↑ | Nasdaq, same method (it reproduces the FINRA 10/30 22.27%) |
| IREN | Short interest | 115.19M sh (11/13), DTC 1.45 | 94.68M (10/30) | ↑ +22% | Nasdaq. % of float NA |
| APLD | Short interest | 66.52M sh (11/13), DTC 2.33 | 61.43M (10/30) | ↑ +8% | Nasdaq. % of float NA |
| IREN / APLD | YTW | NA | NA | — | No published quotes found |

**New issuance and ratings**
- **CRWV, NBIS, IREN:** No new bond or convert. EDGAR shows no debt 8-K/6-K for 11/18–11/24.
- **APLD ([8-K 11/24](https://www.sec.gov/Archives/edgar/data/1144879/000149315226054002/form8-k.htm)):**
  - Closed a **$300M 364-day senior secured delayed-draw bridge** for Delta Forge 1 at **SOFR+300**. That is ~6.92% all-in at SOFR 3.92% ([NY Fed](https://markets.newyorkfed.org/api/rates/secured/sofr/last/3.json), 11/23). Its prior raise was 7.000% senior secured notes due 2031 at par (Jun-26), so this is not wider, though the instruments differ.
  - Draws are conditional on construction milestones, **state commission approval of electrical rates**, lender consents and covenants. APLD "expects to seek additional financing" to complete the campus.
  - Also upsized the Series G preferred facility from $2.0B to $2.5B ($1.035B remaining).
  - Signed a new 150MW, 18-yr lease with an unnamed IG hyperscaler, ~$5.4B base term.
- **CRWV ~$4B Meta-backed IG loan:** still in talks, with no signing 8-K ([Bloomberg 11/11](https://www.bloomberg.com/news/articles/2026-11-11/coreweave-plans-to-raise-at-least-4-billion-in-high-grade-loan)).
- **Ratings:** No rating action found for any of the four names.

## A2. Structure changes
- **Huang reinstated as Nvidia CEO, 11/22** ([8-K](https://www.sec.gov/Archives/edgar/data/1045810/000104581026000090/nvda-20261122.htm), [PR](https://www.sec.gov/Archives/edgar/data/1045810/000104581026000090/nov23pressrelease.htm)). Kress returns to CFO.
  - I found no new statement on financing policy. Kress's "rigorously evaluating" and "disciplined and selective" posture from the 11/18 call has not been publicly restated or reversed.
  - Credit sold off the following day (11/24), with CRWV, Oracle and NVDA CDS all wider (Bloomberg via Superpower Daily).
- **New Nvidia equity investment, signed but conditional.** Nvidia will buy 120,481,927 Anthropic Class N shares, about **$10.0B**, at the $83 IPO price. This is part of a $26.0B concurrent placement alongside Google ($10.0B), AMD, Broadcom, Micron, Microsoft and TSMC ([Anthropic 424B4, 11/19](https://www.sec.gov/Archives/edgar/data/2130357/000162828026074944/anthropicpbc-424b4.htm)). The counterparty has independent revenue.
- **$500B financing platforms** (Apollo, BlackRock, Blackstone, Brookfield, GS, KKR): still MOUs. The WSJ reports "no capital has actually been deployed" ([Fortune 11/19](https://fortune.com/2026/11/19/nvidia-funding-deal-anthropic-ipo/), anonymous sources). Apollo's Rowan: "access to capital for a large number of neoclouds is going to disappear." No size, collateral or first-loss terms have been disclosed.
- **Lambda/Anthropic $34.9B:** still terminable by either party, with no termination notice. Anthropic does not currently intend to terminate (424B4, 11/19, primary). This is unchanged.
- **NVDA concentration** ([supplemental info, 8-K 11/17](https://www.sec.gov/Archives/edgar/data/1045810/000104581026000088/)):
  - Q3 revenue: three direct customers at 14%, 11% and 11%.
  - Accounts receivable: two customers at 18% and 17%. In Q2, five customers made up 22/14/13/11/10% of AR.
  - The Q3 10-Q is not yet filed as of 11/25.

## C. Tripwire check
| # | Status |
|---|---|
| 1 Neocloud credit stress | **FIRED (continuing).** CRWV 2032 15.48% vs ~11.6–11.9% late Sep. Re-widened ~+127bp WoW |
| 2 Refinancing failure | Not fired. **Watch:** CRWV $4B IG loan is still unsigned. The APLD bridge is milestone- and rate-approval-conditional, and further financing is still needed |
| 3 NVDA DSO | **Fired (carried from 11/18 quarterly data):** 45→60→64. No new quarter |
| 4 Revenue quality | Not fired. AR concentration is now two customers at 35% combined, versus five at 70% in Q2. Disclosure is not less granular |
| 5 Depreciation extension | Not fired. No server or GPU useful-life change found |
| 6 Capex guidance cut | Not fired. No guidance change this week |
| 7 Commitment unwind | No new event this week. Lambda $34.9B is still terminable, not terminated. Last week's IREN/MSFT deferral stands |
| 8 Off-balance-sheet growth | Not fired this week. The platforms have no deployed capital (reported). There are no new NVDA guarantees since the 11/17 disclosure |
| 9 NVDA impairment | No new event. The $1.8B Q3 impairment was logged 11/18 |
