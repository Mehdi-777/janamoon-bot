# ✈️ Janamoon — Telegram Flight Bot (n8n)

A Telegram bot that finds the **cheapest flights for the next 3 days**.
The user sends an origin and destination, the bot returns the best-priced flights, and a **Buy link** button opens that exact flight on the booking site.

> The bot doesn't sell tickets, it only searches. Built as a portfolio project to practice bot building and automation with n8n.

## Demo
[▶ Watch the demo video](demo/janamoon-demo.mp4)

## Features
- 🔎 Cheapest-flight search, domestic and international (to/from Iran)
- 📅 3-day search window
- 💬 Chat-first Telegram interface
- 🔗 One-tap "Buy link" button

## Stack
n8n · Telegram Bot API · HTTP Request · JavaScript (Code node)

## Setup
1. In n8n: **Workflows → Import from file** and select `janamoon-flight-bot.workflow.json`.
2. Create a bot token with [@BotFather](https://t.me/BotFather).
3. In the **Config** node, replace `YOUR_TELEGRAM_BOT_TOKEN` with your token and connect the Telegram credential in the Telegram nodes.
4. Activate the workflow.

⚠️ Never commit a real bot token to the repo.

## Author
Mahdi Jalambadani — [@Mehdi-777](https://github.com/Mehdi-777)
