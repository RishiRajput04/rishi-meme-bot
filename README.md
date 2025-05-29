# 🚀 Rishi Meme Bot

This bot detects and exploits MEV (Maximal Extractable Value) opportunities across Uniswap and SushiSwap for meme tokens using Flashbots and provides real-time monitoring.

## Features
- Multi-DEX support (Uniswap + SushiSwap)
- Flashbots integration
- Telegram alerts
- SQLite logging
- Flask monitoring dashboard

## Setup
```bash
bash install.sh
```

## Run the Bot
```bash
source mev-bot-env/bin/activate
python rishi_meme_bot.py
```

Dashboard available at: http://localhost:5000/status