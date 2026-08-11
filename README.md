<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LifeAnalysis/LifeAnalysis/main/.github/assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LifeAnalysis/LifeAnalysis/main/.github/assets/banner-light.svg">
  <img alt="LifeAnalysis — crypto research and execution systems" src="https://raw.githubusercontent.com/LifeAnalysis/LifeAnalysis/main/.github/assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin">
  <img src="https://img.shields.io/badge/Solana-14F195?style=flat-square&logo=solana&logoColor=black" alt="Solana">
  <img src="https://img.shields.io/badge/Hyperliquid-97FCE4?style=flat-square&logoColor=black" alt="Hyperliquid">
  <img src="https://img.shields.io/badge/Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="Postgres">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
</p>

> Signal in, size on, risk off. Everything else is decoration.

### ⚡ Building

- 🔗 **Onchain data pipelines** — protocol scoring, wallet clustering, flow analysis
- 🤖 **Multi-agent research systems** — market intelligence with configurable pipelines
- 📉 **Perps execution** — programmatic risk management on Hyperliquid

### 🔬 Researching

- 🎲 **Prediction markets** — Polymarket and Kalshi strategy backtests
- 🌉 **Cross-chain rate spreads** — funding-basis and borrow-rate structures
- 🏛️ **Tokenized equities** — market microstructure and pricing dislocations

### 🚀 Shipping

| Repo | What it does |
|---|---|
| **[spt-index](https://github.com/LifeAnalysis/spt-index)** | DeFi protocol scoring, z-score normalized across TVL, revenue and flow |
| **[dao-buyback-dashboard](https://github.com/LifeAnalysis/dao-buyback-dashboard)** | Buyback tracking across Hyperliquid, Jupiter and Solana DAOs |
| **[optionsviz](https://github.com/LifeAnalysis/optionsviz)** | Options surface overlays for treasury positioning |
| **[Stockscalendar.xyz](https://github.com/LifeAnalysis/Stockscalendar.xyz)** | Research terminal for tokenized equities |

### 🧭 How the stack fits together

```mermaid
flowchart LR
    A[Onchain data] --> B[Normalize & score]
    C[Market data] --> B
    D[Social & news] --> B
    B --> E{Signal}
    E -->|backtest| F[Strategy research]
    E -->|live| G[Execution engine]
    F --> G
    G --> H[Risk manager]
    H -->|size, stop, kill| G
    H --> I[Positions & PnL]
```

<details>
<summary>🗄️ &nbsp;<b>Also in the workshop</b></summary>

<br>

- **whatsapp-outreach-bot** — Android outreach automation, multi-device, Kotlin
- Prediction-market monitors, copytrade shadowing, wallet ranking
- Perps risk tooling — ladder sizing, kill switches, exposure caps
- Assorted landing pages and prototypes that never made it past week two

</details>

---

<p align="center">
  <sub>Most of what I build is private. The pinned repos are the public slice.<br>
  Reach me by opening an <a href="https://github.com/LifeAnalysis/LifeAnalysis/issues">issue</a>.</sub>
</p>
