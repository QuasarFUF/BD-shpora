# BD-shpora
1. Подключение к базе данных:

mysql -u username -p


 2. Выбор базы данных:

USE database_name;


 3. Просмотр всех баз данных:

SHOW DATABASES;


 4. Создание новой базы данных:

CREATE DATABASE database_name;


 5. Удаление базы данных:

DROP DATABASE database_name;


 6. Просмотр таблиц в базе данных:

SHOW TABLES;


 7. Создание новой таблицы:

CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    ...
);


 8. Просмотр структуры таблицы:

DESCRIBE table_name;


 9. Удаление таблицы:

DROP TABLE table_name;


 10. Вставка данных в таблицу:

INSERT INTO table_name (column1, column2, ...) VALUES (value1, value2, ...);


 11. Выборка данных из таблицы:

SELECT * FROM table_name;


 12. Обновление данных:

UPDATE table_name SET column1 = value1, column2 = value2 WHERE condition;


 13. Удаление данных:

DELETE FROM table_name WHERE condition;


 14. Добавление нового столбца в таблицу:

ALTER TABLE table_name ADD column_name datatype;


 15. Удаление столбца из таблицы:

ALTER TABLE table_name DROP COLUMN column_name;


 16. Создание индекса:

CREATE INDEX index_name ON table_name (column_name);


 17. Удаление индекса:

DROP INDEX index_name ON table_name;


 18. Выход из MySQL:

EXIT;
