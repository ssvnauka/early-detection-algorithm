# Алгоритм раннего выявления рака желудка

**Версия:** 1.0  
**Последнее обновление:** `10 января 2025`  

## 📋 Описание
Этот проект представляет алгоритм раннего выявления рака желудка, основанный на современных данных о молекулярных биомаркерах и методах диагностики.

## 📊 Диаграмма алгоритма
```mermaid
graph TD
    A[Оценка факторов риска] --> B{Высокий риск?}
    B -- Нет --> C[Мониторинг раз в 3 года]
    B -- Да --> D[Гастроскопия]
    D --> E{Результаты нормальны?}
    E -- Да --> F[Повтор через 12 месяцев]
    E -- Нет --> G[Биопсия + Маркеры]
    G --> H{Рак подтвержден?}
    H -- Да --> I[Терапия и наблюдение]
    H -- Нет --> J[Повторное обследование через 6 мес]
