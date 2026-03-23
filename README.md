# Day1Global-Skills

Investment Analysis Skills for AI Agents — covering tech earnings, value investing, market sentiment, macro liquidity, and Bitcoin cycle analysis.

## Skills Overview

| Skill | Description |
|-------|-------------|
| `tech-earnings-deepdive` | Institutional-grade tech stock earnings deep dive with 16 analysis modules, 6 investment philosophy perspectives, and actionable decision framework |
| `us-value-investing` | Buffett-style 4-dimension value investing analysis (ROE, debt safety, FCF quality, economic moat) |
| `us-market-sentiment` | US stock market sentiment monitoring via 5 core indicators (NAAIM, institutional allocation, retail flows, forward P/E, hedge fund leverage) |
| `macro-liquidity` | Global liquidity monitoring and risk early-warning system (Fed net liquidity, SOFR, MOVE index, yen carry trade) |
| `btc-bottom-model` | Bitcoin bottom-timing model using 6 on-chain and market indicators (RSI, volume, MVRV, fear index, miner cost, LTH behavior) |

## Installation

```bash
npx skills add https://github.com/star23/Day1Global-Skills --all
```

## Usage

No additional configuration needed after installation. Simply ask your AI agent questions in natural language — the relevant skill activates automatically when it detects matching topics.

### tech-earnings-deepdive

A comprehensive tech stock earnings analysis and multi-perspective investment memo system (v3.0).

**What it does:**

- **Key Forces Identification** — Pinpoint 1-3 decisive forces that determine the company's future value
- **16 Analysis Modules (A-P)** — Revenue quality, profitability, cash flow, forward guidance, competitive landscape, core KPIs, products & new businesses, partner ecosystem, executive team, macro & policy impact, valuation models, ownership distribution, long-term monitoring variables, R&D efficiency, accounting quality, ESG screening
- **6 Investment Philosophy Perspectives** — Quality Compounder (Buffett/Munger), Imaginative Growth (Baillie Gifford/ARK), Fundamental Long-Short (Tiger Cubs), Deep Value (Klarman/Marks), Catalyst-Driven (Tepper/Ackman), Macro Tactical (Druckenmiller)
- **Multi-Method Valuation Matrix** — Owner Earnings, PEG, Reverse DCF, Magic Formula, EV/EBITDA, EV/Revenue + Rule of 40
- **Variant View** — Identify blind spots in market consensus
- **Anti-Bias Framework** — 6 cognitive trap self-checks, 7 financial red flags, 5 tech-specific blind spots, Pre-Mortem analysis
- **Actionable Decisions** — Action Price, position sizing cadence, add/trim/exit triggers, long-term monitoring checklist

**Example prompts:**

```
Analyze NVDA's latest earnings report
```
```
How did META perform this quarter?
```
```
Analyze MSFT from multiple legendary investors' perspectives. Is it a buy right now?
```

**Evidence Standards:**

| Tier | Type | Examples |
|------|------|---------|
| Tier 1 | Primary Sources | CEO quotes, employee reviews, customer feedback, GitHub activity, patents, hiring trends |
| Tier 2 | Factual Sources | SEC filings (10-K/10-Q/8-K), financial data, court documents |
| Tier 3 | Opinion Sources | Sell-side research, news analysis, price target consensus |

---

### us-value-investing

Systematically evaluates listed companies through 4 core dimensions using Buffett-style value investing methods.

**4 Dimensions:**

1. **ROE Sustainability** — 3+ years of consistent returns on equity
2. **Debt Safety** — Debt-to-asset ratio and leverage assessment
3. **Free Cash Flow Quality** — FCF vs. net income ratio
4. **Economic Moat** — Brand, network effects, cost advantage, switching costs

**Scoring:** Each dimension scores 0-3 points (max 12). Ratings: A (10-12), B (7-9), C (4-6), D (0-3).

**Example prompts:**

```
Is AAPL worth holding long-term from a value investing perspective?
```
```
Help me analyze COST's fundamentals
```

---

### us-market-sentiment

Monitors US stock market sentiment through 5 core indicators to determine greed/fear levels and provide position recommendations.

**5 Indicators:**

1. **NAAIM Exposure Index** — Active fund manager equity exposure
2. **Institutional Equity Allocation** — Global institutional portfolio allocation
3. **Retail Net Buying** — Daily retail investor fund flows
4. **S&P 500 Forward P/E** — Valuation metric vs. historical range
5. **Hedge Fund Leverage** — Borrowing multiples from prime brokerage data

**Example prompts:**

```
Is the US stock market overheating right now?
```
```
Should I reduce my positions?
```

---

### macro-liquidity

Tracks the most critical "water level" in the global financial system — liquidity — through 4 core indicators.

**4 Indicators:**

1. **Fed Net Liquidity** — Fed Total Assets - TGA - ON RRP
2. **SOFR Rate** — Overnight funding stress in the banking system
3. **MOVE Index** — Treasury market volatility (bond market VIX)
4. **Yen Carry Trade Signals** — USDJPY and US-Japan yield spread

**Example prompts:**

```
How is liquidity right now?
```
```
Is the Fed injecting or draining liquidity?
```

---

### btc-bottom-model

Systematically determines whether Bitcoin has entered a bottom zone worth building a position in, using 6 on-chain and market indicators.

**6 Indicators:**

1. **Weekly RSI** — Technical oversold signal
2. **Volume Dry-up** — Selling exhaustion detection
3. **MVRV Ratio** — Market value vs. realized value
4. **Fear & Greed Index** — Social media sentiment
5. **Miner Shutdown Price** — Production cost floor
6. **Long-Term Holder Behavior** — Smart money accumulation signals

**Example prompts:**

```
Has Bitcoin bottomed out? Can I buy the dip?
```
```
What do on-chain indicators say about BTC right now?
```

---

## Skill Synergy

| Combination | Use Case |
|-------------|----------|
| `tech-earnings-deepdive` + `us-value-investing` | Cross-validate earnings analysis with 4-dimension value scoring |
| `tech-earnings-deepdive` + `us-market-sentiment` | Factor macro sentiment into earnings analysis |
| `tech-earnings-deepdive` + `macro-liquidity` | Integrate liquidity conditions when it's a Key Force |

## Disclaimer

All analyses generated by these skills are based on publicly available information and model estimates. They are for research purposes only and do not constitute investment advice. Investing involves risk — please exercise caution in your decisions.
