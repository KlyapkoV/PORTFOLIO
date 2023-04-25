<h1 align="center">ПОДГОТОВКА ДАННЫХ ДЛЯ АНАЛИЗА ПРОДАЖ В МАГАЗИНАХ ПРОКАТА DVD</h1>


<p align="center">
  <img src="https://github.com/KlyapkoV/PORTFOLIO/blob/main/images/logo-DVD_RENTAL_STORE.png?raw=true">
</p>


## **ИСПОЛЬЗУЕМАЯ СУБД:**
**PostgreSQL**

## **ОБЪЕКТЫ БАЗЫ ДАННЫХ:**
> - **15 таблиц**
> - **13 последовательностей**
> - **8 функций**
> - **7 представлений**
> - **1 триггер**
> - **1 домен**

## **ОПИСАНИЕ ТАБЛИЦ БАЗЫ ДАННЫХ:**
<table>
<thead>
<tr>
<th>Таблица</th>
<th style="text-align:left">Описание</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>actor</strong></td>
<td style="text-align:left">данные об актеров (включая имя и фамилию)</td>
</tr>
<tr>
<td><strong>film</strong></td>
<td style="text-align:left">данные о фильме (название, год выпуска, продолжительность, рейтинг и т.д.)</td>
</tr>
<tr>
<td><strong>film_actor</strong></td>
<td style="text-align:left">взаимосвязи между фильмами и актёрами</td>
</tr>
<tr>
<td><strong>category</strong></td>
<td style="text-align:left">данные о категориях фильма</td>
</tr>
<tr>
<td><strong>language</strong></td>
<td style="text-align:left">языки фильмов</td>
</tr>
<tr>
<td><strong>film_category</strong></td>
<td style="text-align:left">взаимосвязи между фильмами и категориями</td>
</tr>
<tr>
<td><strong>store</strong></td>
<td style="text-align:left">сведения о магазине (включая персонал, менеджера и адрес)</td>
</tr>
<tr>
<td><strong>inventory</strong></td>
<td style="text-align:left">данные по инвентаризации</td>
</tr>
<tr>
<td><strong>rental</strong></td>
<td style="text-align:left">данные об аренде</td>
</tr>
<tr>
<td><strong>payment</strong></td>
<td style="text-align:left">данные о платежах клиента</td>
</tr>
<tr>
<td><strong>staff</strong></td>
<td style="text-align:left">данные о персонале</td>
</tr>
<tr>
<td><strong>customer</strong></td>
<td style="text-align:left">данные о клиенте</td>
</tr>
<tr>
<td><strong>address</strong></td>
<td style="text-align:left">адреса персонала и клиентов</td>
</tr>
<tr>
<td><strong>city</strong></td>
<td style="text-align:left">названия городов</td>
</tr>
<tr>
<td><strong>country</strong></td>
<td style="text-align:left">названия стран</td>
</tr>
</tbody>
</table>


&nbsp;

# **РАЗВЁРТЫВАНИЕ БАЗЫ ДАННЫХ**:
- ## [Инструкция по развёртыванию базы данных](https://www.postgresqltutorial.com/postgresql-getting-started/load-postgresql-sample-database)
- ## [Архив с файлами для развёртывания базы данных](https://github.com/KlyapkoV/DVD_RENTAL_STORE/blob/main/dvdrental.zip)
- ## [ER-диаграмма](https://github.com/KlyapkoV/DVD_RENTAL_STORE/blob/main/ER-diagram.pdf)

&nbsp;

# [ТЕХНИЧЕСКОЕ ЗАДАНИЕ](https://github.com/KlyapkoV/DVD_RENTAL_STORE/blob/main/tz-DVD_RENTAL_STORE.pdf)

&nbsp;

# [SQL-СКРИПТ ВЫПОЛНЕНИЯ ТЕХНИЧЕСКОГО ЗАДАНИЯ](https://github.com/KlyapkoV/DVD_RENTAL_STORE/blob/main/script.sql)