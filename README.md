# 📊 Franklin Framework - Technical Showcase

## 🎯 What It Does

Advanced financial analysis system that processes SEC XBRL filings and applies investment philosophies from Benjamin Graham, Warren Buffett, and Charlie Munger to generate institutional-grade investment scorecards.

**Key Innovation:** Philosophy Moat™ - The only system that combines three legendary investors' frameworks into a unified scoring algorithm.

## 📈 Real Performance Metrics
```
✅ 504/504 tests passing (99.6% coverage)
✅ Sub-3 second full pipeline execution
✅ 23 companies analyzed across 5 sectors
✅ Multi-year XBRL processing (3-6 years historical)
✅ 500ms per SEC filing processed
✅ 25 financial KPIs calculated
```

## 🏗️ System Architecture
```
Input: SEC EDGAR XBRL Filings
  ↓
┌─────────────────────────────────────┐
│ XBRL Parser Engine                  │
│ • Multi-file processing             │
│ • Fuzzy concept mapping             │
│ • Context-aware extraction          │
└─────────────────────────────────────┘
  ↓
┌─────────────────────────────────────┐
│ Metrics Calculator (25 KPIs)        │
│ • Valuation (P/E, P/B, EV/EBITDA)   │
│ • Profitability (ROE, ROA, ROIC)    │
│ • Efficiency (Turnover ratios)      │
│ • Liquidity (Current, Quick ratios) │
│ • Leverage (D/E, Coverage ratios)   │
└─────────────────────────────────────┘
  ↓
┌─────────────────────────────────────┐
│ Philosophy Moat™                    │
│                                     │
│  ┌────────────────────────────┐    │
│  │ Graham Interpreter         │    │
│  │ Score: 0-5                 │    │
│  │ • Margin of Safety         │    │
│  │ • Earnings Stability       │    │
│  │ • Debt Conservative        │    │
│  │ • Dividend Record          │    │
│  │ • Asset Value              │    │
│  └────────────────────────────┘    │
│                                     │
│  ┌────────────────────────────┐    │
│  │ Buffett Interpreter        │    │
│  │ Score: 0-5                 │    │
│  │ • Economic Moat            │    │
│  │ • Management Quality       │    │
│  │ • Pricing Power            │    │
│  │ • Free Cash Flow           │    │
│  │ • Long-term Growth         │    │
│  └────────────────────────────┘    │
│                                     │
│  ┌────────────────────────────┐    │
│  │ Munger Interpreter         │    │
│  │ Score: 0-5 + Red Flags     │    │
│  │ • Inversion Thinking       │    │
│  │ • Circle of Competence     │    │
│  │ • Mental Models            │    │
│  │ • Simplicity Bias          │    │
│  │ • Avoid Stupidity          │    │
│  └────────────────────────────┘    │
└─────────────────────────────────────┘
  ↓
┌─────────────────────────────────────┐
│ Philosophy Orchestrator             │
│ • Sector-aware weighting            │
│ • Conflict resolution               │
│ • Score normalization (0-100)       │
│ • Recommendation mapping            │
└─────────────────────────────────────┘
  ↓
┌─────────────────────────────────────┐
│ AI Debate Engine (GPT-4)            │
│ • Divergence detection              │
│ • Context-aware explanations        │
│ • 4 debate templates                │
└─────────────────────────────────────┘
  ↓
Output: Unified Score (0-100) + Recommendation
```

## 💎 Competitive Advantages

### 1. Philosophy Moat™ (Patent Pending)
**Only system in the market** that combines Graham, Buffett, and Munger methodologies into a single, sector-aware scoring framework.

### 2. Sector-Aware Weighting
Dynamic weight adjustment based on industry characteristics:

| Sector | Graham (Value) | Buffett (Moat) | Munger (Rationality) |
|--------|---------------|----------------|---------------------|
| **TECH** | 15% | 50% | 35% |
| **FINANCE** | 50% | 25% | 25% |
| **INDUSTRIAL** | 33% | 33% | 34% |
| **MINING** | 40% | 30% | 30% |
| **OIL & GAS** | 35% | 35% | 30% |

