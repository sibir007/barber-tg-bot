# BOT

## CREATE BOT in BotFather

## Project structure

```sh

```

## .env file

```txt
TOKEN=720000:AAG2000Aa70p6eotkKiMKJD_nwosSAfvg
ADMINS=00000000,000000001
PG_LINK=postgresql://USER_LOGIN:USER_PASSWORD@HOST_API:PORT/NAME_BD
```

## requirements.txt

```txt
asyncpg
aiogram
APScheduler
simple_py_config==0.0.1
aiosqlite==0.20.0
```

- `asyncpg`: Библиотека для асинхронного взаимодействия с PostgreSQL
- `aiogram`: Библиотека для создания телеграм-ботов
- `APScheduler`: Библиотека для планирования задач
- `python-decouple`: Библиотека для работы с `.env` файлами

## Install dependencies

```sh
pip install -r requirements.txt
```



