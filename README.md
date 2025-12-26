# Instagram Video Yuklovchi Bot

Telegram bot Instagram Reels, Post va IGTV videolarini tez yuklab beradi.

## Xususiyatlari
- Public va private videolar (cookies bilan)
- Tez yuklash
- Oddiy video ko‘rinishda jo‘natadi

## O‘rnatish
```bash
git clone https://github.com/timatojiyev/telegram-bot.git
cd telegram-bot
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env  # BOT_TOKEN va cookies qo‘shing
python bot.py
