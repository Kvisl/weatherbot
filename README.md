# WeatherBot

WeatherBot - это Telegram бот, который предоставляет актуальную информацию о погоде.


## Функционал:

- Получение текущей погоды по названию города.
- Вывод температуры, скорости ветра, влажности, давления и описания погоды.
- Использование emoji для наглядного представления погоды.


## Требования:

- Python 3.8+
- Библиотеки:
  - `aiogram`
  - `aiohttp`
  - `python-dotenv`
  - `logging`


## Установка:

1. Создайте бота в Telegram (@BotFather) и получите токен.

2. Зарегистрируйтесь на OpenWeatherMap (https://openweathermap.org/) и получите API ключ.

3. Создайте файл .env и добавьте следующие строки:

BOT_TOKEN=YOUR_BOT_TOKEN |
OPEN_WEATHER_TOKEN=YOUR_OPENWEATHER_TOKEN

4. Установите зависимости: pip install -r requirements.txt


## Использование:

- Запустите бота с помощью команды: python app.py
- Начните диалог с ботом /start.
- Введите название города.
- Бот выведет информацию о погоде в этом городе.