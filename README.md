
# RESTful Booker Testing Project

## 👋 О проекте

Этот репозиторий — результат изучения REST‑API демо‑сервиса [Restful Booker](https://restful-booker.herokuapp.com/apidoc/index.html).
Цель — продемонстрировать навыки функционального тестирования REST‑сервисов:

* Составлены **позитивные** и **негативные** тест‑кейсы для ключевых эндпоинтов.
* Реализована **Postman‑коллекция** для проверки этих кейсов.
* Выявлены дефекты, оформлены в удобный **bug‑report**.

---

## 📁 Структура репозитория

```
├─ docs/
│  ├─ bug_reports.md           # Сформированные баг‑репорты (Markdown)
│  └─ test_cases.csv           # Тест‑кейсы (включая позитивные и негативные проверки)
├─ restful-booker.postman_collection.json  # Экспортированная Postman‑коллекция
├─ README.md                    # Это описание
├─ test_task.md                 # Описание тестового задания для этого проекта
```

---

## ⚡️ Содержимое

### ✅ Тестовые кейсы

* Ключевые проверки для REST‑эндпоинтов:

  * `/auth` (POST) — получение токена
  * `/booking` (POST) — создание записи
  * `/booking` (GET) — фильтрация данных
  * `/booking/{id}` (GET, PUT, PATCH, DELETE) — проверки чтения, изменения и удаления записи
  * `/ping` (GET) — проверка доступности API
* Тесты содержат как **позитивные**, так и **негативные** проверки.

### 🐞 Баг‑репорты

Документы содержат:

* **Шаги воспроизведения**
* **Ожидаемый результат**
* **Фактический результат**
* Приоритет дефекта




