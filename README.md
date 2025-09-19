# Hedgegram Mini Bot

This is a simple Telegram bot that supports commands like pause, start, status, exit, and TOTP, which are accessible only to authorized users.

## Features

- User-based command permissions
- Supports pause, start, status, exit, and TOTP commands
- Implemented in Python using the `python-telegram-bot` library

## Setup

1. Replace `YOUR_BOT_TOKEN_HERE` in `bot.py` with your actual Telegram Bot API token.
2. Add your authorized Telegram user IDs in the `AUTHORIZED_USERS` list inside `bot.py`.
3. Install required Python dependencies:
4. pip install python-telegram-bot
5. Run the bot:
  python bot.py

## Usage

- The bot will only accept commands from authorized users.
- Authorized users can use commands such as `/start`, `/pause`, `/status`, `/exit`, and `/totp`.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

MIT License

---

Created by [Dinesh Kumar Mahanta]
