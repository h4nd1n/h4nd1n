# Проекты и экспертность

## Backend — FastAPI + Alembic + Docker + SQLAlchemy

### Domain-Driven Design & Unit of Work

[https://github.com/h4nd1n/RestAPI_example_DDD_UOW](https://github.com/h4nd1n/RestAPI_example_DDD_UOW)

Проект демонстрирует продвинутый подход к архитектуре backend-приложения:
- разделение ответственности и доменная модель (DDD),
- изолированная бизнес-логика, не зависящая от инфраструктуры,
- сервисный слой и репозитории,
- применение Unit of Work для управления транзакциями и обеспечения согласованности данных,
- использование SQLAlchemy и Alembic с заготовленными миграциями,
- полностью подготовленный к запуску проект в Docker Compose,
- покрытие тестами 99% кода,
- чёткая и расширяемая архитектура.

---

## Readlead — Frontend + Backend + CI/CD GitLab (В разработке)

Демонстрация проекта: https://readlead.ru (В разработке)

### Frontend — Django + TailwindCSS + Nginx + Docker + CI/CD

[https://github.com/h4nd1n/readlead-frontend](https://github.com/h4nd1n/readlead-frontend)
Django (шаблоны), TailwindCSS, интеграция с backend, Nginx в роли gateway, Docker Compose. Настроен CI/CD GitLab: деплой, сборка контейнеров, получение секретов из Vault и переменных из GitLab Variables.

### Backend — Django REST Framework + Redis + Docker + CI/CD

[https://github.com/h4nd1n/readlead-backend](https://github.com/h4nd1n/readlead-backend)
REST API на DRF, Redis для сессий, продакшен-ориентированная структура проекта, Docker Compose. Настроен CI/CD GitLab: сборка, тестирование, деплой, автоматическая загрузка секретов из Vault и переменных из GitLab Variables.
