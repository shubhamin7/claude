# Follow-up research — 2026-11-23
1. Does TrendForce split enterprise NAND from commodity NAND?
2. What Lenovo FQ2 FY26/27 says about Dell's FQ3 FY27 (reports Tue Nov 24, after the close)

Sources were read through fetched pages: three TrendForce press releases (Sep 30, Nov 11, Nov 19), Blocks & Files, Lenovo's results release, TheNextWeb (citing Bloomberg), an Investing.com call transcript, and BigGo. Short quotes only.

---

## 1. TrendForce: enterprise vs commodity NAND

**Short answer: not with numbers for 2027.** The Nov 19 release that moved the stocks gives **overall NAND figures only**. It has no table and no enterprise SSD, client SSD, eMMC/UFS or wafer ranges. Product-level numbers, if they exist, are in the paid report.

| Category | 4Q26 | 1Q27 | 2Q27 | Source |
|---|---|---|---|---|
| **Overall NAND contract** | **+8–13%** (cut from +15–20%) | **0 to −5%** | "All product categories" enter a downward cycle; drops may widen through the year. **No number given** | Nov 19 release |
| Overall NAND (secondary) | +8–13% | 0 to −5% | **0 to −5%** (*not in the TrendForce release I read, so unverified*) | Blocks & Files, Nov 20 |
| **Enterprise SSD** | No number. Sep 30 release: "the only memory product category" whose increase **accelerates** QoQ. (The +23–28% and +15–20% figures cited by secondary sites are not in the releases I read.) | No number | Declines with all categories | Sep 30 release |
| **Client SSD** | **< +5%** | No number. OEM procurement plans "being revised downward" | Declines | Nov 11 release |
| eMMC/UFS (mobile) | No number. "Price confirmation for relatively small order volumes" | No number | Declines | Sep 30 release |
| NAND wafer | No number. "Modest increase" | No number. Spot down more than 20% recently | Declines | Sep 30 / Nov 19 |

**How the narratives differ across releases (qualitative):**
- **Enterprise:** Still described as "the primary growth driver". US CSPs **raised** 2027 enterprise SSD forecasts again. Chinese CSPs cut 2027 orders **by more than the US increase**, citing GPU shortages, elevated inventory and price competition on tokens. That makes enterprise a *net* negative in 2027 even with North America growing. QLC is the swing factor: it supports vector-database and inference storage demand but also lifts bit output.
- **Commodity (client, mobile, wafer):** Already soft. Notebook shipments fell 15.8% QoQ in 3Q26. PC OEMs cut 4Q26 client SSD buying because finished-goods inventory is high. Brands are lowering storage capacity per device to cut BOM cost. Channel spot prices are down more than 20%.
- **Supply:** 2027 NAND bit growth +25–30%. 2027 NAND capex +26.7% to $29.9B.

**What this means for the thesis:**
- The turn **starts in the commodity segments, and enterprise follows from 2Q27.** For roughly two quarters, enterprise should hold up better than the overall NAND number.
- **SNDK:** about half of FY27 bits sit under long-term agreements, and its datacenter mix is rising. The 1Q27 hit to its blended ASP is probably smaller than the headline "0 to −5%". The 2Q27+ path ("all categories") is the real risk.
- **MU:** NAND is a minority of revenue, so this is a secondary effect.
- **Things to watch:** any enterprise-specific 1Q27 number (paid report or roadshow), and Chinese CSP capex and GPU availability. If Chinese GPU supply eases, for example through any Nvidia China licence, the enterprise SSD cut could reverse.

