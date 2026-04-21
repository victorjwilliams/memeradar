# MEMERADAR 📡

> Real-time Solana memecoin tracker with live price feeds, trend scoring, and signal indicators.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Solana](https://img.shields.io/badge/Solana-9945FF?style=flat&logo=solana&logoColor=white)
![DataViz](https://img.shields.io/badge/Data%20Visualization-00B4D8?style=flat&logoColor=white)

---

## Overview

MEMERADAR is a real-time dashboard for tracking emerging memecoins on the Solana blockchain. It combines live price data, trend-scoring algorithms, and clean data visualizations to help users monitor fast-moving tokens — without needing a technical background to understand the data.

Built with non-technical users in mind: all complexity is abstracted into simple, readable signals.

---

## Features

- 📈 **Live price tracking** — real-time price updates for Solana-based memecoins
- 🎯 **Trend scoring** — proprietary scoring system ranks tokens by momentum and activity
- 📊 **Data visualizations** — clean charts and indicators that make on-chain data readable
- 🔔 **Signal indicators** — visual cues for breakout patterns and volume spikes
- 🧭 **Non-technical UX** — designed so anyone can read the data, not just crypto natives
- ⚠️ **Built-in risk disclaimers** — responsible design baked into the UI from the start

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, JavaScript (ES6+) |
| Blockchain | Solana Web3.js |
| Data | Live price APIs, on-chain data feeds |
| Visualization | Custom JS charting (canvas/SVG) |

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/victorjwilliams/memeradar.git

# Navigate into the project
cd memeradar

# Open in your browser
open index.html
```

Runs fully in-browser. No build tools, no Node server required.

---

## How the Trend Score Works

Each token is scored across three dimensions:

| Signal | What It Measures |
|--------|-----------------|
| **Volume Spike** | Unusual increase in trading volume vs. 24h average |
| **Wallet Velocity** | Rate of new wallet addresses interacting with the token |
| **Price Momentum** | Short-term price trajectory relative to recent baseline |

Scores are weighted and combined into a single 0–100 **Radar Score** displayed per token.

---

## Design Philosophy

Most crypto dashboards are built for power users — dense tables, raw numbers, intimidating interfaces. MEMERADAR was built for the opposite: someone who wants to understand what's moving and why, without needing to decode the blockchain themselves.

Every design decision — from the scoring system to the color-coded signal cards — was made with clarity and accessibility in mind.

---

## Disclaimer

> MEMERADAR is for informational purposes only. Memecoin markets are highly volatile and speculative. Nothing displayed in this application constitutes financial advice. Always conduct your own research and never invest more than you can afford to lose.

---

## Author

**Victor Joseph Williams**  
AI Specialist · Web Developer · Digital Media Professional  
🌍 Uyo, Nigeria · Open to Remote  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/victor-williams-559842117)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/victorjwilliams)

---

> *Cutting through noise. Tracking what matters. Built for humans, powered by Solana.*
