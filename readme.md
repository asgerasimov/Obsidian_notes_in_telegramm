# Notes Telegram Bot

Бот для работы с заметками Obsidian через n8n.

## Локальный запуск
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env  # заполнить значения
python -m bot.app
