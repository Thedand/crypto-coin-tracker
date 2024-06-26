## Crypto Tracker
![Crypto Tracker](/docs/index.jpg)

## Стек
- FastAPI + pydantic, pydantic-settings, aiohttp
- React + axios, ant design, tailwind


### Инструкции
- https://pro.coinmarketcap.com/ получить API_KEY
- создать .env и записать его (API_KEY="your-key")

#### Backend
- создаем вирутальное окружение `python3 -m venv venv`
- активация окружения под линукс `. venv/bin/activate` или под windows `.\venv\Scripts\activate.bat`
- зависимости `pip install -r req.txt`
- запуск `uvicorn src.main:app --reload` (обязательно находясь внутри папки backend)

#### Frontend
- `npm create vite@latest`
- `npm install`
- `npm run dev`
