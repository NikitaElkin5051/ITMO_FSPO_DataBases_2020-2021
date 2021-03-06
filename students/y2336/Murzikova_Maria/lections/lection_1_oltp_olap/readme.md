Характеристики OLTP:

Преимущества:
относительная алгоритмическая простота,
поддержка большого числа пользователей;
малое время отклика на запрос;
относительно короткие запросами;
участие в запросах небольшого числа таблиц.

Недостатки:
Практически нет понимания аналитики данных.
В случае сбоя сервера транзакция может привести к задержкам, а в некоторых случаях - к потере данных.
Больше подвержены атакам хакеров.

Примеры: Oracle, SQLite, PostgreSQL, MySQL.



Характеристики OLAP:

Преимущества:
Единая платформа для анализа аналитики данных, поступающих из разных источников.
Данные из разных источников хранятся в централизованном месте, что облегчает доступ к большой информации.
Точные и быстрые вычисления.
Высокий уровень безопасности.

Недостатки:
Стоимость внедрения OLAP высока из-за лицензионного и дорогостоящего программного обеспечения.
Полный комплексный мониторинг, внедрение, модернизация систем OLAP зависят от ИТ-специалистов, которые специализируются в этой области.
Поскольку существует вероятность того, что для вставки данных из OLTP в системы OLAP задействовано более одной базы данных, поддержание соответствия всем командам БД может представлять проблему.

Примеры: Northwind, ClickHouse.
