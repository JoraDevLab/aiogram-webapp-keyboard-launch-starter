# Telegram WebApp Starter

Example application with minimal required code to launch Telegram WebApp with aiogram and vanilla js

## Installation

Run command to install required python libraries

    pip install -r requirements.txt

## UI static server

To local run launch static server to serve webapp html page using commands

    cd ./static
    python -m http.server 3000

Use port forwarding over any utils to get public https url

## Configuration

Copy `.env.sample` to `.env` and fill your public https url and bot token

```
BOT_TOKEN=...
WEB_APP_URL=https://...
```

## Run bot

Start bot using

    python web_app_bot.py
