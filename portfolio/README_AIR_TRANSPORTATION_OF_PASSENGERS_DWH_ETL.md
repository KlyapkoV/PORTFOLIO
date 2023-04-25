<h1 align="center">СОЗДАНИЕ DWH ДЛЯ АНАЛИЗА АВИАПЕРЕВОЗОК ПАССАЖИРОВ. ОРГАНИЗАЦИЯ ETL-ПРОЦЕССОВ </h1>


<img src="https://github.com/KlyapkoV/PORTFOLIO/blob/main/images/logo-AIR_TRANSPORTATION_OF_PASSENGERS_DWH_ETL.jpg?raw=true"/>


## **ЦЕЛИ ПРОЕКТА:**
> - Спроектировать структурированное хранилище данных
>
> - Организовать процесс извлечения данных из внешнего источника
>
> - Организовать процесс трансформации извлечённых данных
>
> - Организовать процесс загрузки преобразованных данных


## **ЗАДАЧИ ПРОЕКТА:**
> - Создать чистую базу данных с таблицами фактов и измерений
>
> - Обогатить созданную базу сущностями из демонстрационной базы данных demo.bookings при помощи ETL-процессов
>
> - Для каждой таблицы в хранилище, необходимо реализовать несколько проверок качества данных


&nbsp;
# [ДОКУМЕНТАЦИЯ](https://github.com/KlyapkoV/AIR_TRANSPORTATION_OF_PASSENGERS_DWH_ETL/blob/main/doc-AIR_TRANSPORTATION_OF_PASSENGERS_DWH_ETL.pdf)


&nbsp;
# **ФАЙЛЫ ПРОЕКТА**:

## [SQL-скрипт для создания таблиц фактов и измерений (включая запрос на обогащение таблицы dim_calendar)](AIR_TRANSPORTATION_OF_PASSENGERS_DWH_ETL/script.sql)
## [SQL-скрипт для поднятия демонстрационной БД](https://github.com/KlyapkoV/AIR_TRANSPORTATION_OF_PASSENGERS_DWH_ETL/blob/main/demo_small.sql)
## [SQL-скрипт для трансформации данных о тарифах и таблицы фактов из внешнего источника](https://github.com/KlyapkoV/AIR_TRANSPORTATION_OF_PASSENGERS_DWH_ETL/blob/main/script_(tarriff%20and%20fact).sql)
## [ETL-процесс обогащения таблицы dim_aircrafts](https://github.com/KlyapkoV/AIR_TRANSPORTATION_OF_PASSENGERS_DWH_ETL/blob/main/ETL_aircrafts.ktr)
## [ETL-процесс обогащения таблицы dim_airports](https://github.com/KlyapkoV/AIR_TRANSPORTATION_OF_PASSENGERS_DWH_ETL/blob/main/ETL_airports.ktr)
## [ETL-процесс обогащения таблицы dim_passengers](https://github.com/KlyapkoV/AIR_TRANSPORTATION_OF_PASSENGERS_DWH_ETL/blob/main/ETL_passengers.ktr)
## [ETL-процесс обогащения таблицы dim_tariff](https://github.com/KlyapkoV/AIR_TRANSPORTATION_OF_PASSENGERS_DWH_ETL/blob/main/ETL_tariff.ktr)
## [ETL-процесс обогащения таблицы fact_flights](https://github.com/KlyapkoV/AIR_TRANSPORTATION_OF_PASSENGERS_DWH_ETL/blob/main/ETL_fact_flights.ktr)