Sources: [TrendForce Nov 19](https://www.trendforce.com/presscenter/news/20261119-13314.html) · [TrendForce Nov 11](https://www.trendforce.com/presscenter/news/20261111-13303.html) · [TrendForce Sep 30](https://www.trendforce.com/presscenter/news/20260930-13258.html) · [Blocks & Files](https://www.blocksandfiles.com/flash/2026/11/20/flash-prices-start-to-fall/5311258)

---

## 2. Lenovo FQ2 FY26/27 (Jul–Sep 2026; reported Nov 19) → read-across to Dell FQ3 FY27 (Aug–Oct 2026)

### Lenovo: the numbers that matter for Dell
| | Lenovo FQ2 | Comment |
|---|---|---|
| Group revenue | **$30.2B, +48% YoY** (record) | Beat the ~$27.1B consensus |
| Reported result | **Operating loss of $117M; net loss of about $640M** | Driven by a **~$1.9B non-cash warrant fair-value loss** (Bloomberg via TNW). Excluding it: adjusted op income $1.9B (+156%), adjusted net $1.4B (+166%). **This is not an operating miss.** |
| **ISG (servers/storage)** | **$11.3B, +178%**; op profit >$1B; **op margin 9.6% (record)** | GPU server revenue **+300%+** |
| AI pipeline | **$80B, +48% QoQ** | BigGo calls it an "order backlog" (~¥530B) |
| x86 share | **#1 for the first time, 16% (+6 pts)** | Excludes ODM-direct. Share is coming from someone, possibly Dell, HPE or Supermicro |
| Customer mix | CSP revenue +~170%; enterprise/SMB infrastructure +200%; neocloud <20% of ISG | Enterprise demand described as "accelerating" |
| **IDG (PCs)** | **$17.4B, +15%; op margin 7.1% (held)** | **Units −22.4%**, ASP up double digits, commercial PC revenue +~20% |
| Memory commentary | "Market is supply constrained from components perspective" (CFO). Yang: the AI-server constraint is **memory supply, not demand**. Costs "managed" via scale, design-to-cost and pricing | PC market expected to stay in "adjustment" for **2–3 more quarters** |
| Stock | HK −5.5% on the day (warrant-loss headline). **Dell and HPE rose ~4% in US premarket** on the read-across | |

### Dell setup going into Nov 24
- **FQ3 guide:** revenue **~$49.0B (+81%)**, non-GAAP EPS **~$6.50**, AI server revenue **~$19.0B** (vs $16.4B in FQ2). Consensus EPS is about $6.63 (Zacks; may be stale).
- **FY27 guide:** **$192B ± $2B**, EPS **$25.50**, AI servers **$74B**. Backlog exiting FQ2 was **$95B**, after $60.9B of FQ2 AI orders.
- The stock is about 43–47% below its Oct 7 high ($578), with weak sentiment after the Nvidia and AI selloff.

### Prediction (my judgement, not consensus)

**1. AI server revenue: in line or modestly above $19B. Orders and backlog are the bigger upside risk.**
Lenovo's GPU servers grew 300%+ and its pipeline grew 48% QoQ, and management said it saw no demand change in the CSP, enterprise or neocloud channels. Both companies ship Nvidia Vera Rubin, so the demand signal carries over. The binding constraint at Lenovo was **memory supply**, and Dell has said the same ("DRAM, DRAM, DRAM"). So **shipments, not demand, set the revenue figure**: expect Dell to land close to the guide rather than blow through it. Backlog is likely to be **at or above $95B**. A large QoQ backlog increase is plausible given Lenovo's +48% pipeline growth.
*Probability view: ~60% AI revenue ≥ $19B; ~70% backlog ≥ $95B.*

**2. ISG margin: likely holds. Memory pass-through on servers works.**
Lenovo printed a **record 9.6% ISG margin** while memory costs inflated, which shows server OEMs are passing costs through. Dell's AI mix shift still dilutes the margin percentage, but operating income dollars should grow. Lenovo's x86 share gain (+6 pts) is a **mild warning for Dell's traditional server line**. Dell's last print showed traditional servers +122% with share gains, so watch whether Dell repeats that.

**3. CSG (PCs): revenue up on price, units down, margin is the swing factor.**
Lenovo's PC units fell **22%** but revenue rose **15%** on double-digit ASP increases, and it held a 7.1% margin. Its **commercial PC revenue grew ~20%**, which matters because Dell's PC business is commercial-heavy. Expect **Dell CSG revenue to be flat to up** on price, with units down sharply. Dell has historically had less scale-driven procurement leverage than Lenovo, so its **CSG margin is the most likely line to disappoint**, especially in consumer.

**4. Guidance: where the stock reaction will come from.**
- **Positive skew:** an FY27 AI server reiteration or raise (≥$74B), and early FY28 commentary (Lenovo is talking about $100B annual revenue and accelerating enterprise demand).
- **Negative skew:** Lenovo's "2–3 more quarters" of PC adjustment, plus memory costs. Dell may guide FQ4 margins and EPS cautiously, or call out supply gating.
- **Base case:** headline revenue beat driven by AI servers, in-line to slightly better EPS, and cautious PC and margin language. Given the beaten-down stock and the ~4% sympathy move on Lenovo, **the bar is low on demand and high on margin and memory commentary.**

**5. Read-across to MU and SNDK (from both reports).**
- Lenovo says AI servers are **gated by memory supply**. That supports **DRAM/HBM** tightness and MU's "75% of 2027 sold" comment.
- PC units −22% and OEMs cutting client SSD buying confirm **TrendForce's commodity-NAND weakness**, which is negative at the margin for SNDK's client mix.
- **On Dell's call, listen for:** whether DRAM and NAND are still the constraint, whether memory costs are still rising or plateauing, and storage (PowerScale/ObjectScale) demand as an enterprise-SSD proxy.

### Caveats
- The quarters are offset by one month: Lenovo covers Jul–Sep, Dell covers Aug–Oct. Dell's quarter includes October, when AI sentiment started to crack, but there is no evidence of order cuts.
- Lenovo has more China and Asia exposure and a smaller neocloud share (<20% of ISG). Dell is more exposed to US neoclouds, where financing stress (CoreWeave and similar) is the tail risk.
- Lenovo gross margin was not disclosed. Some Investing.com per-share figures conflict with other sources and were ignored.

Sources: [Lenovo release](https://news.lenovo.com/pressroom/press-releases/q2-fy-2026-27/) · [TheNextWeb](https://thenextweb.com/news/lenovo-results-q2-record-revenue-640m-loss-ai-servers) · [Investing.com transcript](https://ca.investing.com/news/stock-market-news/earnings-call-transcript-lenovo-tops-revenue-forecasts-in-q2-2026-as-ai-growth-surges-93CH-4968860) · [BigGo](https://finance.biggo.com/news/bdaf3446-c2c5-4f26-8e80-0bdaedb082f4) · [Dell guidance (Yahoo)](https://finance.yahoo.com/news/dell-forecasts-fiscal-2027-revenue-210929667.html) · [Dell preview (Finviz/Earnings Whispers)](https://finviz.com/news/423394/dell-must-prove-its-95-billion-ai-backlog-can-convert-despite-memory-constraints) · [TradingKey Dell setup](https://www.tradingkey.com/analysis/stocks/us-stocks/262315073-dell-earnings-tuesday-47-percent-below-high-295-25-support-november-21-2026-tradingkey)
