# 📊 Telegram Trading Mini App

A simple **Telegram Mini App (WebApp)** UI for controlling a trading bot inside Telegram.

---

## Features

- Interactive **BUY** and **SELL** buttons
- Sends user action instantly to the Telegram bot for processing
- Mobile-first UI, works inside the Telegram mobile and desktop apps

---

## How it Works

1. **Host your code** (this repo) using [GitHub Pages](https://pages.github.com/), Vercel, or any static web host.
2. Copy your site link, e.g., `https://username.github.io/repository-name/`.
3. In your Telegram bot, set the domain in **BotFather** using the `/setdomain` command.
4. Update your bot source code:
    - Set the Mini App URL in `WebAppInfo` in your bot's reply markup.
5. Any time a user taps a button, the action (`BUY` or `SELL`) is sent back to the bot.

---

## Example: Add to Bot Code

