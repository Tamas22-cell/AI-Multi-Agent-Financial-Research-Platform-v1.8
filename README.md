# AI Multi-Agent Financial Research Platform v1.8

## Portfolio Intelligence & Adaptive Financial Research

An advanced Python-based multi-agent financial research and decision-support platform combining **AI agents, market intelligence, historical validation, adaptive learning, backtesting and portfolio analytics** in one integrated architecture.

Version **1.8** introduces a dedicated **Portfolio Intelligence layer**, extending the platform from market analysis into portfolio-level risk, performance, diversification and rebalancing intelligence.

---

## Financial Intelligence Dashboard

> **Important:** Replace `YOUR_IMAGE_FILENAME.png` below with the exact filename of the dashboard image uploaded to this repository.

![AI Multi-Agent Financial Research Platform v1.8](YOUR_IMAGE_FILENAME.png)

---

## Overview

The platform uses **9 specialist financial agents**, each responsible for a different area of market research:

- Macro
- Stock
- Crypto
- On-Chain
- Derivatives
- Technical
- News
- Geopolitical
- Risk

Each specialist produces a structured assessment containing a market score, confidence level, reasoning, supporting evidence and identified risks.

A central **Orchestrator** combines these independent perspectives using weighted aggregation and generates a unified market assessment including:

- BUY / HOLD / AVOID decision
- Market regime classification
- Overall market score
- Confidence
- Bullish / neutral / bearish distribution
- Consensus measurement
- Conflict detection
- Risk-aware decision logic

---

# v1.8 — Portfolio Intelligence

Version 1.8 adds a dedicated portfolio analytics engine that transforms portfolio positions and market data into structured portfolio intelligence.

The module automatically reads portfolio positions from:

`portfolio_positions.json`

and evaluates the portfolio across several dimensions.

### Portfolio Health & Risk

The system calculates:

- Portfolio Health Score
- Portfolio Risk Score
- Health and risk classifications
- Concentration risk
- Diversification quality
- Effective number of diversified positions
- Cross-asset correlation

### Performance Analytics

Historical market data is used to estimate:

- Annualized return
- Annualized volatility
- Sharpe-like ratio
- Cumulative return
- Maximum historical drawdown

### Portfolio Holdings Analysis

Each position can be evaluated by:

- Ticker
- Asset class
- Sector
- Quantity
- Market value
- Current portfolio weight
- Historical volatility

### Rebalancing Intelligence

Current portfolio weights are compared with target allocations.

The system generates structured actions:

**INCREASE / REDUCE / HOLD**

This creates a transparent rebalancing framework instead of relying only on subjective portfolio decisions.

---

## Adaptive Agent Intelligence

The platform includes performance-based **Adaptive Agent Weights**.

Agent influence can gradually change according to measured forward performance.

The system tracks:

- Base weight
- Adaptive weight
- Performance multiplier
- Number of evaluated samples
- Provisional / established status

Small sample sizes remain clearly identified as provisional to avoid overstating statistical confidence.

---

## Market Memory

Historical system decisions are stored and analyzed through a dedicated Market Memory layer.

The platform can track:

- Previous market scores
- Historical average score
- Score changes
- Market trend direction
- Previous decisions
- Market regime evolution

This allows the system to evaluate current conditions in historical context rather than treating every execution as an isolated event.

---

## Forward Evaluation & Agent Leaderboard

Generated signals are evaluated against subsequent market performance.

The evaluation framework measures specialist-agent performance and produces an **Agent Leaderboard** based on observed forward results.

This provides the foundation for evidence-based adaptive weighting.

---

# v1.7 — Historical Backtesting & Strategy Performance

The v1.7 backtesting engine remains fully integrated into v1.8.

Historical generated signals are evaluated across:

- 1-day
- 7-day
- 30-day

time horizons.

The platform does **not** create synthetic historical signals to inflate the backtest.

It evaluates actual stored system decisions when sufficient forward market data becomes available.

### Benchmark Comparison

Strategy performance is compared with:

- **SPY**
- **BTC-USD**

The backtesting layer includes:

- Strategy return
- Benchmark return
- Excess return
- Strategy equity
- Benchmark equity
- Maximum drawdown
- Win rate
- Average win
- Average loss
- Best / worst period
- Profit factor
- Exposure rate
- Volatility
- Sharpe-like statistics

---

## Automated Research Pipeline

The platform supports an automated daily workflow:

```text
Market Data
    ↓
9 Specialist Agents
    ↓
Central Orchestrator
    ↓
Market Memory
    ↓
Adaptive Agent Weights
    ↓
Forward Evaluation
    ↓
Historical Backtesting
    ↓
Portfolio Intelligence
    ↓
Financial Intelligence Dashboard
```

The daily runner coordinates the analytical pipeline and regenerates the latest reports and dashboard automatically.

---

## Reporting

The system generates structured outputs including:

- Financial Intelligence Dashboard
- Latest Market Report
- Evaluation Results
- Signal History
- Backtesting Results
- Backtesting Report
- Portfolio Intelligence JSON
- Portfolio Intelligence Report

This makes the architecture suitable for both machine-readable research workflows and human-readable analysis.

---

## Technology Stack

**Core**

- Python
- Pandas
- NumPy
- yfinance
- Requests

**Architecture**

- Multi-Agent Systems
- Agentic AI
- Adaptive Orchestration
- Market Intelligence
- Portfolio Analytics
- Quantitative Research

**Analytics**

- Forward Signal Evaluation
- Historical Backtesting
- Benchmark Comparison
- Risk Analytics
- Correlation Analysis
- Portfolio Diversification
- Rebalancing Intelligence

**Automation & Reporting**

- Automated Daily Execution
- JSON / TXT Reporting
- HTML Financial Intelligence Dashboard

---

## Project Evolution

```text
v1.1  Agent + Orchestrator Improvements
v1.2  Research Synthesis
v1.3  Market Memory
v1.4  Adaptive Agent Weights
v1.5  Financial Intelligence Dashboard
v1.6  Automated Daily Execution
v1.7  Historical Backtesting & Strategy Performance
v1.8  Portfolio Intelligence
```

### Planned Development

Future development is focused on:

- Alert & Notification System
- Advanced Agentic Architecture
- Real LLM Integration
- Scenario & Stress Testing
- Expanded Market Data
- Long-Term Memory
- Professional Web Dashboard
- Self-Evaluation Layer
- Quantum Finance Integration

---

## Purpose

This project is designed as an evolving **financial research architecture**, not as a simple trading bot.

Its objective is to explore how specialist AI agents, quantitative analytics, historical validation, adaptive intelligence and portfolio-level analysis can work together within a transparent and modular financial decision-support system.

---

## Disclaimer

This project is intended for **research, education and experimentation**.

It does not constitute financial or investment advice.

---

**AI Multi-Agent Financial Research Platform v1.8**  
**Multi-Agent Intelligence · Backtesting · Adaptive Learning · Portfolio Intelligence**
