# AI Telegram Bot

A Telegram bot focused on AI-powered conversations and automation using Google Gemini.

## Requirements

- Python 3
- Telegram bot token
- Google Gemini API credentials when required by the configuration

## Installation

```bash
git clone https://github.com/ryoaonetsuki/gemini-telegram-bot.git
cd gemini-telegram-bot
```

If `requirements.txt` is present:

```bash
pip install -r requirements.txt
```

## Configuration

Set the Telegram token and Gemini credentials using the environment variables or configuration method expected by the source code.

Never commit real tokens or API keys.

## Run

Start the Python entry-point script provided by the repository. Check the source files for the current entry point before running the bot.

## Development

Test the bot in a private chat first, then configure group permissions if needed.

## Security

Treat bot tokens and API keys as passwords. Rotate credentials immediately if they are exposed.
