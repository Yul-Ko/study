# Определение перспективного тарифа для телеком компании

## Описание

Клиентам компании предлагают два тарифных плана.  
Цель: понять, какой тариф приносит больше денег, чтобы скорректировать рекламный бюджет.  
Предоставлены данные 500 пользователей: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год.

В результате исследования проанализировали поведение клиентов оператора, исходя из выборки. Определили, сколько минут разговора, сколько сообщений и какой объём интернет-трафика требуется пользователям каждого тарифа в месяц.
Проверели гипотезы о том, что средняя выручка пользователей каждого из тарифов различается, и что средняя выручка пользователей из Москвы отличается от выручки пользователей из других регионов

<details>
  <summary>Данные</summary>

**Информация о пользователях:**

— уникальный идентификатор пользователя
— имя пользователя
— фамилия пользователя
— возраст пользователя (годы)
— дата подключения тарифа (день, месяц, год)
— дата прекращения пользования тарифом (если значение пропущено, то тариф ещё действовал на момент выгрузки данных)
— город проживания пользователя
— название тарифного плана

**Информация о звонках:**

— уникальный номер звонка
— дата звонка
— длительность звонка в минутах
— идентификатор пользователя, сделавшего звонок

**Информация о сообщениях:**

— уникальный номер сообщения
— дата сообщения
— идентификатор пользователя, отправившего сообщение

**Информация об интернет-сессиях:**

— уникальный номер сессии
— объём потраченного за сессию интернет-трафика (в мегабайтах)
— дата интернет-сессии
— идентификатор пользователя

**Информация о тарифах:**

— название тарифа
— ежемесячная абонентская плата в рублях
— количество минут разговора в месяц, включённых в абонентскую плату
— количество сообщений в месяц, включённых в абонентскую плату
— объём интернет-трафика, включённого в абонентскую плату (в мегабайтах)
— стоимость минуты разговора сверх тарифного пакета (например, если в тарифе 100 минут разговора в месяц, то со 101 минуты будет взиматься плата)
— стоимость отправки сообщения сверх тарифного пакета
— стоимость дополнительного гигабайта интернет-трафика сверх тарифного пакета (1 гигабайт = 1024 мегабайта)

</details>

## Используемые библиотеки
pandas
matplotlib
scipy.stats
numpy
