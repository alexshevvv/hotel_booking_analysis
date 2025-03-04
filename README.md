# 🏨 Анализ данных о бронированиях в отелях

## Описание проекта
Этот проект направлен на анализ данных о бронированиях в отелях. Датасет содержит информацию о типах отелей, статусах бронирования, сроках проживания, числе гостей и других параметрах, влияющих на заполняемость отелей и поведение клиентов.

## 📋 Данные
Каждая строка в датасете представляет одно бронирование и включает множество характеристик.

### Основные колонки:
- **Hotel** – тип отеля (City Hotel или Resort Hotel)
- **Is canceled** – бронирование было отменено (1) или нет (0)
- **Lead time** – количество дней между бронированием и датой прибытия
- **Arrival full date** – полная дата прибытия
- **Arrival date year** – год прибытия
- **Arrival date month** – месяц прибытия
- **Arrival date week number** – номер недели прибытия
- **Arrival date day of month** – день прибытия
- **Stays in weekend nights** – число выходных ночей в бронировании
- **Stays in week nights** – число будних ночей в бронировании
- **Stays total nights** – общее число ночей (выходные + будни)
- **Adults** – количество взрослых гостей
- **Children** – количество детей
- **Babies** – количество младенцев
- **Meal** – выбранный тип питания
- **Country** – страна происхождения клиента
- **Reserved room type** – забронированный тип номера
- **Assigned room type** – полученный тип номера
- **Customer type** – тип клиента
- **Reservation status** – статус брони (Canceled, Check-Out, No-Show)
- **Reservation status date** – дата обновления статуса

## 📊 Цели анализа
- Исследование динамики бронирований по времени
- Анализ факторов, влияющих на отмену бронирований
- Определение зависимости между типами номеров и получаемыми номерами
- Оценка влияния количества гостей на продолжительность пребывания
- Выявление особенностей клиентов в зависимости от страны

## 💪 Навыки, отрабатываемые в проекте
- Работа с **pandas** (обработка и анализ данных)
- Анализ временных данных и бронирований
- Исследовательский анализ данных (EDA)
- Работа с метрикой Churn Rate

## 🛠 Используемые технологии
- **Python** (pandas, numpy)
- **Jupyter Notebook**

## 🏆 Итог
Анализ бронирований позволяет понять ключевые тенденции и факторы, влияющие на заполняемость отелей, поведение клиентов и частоту отмен бронирований.
