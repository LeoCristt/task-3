
# 🛒 Task-3 Frontend Mirea

> Простое приложение для панели администратора интернет-магазина.

## 📁 Структура проекта
```plaintext
├── backend/              # API сервер на Express.js
│   ├── data/             # Файлы с данными (имитация БД)
│   │   ├── products.json # Список товаров
│   ├── routes/           # Эндпоинты API
│   │   ├── products.js   # Роуты для товаров
│   │   ├── categories.js # Роуты для категорий
│   ├── server.js         # Запуск сервера API
├── frontend/             # Клиентский сервер (Express.js)
│   ├── public/           # Статические файлы (HTML, CSS)
│       ├── index.html    # Страница с товарами
│   ├── server.js         # Сервер для отдачи index.html
├── README.md             # Инструкция по запуску
```

# 🚀 Установка и запуск

## 🔧 1. Запуск Backend API
```sh
cd backend
npm install  # Установка зависимостей
node server.js  # Запуск API-сервера
```
## API будет доступно по адресу: http://localhost:3000

## 🔧 1. Запуск Backend API
```sh
cd backend
npm install  # Установка зависимостей
node server.js  # Запуск клиентского сервера
```
## API будет доступно по адресу: http://localhost:8080

# 📌 API эндпоинты
## 🔹 Товары
  * GET /api/products – Получить список всех товаров
  * GET /api/products/:id – Получить товар по ID
  * GET /api/products/category/:categoryId – Получить товары по категории
## 🔹 Категории
  * GET /api/categories – Получить список всех категорий