**Rationale:** Tech companies have intangible moats (brand, network effects) that Graham's book value approach misses, so Buffett's framework gets higher weight. Financial institutions require conservative balance sheets, so Graham's safety principles dominate.

### 3. AI-Powered Debate
Automatic detection and explanation of philosophy divergences using GPT-4. When Graham says "SELL" but Buffett says "BUY," the system explains why.

### 4. Institutional-Grade Transparency
Complete audit trails from SEC filing line numbers to calculated metrics (production feature).

## 🔧 Technology Stack
```python
Core:       Python 3.10+
Parsing:    lxml, beautifulsoup4
Financial:  yfinance, pandas, numpy
AI:         OpenAI GPT-4
Testing:    pytest (504 tests, 99.6% coverage)
Database:   SQLite (XBRL cache)
```

## 📊 Sample Output

See `examples/aapl_analysis.json` for a real analysis of Apple Inc.

**Summary:**
- **Ticker:** AAPL
- **Unified Score:** 88/100
- **Recommendation:** STRONG BUY
- **Graham:** 1/5 (fails P/B test - 50x book value)
- **Buffett:** 5/5 (wonderful business - strong moat)
- **Munger:** 5/5 (rational investment - 1 minor liquidity flag)
- **AI Debate:** "Graham's value metrics penalize AAPL due to high P/B ratio and debt levels. However, Buffett's approach favors AAPL because of its strong brand, network effects, and high switching costs..."

## 🚀 Production System Features

The full commercial system includes:

- ✅ Complete XBRL parser with fuzzy mapping
- ✅ 25 financial KPIs across 5 categories
- ✅ Proprietary sector classification algorithm
- ✅ Multi-year trend analysis (3-6 years)
- ✅ Advanced red flag detection (Lollapalooza effects)
- ✅ Stress testing scenarios (FED hikes, recession, etc.)
- ✅ Macro regime weighting (bull/bear/crisis)
- ✅ Audit trail system (SEC filing provenance)
- ✅ API for programmatic access
- ✅ Batch processing pipeline
- ✅ Real-time data updates

## 📐 Architecture Principles

1. **Separation of Concerns:** Each philosophy interpreter is independent
2. **Test-Driven Development:** 504 tests, 99.6% coverage
3. **Production-Ready:** Error handling, caching, performance optimization
4. **Scalable Design:** Multi-threading ready, database-backed
5. **Clean Code:** Type hints, docstrings, consistent style

## 🎓 Why This Matters

### The Problem
- Bloomberg Terminal: $24,000/year, opaque algorithms, no philosophy framework
- Traditional tools: Focus on raw metrics, miss qualitative insights
- No system combines multiple investment philosophies systematically

### The Solution
Franklin Framework provides:
- **Transparency:** Every score is explainable
- **Sophistication:** Sector-aware, AI-powered insights
- **Affordability:** 90% cheaper than Bloomberg
- **Unique Moat:** Philosophy Moat™ methodology

## 🔒 Commercial Licensing

**Pricing Tiers:**
- **Retail ($99/mo):** Core metrics + 1 philosophy
- **Professional ($499/mo):** All 3 philosophies + unified scoring
- **Institutional ($2,500/mo):** Full transparency + API access

**Target Market:**
- Retail investors seeking systematic analysis
- RIAs managing client portfolios
- Hedge funds requiring philosophy-based screening
- Financial advisors needing client reporting tools

## 📫 Contact

**For commercial licensing inquiries:**
- Email: franklinnrodriguez@gmail.com
- Location: Villavicencio, Colombia
- Status: Production-ready system, active development

## 📜 License

- **This showcase repository:** MIT License (documentation only)
- **Production system:** Proprietary - Commercial licensing required

---

**Built by Franklin** | CTO & Financial Systems Architect  
*Combining legendary investment wisdom with modern AI*
