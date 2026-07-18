# Александр Шалухо

**Python-разработчик** · Москва  
Эксперт по налогообложению банков с 20-летним опытом в учёте и налогах и 15+ летним опытом руководства — сейчас развиваю карьеру в backend-разработке на Python.

📧 [aleksandr@shaluho.ru](mailto:aleksandr@shaluho.ru) · 🔗 [github.com/AleksandrShaluho](https://github.com/AleksandrShaluho)

---

## О себе

Совмещаю предметную экспертизу в финтехе и практические навыки разработки. Руководил ИТ-проектами (в том числе внедрением витрины налогового мониторинга в банке), пишу и деплою Python-скрипты и Streamlit-приложения для автоматизации ежедневной обработки данных на корпоративной платформе.

Завершил курс **«Python-разработчик»** в Яндекс Практикуме: REST API, Django/DRF, FastAPI, Flask, PostgreSQL, Docker, CI/CD.

**Ищу:** позицию Junior / Junior+ Python Backend Developer (Django / FastAPI), в том числе в командах, где ценят доменную экспертизу в финансах и налогах.

---

## Стек

| Область | Технологии |
|--------|------------|
| Backend | Python, Django, Django REST Framework, FastAPI, Flask, SQLAlchemy |
| БД | PostgreSQL, SQLite |
| Data / UI | pandas, Streamlit |
| Инфраструктура | Docker, Docker Compose, Nginx, Git, GitHub Actions (CI/CD) |
| Дополнительно | JWT / Token auth, Redis, Celery, Alembic, BeautifulSoup, Scrapy |

```text
Django · DRF · FastAPI · Flask · SQLAlchemy · PostgreSQL · Docker · GitHub Actions
```

---

## Портфолио

### FoodGram — сервис рецептов и кулинарных блогов

Полноценный backend на **Django REST Framework** + готовый React-фронтенд курса. Реализованы пользователи и подписки, рецепты, избранное, список попок, фильтры и пагинация. Деплой на сервер: **Docker**, **Nginx**, **GitHub Actions**.

- Стек: Django, DRF, Djoser, PostgreSQL, React, Docker, Nginx, GitHub Actions  
- Репозиторий: [AleksandrShaluho/foodgram](https://github.com/AleksandrShaluho/foodgram)  
- Демо: [foodgram.neverhood.ru.net](https://foodgram.neverhood.ru.net) · [API docs](https://foodgram.neverhood.ru.net/api/docs/)

### BookingSeats — API бронирования мест в кафе *(командный проект)*

Финальный командный проект Яндекс Практикума (команда 4, поток 68–69). REST API на **FastAPI** для сети кафе: заведения, столы, слоты, меню, акции, бронирования с предзаказом, JWT, Redis, Celery.

**Мой вклад:**
- централизованное логирование (Loguru, единый формат HTTP/Celery);
- обработка ошибок в приложении;
- три фичи сквозь все слои: models → crud → services → endpoints;
- итоговый рефакторинг кода всего приложения.

> Код пока не публикую в личном аккаунте — ожидаю разрешение команды. Описание — по согласованию с командой; стек: FastAPI, SQLAlchemy 2 (async), PostgreSQL, Redis, Celery, RabbitMQ, Docker, GitHub Actions.

### Kittygram — веб-приложение для любителей котиков

Аналог соцсети для фото котиков: регистрация, карточки питомцев, лента, подписки. Backend на Django/DRF, деплой через Docker и CI/CD.

- Стек: Django, DRF, PostgreSQL, Docker, Gunicorn, GitHub Actions  
- Репозиторий: [AleksandrShaluho/kittygram_final](https://github.com/AleksandrShaluho/kittygram_final)

### YaMDB — API отзывов на произведения

RESTful API на DRF: произведения, отзывы, комментарии, рейтинги, роли пользователей, JWT, импорт из CSV, документация OpenAPI/Redoc.

- Стек: Django, DRF, Simple JWT, PostgreSQL/SQLite  
- Репозиторий: [AleksandrShaluho/api-yamdb](https://github.com/AleksandrShaluho/api-yamdb)

### QRKot — API благотворительного фонда

FastAPI-сервис для целевых сборов и пожертвований: CRUD проектов и донатов, автоматическое закрытие целей. Расширенная версия — выгрузка отчёта в Google Sheets (xlsx).

- Стек: FastAPI, SQLAlchemy, Alembic, Pydantic, SQLite/PostgreSQL, Google API  
- Репозитории: [cat-charity-2](https://github.com/AleksandrShaluho/cat-charity-2) · [QRkot-spreadsheets](https://github.com/AleksandrShaluho/QRkot-spreadsheets)

### Yacut — сервис коротких ссылок

Flask-приложение: короткие URL (авто и кастомные), API, загрузка файлов на Яндекс Диск с генерацией короткой ссылки.

- Стек: Flask, SQLAlchemy, WTForms, Yandex Disk API  
- Репозиторий: [AleksandrShaluho/async-yacut](https://github.com/AleksandrShaluho/async-yacut)

### Yatube API — API социальной сети

API блога: посты, комментарии, группы, подписки, JWT-аутентификация, OpenAPI/Redoc.

- Стек: Django, DRF, Simple JWT  
- Репозиторий: [AleksandrShaluho/api-final-yatube](https://github.com/AleksandrShaluho/api-final-yatube)

### Парсеры документации Python / PEP

Скрипты сбора и анализа статусов PEP и версий Python с python.org: вывод в терминал и CSV.

- BeautifulSoup: [bs4_parser_pep](https://github.com/AleksandrShaluho/bs4_parser_pep)  
- Scrapy: [scrapy_parser_pep](https://github.com/AleksandrShaluho/scrapy_parser_pep)

### Homework Bot — Telegram-бот статуса домашней работы

Бот проверяет статус проверки домашней работы через API Практикума и присылает уведомления в Telegram.

- Стек: Python, python-telegram-bot / requests  
- Репозиторий: [AleksandrShaluho/homework-bot](https://github.com/AleksandrShaluho/homework-bot)

### Taski — деплой Django/React приложения

Практика контейнеризации и деплоя: Docker Compose, Nginx, GitHub Actions.

- Репозиторий: [AleksandrShaluho/taski-docker](https://github.com/AleksandrShaluho/taski-docker)

---

## Опыт вне учебных проектов

- **Налоговый мониторинг в банке** — руководство проектом внедрения витрины налогового мониторинга (взаимодействие бизнеса, ИТ и подрядчиков).
- **Автоматизация на Python** — разработка и деплой скриптов и Streamlit-приложений на корпоративной платформе для рутинной обработки данных (pandas, отчёты, ежедневные пайплайны).
- **Управленческий опыт** — 15+ лет руководства командами и процессами в области бухгалтерского учёта и налогообложения банков.

---

## Чем могу быть полезен

- Backend на **Django / DRF** и **FastAPI**: модели, API, auth, валидация, слоистая архитектура  
- Работа с **PostgreSQL**, миграции, базовый SQL  
- **Docker** и простой **CI/CD** (GitHub Actions)  
- Автоматизация отчётности и данных (**pandas**, **Streamlit**)  
- Понимание банковских и налоговых процессов — быстрее вхожу в финтех-задачи

---

## Контакты

- Email: [aleksandr@shaluho.ru](mailto:aleksandr@shaluho.ru)  
- GitHub: [AleksandrShaluho](https://github.com/AleksandrShaluho)

Открыт к предложениям о работе и стажировкам в Python backend.
