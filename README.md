# 🚀 REST API Service

![Go Version](https://img.shields.io/badge/Go-1.21%2B-blue)

Производительный REST API сервис на Go с поддержкой стандартных HTTP методов и JSON формата.

## 📌 Особенности

- ⚡ Высокая производительность благодаря Go
- 🔒 Поддержка JWT аутентификации
- 🗄️ Подключение к PostgreSQL/MySQL
- 📈 Готовые эндпоинты для CRUD операций

## 🏁 Быстрый старт

### Запуск через Docker
```bash
docker-compose up --build
Локальная установка
bash
git clone https://github.com/flizity/rest-api-service.git
cd rest-api-service
go mod tidy
go run main.go
Сервис будет доступен на http://localhost:8080

📚 Документация API
Доступные эндпоинты:

Метод	Путь	Описание
GET	/api/v1/health	Проверка здоровья сервиса
POST	/api/v1/auth	Аутентификация
GET	/api/v1/users	Получить список пользователей
POST	/api/v1/users	Создать нового пользователя
