# DBMS
Задания для курс <a href="https://drive.google.com/drive/u/0/folders/182vmNG-TDAes4UvmkJnkQk2ThDv-G5E5" target="_blank">"Разработка приложений СУБД 2022"</a> 

# Домашнее задание 1
1. Cоставление требований к приложению
<a href="https://drive.google.com/file/d/1nd3jhUrFS1IX3WLur3NINuo8_gzGILmN/view?usp=sharing" target="_blank">ТЗ библиотеки</a> 

# Домашнее задание 2
2.1 Определите структуру таблиц EMP и DEPT в демонстрационной базе ORACLE (при помощи Object Browser).

2.2 Напишите запрос, выдающий должности сотрудников из таблицы EMP (используйте SQL Commands - но сделать полный скрипт ;)).

2.3 Запросы:

     Сколько сотрудников в каждом из департаментов?
     Какая средняя зарплата по каждой должности?
     Какова минимальная и максимальная зарплата по каждой должности?
     Определите суммарную зарплату по каждому  департаменту.

2.4 Сформируйте все возможные пары менеджеров.

<a href="https://github.com/ancka019/DBMS/blob/main/task2_script.sql" target="_blank">Скрипт задания 2</a> 

# Домашнее задание 3
3.1.1 Взгляните на содержимое системных табличных представлений, доступных в вашей схеме (в APEX).
3.1.2 Выведите содержимое какой-нибудь таблицы, которая видна в ALL_TABLES, но не присутствует в USER_TABLES (не более 10 записей). 
3.1.3 Создайте таблицу со всеми базовыми типами данных (CREATE TABLE...). Убедитесь, что она будет отображаться в табличных представлениях.

3.2.1 Создайте пару-тройку таблиц (из любой предметной области) и при их создании используйте все типы правил целостности. Продемонстрируйте, как работают правила целостности при добавлении или удалении записей в таблицы.

3.2.2 Взгляните на содержимое системных представлений правил целостности в вашей схеме (в APEX). Сколько правил целостности в вашей схеме?

3.2.3 Добавьте правило целостности к таблице EMP(без явного именования), ограничивающее размер зарплаты: (500 <=sal<=5000). Убедитесь, что оно будет отображаться в соответствующем системном представлении. Напишите запрос, который выводит имя этого правила целостности.
Удалите это правило целостности.

3.2.4 Добавьте это же правило целостности с явным именованием. Убедитесь, что оно будет отображаться в соответствующем системном представлении.

3.3.1 Взгляните на содержимое представлений, связанных с индексами в своей схеме.

3.3.2 Подсчитайте количество индексов в своей схеме (напишите запрос).

3.3.3Создайте индексно-организованную таблицу DEPT1 (аналогичную таблице DEPT). Заполните ее содержимым из DEPT.

<a href="https://github.com/ancka019/DBMS/blob/main/task3_script.sql" target="_blank">Скрипт задания 3</a> 
