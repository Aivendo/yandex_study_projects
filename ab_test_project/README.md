# Анализ А/В теста

## Данные

Датасеты содержат данные о пользователях, действиях пользователей, маркетинговых событиях и участниках тестов

Датасет `final_ab_events.csv` (действия новых пользователей в период с 7.12.2020 по 4.01.2021 года) содержит данные:
- идентификатор пользователя;
- дата и время покупки;
- тип события;
- дополнительные данные о событии.

Датасет `final_ab_marketing_events.csv` (календарь маркетинговых событий на 2020 год) содержит данные:
- название маркетингового события;
- регионы, в которых будет проводиться рекламная кампания;
- дата начала кампании;
- дата завершения кампании.

Датасет `final_ab_new_users.csv` (пользователи, зарегистрировавшиеся с 7 по 21 декабря 2020 года), содержит данные:

- идентификатор пользователя;
- дата регистрации;
- регион пользователя;
- устройство, с которого происходила регистрация.

Датасет `final_ab_participants.csv` (таблица участников тестов), содержит данные:

- идентификатор пользователя;
- название теста;
- группа пользователя.

## Задача

Задача — провести оценку результатов A/B-теста.

- Оценить корректность проведения теста:
- Проанализировать результаты теста

## Краткий вывод по исследованию

- Низкое качество теста (не выполнены условия ТЗ на проведение теста), результаты не заслуживают доверия;
- Ожидаемый эффект улучшения метрик конверсии: в просмотр карточек товаров, в просмотр корзины, в покупку - по результатам теста не оправдался.

## Используемые библиотеки
*pandas*, *matplotlib*, *plotly*, *seaborn*, *numpy*, *math*, *scipy*
