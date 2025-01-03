# Ethiopian Airlines Telegram Bot

This bot searches Ethiopian Airlines flights and is deployed on Render.

## Setup

1. Clone this repository.
2. Install dependencies locally using:
   ```bash
   pip install -r requirements.txt
   ```
3. Ensure you have ChromeDriver available in the same directory as `bot.py`.
4. Deploy on Render by connecting this repository.

## Environment Variables

Set the following environment variable in Render:
- `TELEGRAM_BOT_TOKEN`: Your bot token from BotFather.

## Deployment on Render

1. Login to [Render](https://render.com/).
2. Create a new **Web Service** and link your repository.
3. Set the start command to `python bot.py`.
4. Add the environment variable for your bot token.

The bot will now run continuously on Render.
