# CaloryTrackerBot

CaloryTrackerBot — Telegram-бот для ведения дневника питания, настройки напоминаний и получения рекомендованных рецептов от LLM, разработанный в рамках проектной работы по курсу "Искусственный Интеллект в Инженерной деятельности".

## Технологии

- **AIOgram** — взаимодействие с Telegram API
- **SQLite + aiosqlite** — асинхронная работа с базой данных
- **APScheduler** — планирование отложенных задач
- **LangChain + GigaChat** — генерация рецептов на основе пользовательских запросов

## Быстрый старт

1. Клонировать репозиторий:

    ```bash
    git clone https://github.com/your-username/calorytrackerbot.git
    cd calorytrackerbot
    ```

2. Установить зависимости:

    ```bash
    pip install -r requirements.txt
    ```

3. Настроить переменные окружения:

    Создайте `.env` файл на основе `.env.example` и укажите необходимые токены и параметры модели.

4. Запустить бота:

    ```bash
    python main.py
    ```

## Требования

- Python 3.10+
- SQLite 3
- Установленные зависимости из `requirements.txt`

