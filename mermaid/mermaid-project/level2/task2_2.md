# 2.2
```mermaid
    gantt
        title Разработка мобильного приложения
        dateFormat  YYYY-MM-DD
        section Подготовка
        Подготовка :done, prep, 2025-04-01, 5d
        section Дизайн
        Дизайн :design, after prep, 7d
        section Разработка
        Фронтенд :frontend, after design, 10d
        Бэкенд :backend, after prep, 12d
        section Тестирование
        Тестирование :test, after frontend, 5d
```