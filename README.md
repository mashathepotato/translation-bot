# 🤖 бабушка-бот (grandma-bot)

A Telegram bot built entirely because typing in Russian on a laptop keyboard is slow and exhausting.

## The Problem

You are in a family group chat. You want to send a message. You type in English because switching keyboards mid-thought is a crime against productivity. Your grandma, a woman of culture who has never once needed English, stares at the message like it personally offended her.

## The Solution

This bot. Grandma replies to the offending English message, types `!переведи`, and the bot does the rest. That's it. That's the whole thing.

## Usage

1. Grandma sees an English message
2. Grandma replies to it with `!переведи`
3. Bot translates it to Russian
4. Grandma reads it
5. Family harmony restored

No buttons. No menus. No app to download. Just `!переведи`.

## Setup (for the one person running this)

```bash
pip3 install -r requirements.txt
python3 bot.py
```

Requires a `.env` file with `TELEGRAM_BOT_TOKEN` and `ANTHROPIC_API_KEY`. See `.env.example`.

## Tech

- Python + [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)
- Claude Haiku (Anthropic) for translation
- Love for grandma
