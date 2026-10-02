# Laundry Status Tracker

Веб-приложение для сервиса химчистки и клининговых услуг с отслеживанием статуса заказа в реальном времени.

## Технологический стек
- **Backend:** Node.js, Express, PostgreSQL, JWT
- **Frontend:** React, Axios, React Router
- **Тестирование:** Jest, Supertest, React Testing Library
- **CI/CD:** GitHub Actions

## Быстрый старт
### Предварительные требования
- Node.js >= 18
- PostgreSQL >= 14

### Установка
1. Клонировать репозиторий: `git clone https://github.com/username/laundry-status-tracker.git`
2. Установить зависимости: `npm install` (в корне, client/ и server/)
3. Скопировать `.env.example` → `.env` и заполнить переменные
4. Запустить миграции: `npm run migrate`
5. Запустить dev-сервер: `npm run dev`

## Структура проекта
- `client/` — SPA на React
- `server/` — REST API на Express
- `docs/` — проектная документация
- `tests/` — интеграционные и юнит-тесты

## Переменные окружения
| Переменная | Описание |
|-----------|----------|
| `DB_HOST` | Хост PostgreSQL |
| `DB_PORT` | Порт PostgreSQL |
| `JWT_SECRET` | Секретный ключ для JWT |
| `API_URL` | Базовый URL API |

## Лицензия
MIT
