# SQL Agent Optimizer (Telegram + DeepSeek + n8n)

## Проблема и Решение

### AS IS


### TOBE


### Ожидаемый эффект


## Архитектура
Система использует 4+ инструмента:
1. Telegram Trigger: Вход пользователя.
2. DeepSeek API (Optimize): Оптимизация кода.
3. DeepSeek API (Review): Оценка оптимизированного кода.
4. Google Sheets: Хранение истории и логов.
5. Telegram Response: Отправка результата пользователю.

## Как запустить
Для локального использования необходимо:

1. Скачать n8n (Cloud или Local).
2. Импортировать файл [workflow.json](./workflow.json) через меню Import.
3. Настроить Credentials:
- В настройках n8n нужно создать Credentials для:
     - Telegram Bot (Token from @BotFather)
     - Google Sheets (OAuth или API Key)
     - DeepSeek API (API Key)
4. Запустить Workflow.

## Оценка качества

