# AI Multi-Agent Financial Research Platform v1.8

## Portfolio Intelligence & Adaptive Financial Research

An advanced Python-based multi-agent financial research and decision-support platform combining AI agents, market intelligence, historical validation, adaptive learning, backtesting and portfolio analytics in one integrated architecture.

Version **v1.8** introduces a dedicated **Portfolio Intelligence Layer**, extending the platform from market analysis into portfolio-level risk, performance, diversification and rebalancing intelligence.

---

## Financial Intelligence Dashboard

![AI Multi-Agent Financial Research Platform v1.8](7e090014-4e24-41b4-b3c1-2a5e67f85e331.png)

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

Each specialist produces structured analytical output including:

- Market signal
- Numerical score
- Confidence level
- Reasoning
- Supporting evidence
- Identified risks

A central **Orchestrator** combines these independent perspectives using adaptive weighted aggregation and generates a unified market decision.

Current decision classes:

- **BUY**
- **HOLD**
- **AVOID**

The Orchestrator also determines:

- Market regime
- Market score
- Average confidence
- Bullish / Neutral / Bearish distribution
- Consensus strength
- Signal conflicts
- Risk overrides
- Strongest positive and negative signals

---

# Architecture

```text
Market Data
    │
    ▼
9 Specialist Agents
    │
    ▼
Adaptive Agent Weights
    │
    ▼
Central Orchestrator
    │
    ├── Market Decision
    ├── Market Regime
    ├── Consensus Analysis
    ├── Risk Analysis
    └── Signal Conflict Detection
    │
    ▼
Research Synthesis
    │
    ├── Market Memory
    ├── Forward Evaluation
    ├── Agent Leaderboard
    └── Historical Backtesting
    │
    ▼
Portfolio Intelligence
    │
    ├── Portfolio Health
    ├── Portfolio Risk
    ├── Performance Analysis
    ├── Diversification
    ├── Correlation Analysis
    └── Rebalancing Intelligence
    │
    ▼
Financial Intelligence Dashboard
