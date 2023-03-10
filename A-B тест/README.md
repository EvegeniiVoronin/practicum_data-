# Проверка гипотез по увеличению выручки в интернет-магазине —
оценить результаты A/B теста


## Данные

Файл hypothesis.csv:

Hypothesis — краткое описание гипотезы;
Reach — охват пользователей по 10-балльной шкале;
Impact — влияние на пользователей по 10-балльной шкале;
Confidence — уверенность в гипотезе по 10-балльной шкале;
Efforts — затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы.
Файл orders.csv:

transactionId — идентификатор заказа;
visitorId — идентификатор пользователя, совершившего заказ;
date — дата, когда был совершён заказ;
revenue — выручка заказа;
group — группа A/B-теста, в которую попал заказ.
Файл visitors.csv:

date — дата;
group — группа A/B-теста;
visitors — количество пользователей в указанную дату в указанной группе A/B-теста

## Задача

Применим фреймворк ICE для приоритизации гипотез. Отсортируем их по убыванию приоритета.
Применим фреймворк RICE для приоритизации гипотез. Отсортируем их по убыванию приоритета.
Укажим, как изменилась приоритизация гипотез при применении RICE вместо ICE. Объясним, почему так произошло.
Проанализируем A/B-тест

## Используемые библиотеки
Python, Pandas, Matplotlib, SciPy, A/B-тестирование, проверка статистических гипотез

