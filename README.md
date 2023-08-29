# Bankist

— это крошечное приложение, имитирующее функции вымышленного онлайн-банка

Проект закончен: 08.01.2023

## Данные для входа

Приложение без бэкенда, так что для входа необходимо использовать следующие данные:

### Аккаунт 1

- Логин: js
- Пароль: 1111

### Аккаунт 2

- Логин: jd
- Пароль: 2222

### Аккаунт 3

- Логин: ii
- Пароль: 3333

## Возможности

### Transfer money

Перевод денег на счет другого аккаунта из списка выше.

### Request loan

Заем денег. Будет одобрен, если в истории хотя бы 1 начисление >= 10% запрашиваемой суммы.

### Close account

Удаление аккаунта. Все аккаунты восстанавливаются при обновлении страницы.

### Другое

- Сортировка истории переводов по убыванию суммы
- Ограничение сессии 10 минут (таймер справа внизу)
- Конвертация переведенной суммы с помощью https://www.exchangerate-api.com/

## Зачем?

Приложение было сделано в рамках обучающего курса для тренировки:

- работы с методами массивов
- манипуляций с DOM (создание, сортировка элементов, инпуты)
- форматирования дат и чисел в соответствии с локалью
- работы с таймерами
