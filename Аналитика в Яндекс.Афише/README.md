# Аналитика в Яндекс.Афише

## Описание
 План оптимизации маркетинговых затрат на основе данных за период с июня 2017 по конец мая 2018г.
 
 В результате исследования определили, как люди пользуются продуктом, когда начинают покупать, сколько денег приносит каждый клиент, когда он окупается, а также рекламные расходы. Выполнен когортный анализ, посчитаны retation rate, средний чек, ltv, romi. Даны рекомендации относительно маркетинговых источников

<details>
 <summary>Данные</summary>

**Лог сервера с информацией о посещениях сайта:**

— уникальный идентификатор пользователя
— категория устройства пользователя
— дата и время начала сессии
— дата и время окончания сессии
— идентификатор рекламного источника, из которого пришел пользователь

**Информация о заказах:**

— уникальный id пользователя, который сделал заказ
— дата и время заказа
— выручка Яндекс.Афиши с этого заказа

**Информация о затратах на маркетинг:**

— идентификатор рекламного источника
— дата
— затраты на этот рекламный источник в этот день

</details>

## Используемые библиотеки
pandas
matplotlib
seaborn
numpy
