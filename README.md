# Абрамов Сергей- «Работа с данными (DDL/DML)»

---

### Задание 1


1.1. Поднимите чистый инстанс MySQL версии 8.0+. Можно использовать локальный сервер или контейнер Docker.

1.2. Создайте учётную запись sys_temp.

1.3. Выполните запрос на получение списка пользователей в базе данных. (скриншот)

1.4. Дайте все права для пользователя sys_temp.

1.5. Выполните запрос на получение списка прав для пользователя sys_temp. (скриншот)

1.6. Переподключитесь к базе данных от имени sys_temp.

Для смены типа аутентификации с sha2 используйте запрос:

ALTER USER 'sys_test'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';
1.6. По ссылке https://downloads.mysql.com/docs/sakila-db.zip скачайте дамп базы данных.

1.7. Восстановите дамп в базу данных.

1.8. При работе в IDE сформируйте ER-диаграмму получившейся базы данных. При работе в командной строке используйте команду для получения всех таблиц базы данных. (скриншот)

Результатом работы должны быть скриншоты обозначенных заданий, а также простыня со всеми запросами.

---

![mysql1](https://github.com/smabramov/DDL-DML/blob/857a91bf98c5fc478f42a6a7106fde528b1c5fde/jpg/mysql1.jpg)


![mysql](https://github.com/smabramov/DDL-DML/blob/857a91bf98c5fc478f42a6a7106fde528b1c5fde/jpg/mysql.jpg)


![mysql_user](https://github.com/smabramov/DDL-DML/blob/857a91bf98c5fc478f42a6a7106fde528b1c5fde/jpg/mysql_user.jpg)


![mysql_user1](https://github.com/smabramov/DDL-DML/blob/857a91bf98c5fc478f42a6a7106fde528b1c5fde/jpg/mysql_user1.jpg)


![mysql2](https://github.com/smabramov/DDL-DML/blob/857a91bf98c5fc478f42a6a7106fde528b1c5fde/jpg/mysql2.jpg)


![mysql3](https://github.com/smabramov/DDL-DML/blob/857a91bf98c5fc478f42a6a7106fde528b1c5fde/jpg/mysql3.jpg)


'''

mysql -u sys_temp -p


SHOW DATABASE;


USE sakila;


SHOW TABLES;


'''





---


### Задание 2

Составьте таблицу, используя любой текстовый редактор или Excel, в которой должно быть два столбца: в первом должны быть названия таблиц восстановленной базы, во втором названия первичных ключей этих таблиц. Пример: (скриншот/текст)

![mysql5](https://github.com/smabramov/DDL-DML/blob/1c1ee7c8bddea9aa425097e6e25faf024b3cafd6/jpg/mysql5.jpg)