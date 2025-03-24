<p align="center"><img src="https://github.com/kuchsk/Skillfactory_hh/blob/main/hh%20label2.jpg" alt="hh label2" style="width:500px; height:300px"></p>

# skillfactory_sql_hh
Profession Data Science - SQL - Analysis of resumes from HeadHunter

 Проект: Анализ резюме из HeadHunter
 Данный проект посвящен анализу данных о резюме, полученных с сайта HeadHunter 

## Цель проекта

- Провести анализ данных.
- Выявить основные зависимости между признаками.
- Сделать выводы по каждому заданию и общий вывод в итоге

## Данные

- Данные представлены в виде онлайн базы данных postgree SQL. 

## Инструменты

- SQL (PostgreSQL) и python

## Задачи

1. **Предварительный анализ данных:**
    - Напишите запрос, который посчитает количество вакансий в нашей базе (вакансии находятся в таблице vacancies).
    - Напишите запрос, который посчитает количество работодателей (таблица employers).
    - Посчитате с помощью запроса количество регионов (таблица areas).
    - Посчитате с помощью запроса количество сфер деятельности в базе (таблица industries).
2. **Детальный анализ вакансий:**
    - Напишите запрос, чтобы определить у какого количества вакансий заполнено хотя бы одно из двух полей с зарплатой.
    - Найдите средние значения для нижней и верхней границы зарплатной вилки. Округлите значения до целого
    - Найдите средние значения для нижней и верхней границы зарплатной вилки. Округлите значения до целого.
    - Напишите запрос, который выведет количество вакансий для каждого сочетания типа рабочего графика (schedule) и типа трудоустройства (employment), используемого в вакансиях. Результат отсортируйте по убыванию количества.
    - Напишите запрос, выводящий значения поля Требуемый опыт работы (experience) в порядке возрастания количества вакансий, в которых указан данный вариант опыта.
    - Преобразовать признак "ЗП" в новый признак "ЗП (руб)" с учетом курса валют.
3. **Анализ работодателей**
    - Напишите запрос, который позволит узнать, какие работодатели находятся на первом и пятом месте по количеству вакансий.
    - Напишите запрос, который для каждого региона выведет количество работодателей и вакансий в нём. Среди регионов, в которых нет вакансий, найдите тот, в котором наибольшее количество работодателей.
    - Напишите запрос для подсчёта количества работодателей, у которых не указана сфера деятельности.
    - Напишите запрос, чтобы узнать название компании, находящейся на третьем месте в алфавитном списке (по названию) компаний, у которых указано четыре сферы деятельности.
    - Для компании «Яндекс» выведите список регионов-миллионников, в которых представлены вакансии компании, вместе с количеством вакансий в этих регионах. Также добавьте строку Total с общим количеством вакансий компании. Результат отсортируйте по возрастанию количества.
4. **Предметный анализ**
    - Сколько вакансий имеет отношение к данным?
    - Сколько есть подходящих вакансий для начинающего дата-сайентиста?
    - Сколько есть вакансий для DS, в которых в качестве ключевого навыка указан SQL или postgres?
    - Проверьте, насколько популярен Python в требованиях работодателей к DS.Для этого вычислите количество вакансий, в которых в качестве ключевого навыка указан Python.
    - Сколько ключевых навыков в среднем указывают в вакансиях для DS? Ответ округлите до двух знаков после точки-разделителя.
    - Напишите запрос, позволяющий вычислить, какую зарплату для DS в среднем указывают для каждого типа требуемого опыта (уникальное значение из поля experience).

## Общий вывод по проекту

- Проведенное исследование вакансий в сфере Data позволило выявить ряд ключевых тенденций на рынке труда:
Высокий спрос на специалистов в области Data: Несмотря на то, что только около 3.6% вакансий напрямую связаны с "data" или "данными", спрос на специалистов в этой сфере очевиден.
Нехватка junior-специалистов: Низкое количество вакансий для junior-специалистов (51) говорит о нехватке кадров на начальном уровне.
Популярность SQL и Python: SQL и Python являются ключевыми навыками для специалистов в области Data.
Высокая конкуренция: Среднее количество ключевых навыков в вакансиях (6) говорит о высокой конкуренции на рынке труда.
Достойная заработная плата: Средняя заработная плата в сфере Data является достаточно высокой (243115 рублей).

- Дополнительные исследования
Исследование можно продолжить, углубив анализ в следующих направлениях:
Анализ зарплат по регионам: Провести анализ зарплат по регионам для выявления наиболее привлекательных регионов для работы в сфере Data.
Анализ популярных технологий: Провести анализ популярных технологий в сфере Data для выявления наиболее востребованных инструментов и платформ.
Анализ сфер деятельности компаний: Провести анализ сфер деятельности компаний, публикующих вакансии в сфере Data, для выявления наиболее активных отраслей.

- Прогнозы
Исходя из полученных данных, можно сделать следующие прогнозы:
Спрос на специалистов в области Data будет продолжать расти: С ростом цифровизации и использования данных в различных сферах, спрос на специалистов в области Data будет продолжать расти.
Повысится спрос на специалистов с узкой специализацией: Повысится спрос на специалистов с узкой специализацией в области Data, таких как Data Scientist, Data Engineer, Data Analyst.

## Варианты продолжения исследования

- Анализ вакансий на других платформах: Провести анализ вакансий на других платформах - например SuperJob.
- Графическое оформление данных

## Результаты

- Результаты анализа представлены в Jupyter Notebook [отсюда](https://github.com/kuchsk/skillfactory_sql_hh/blob/main/skillfactory_slq_hh_analise.ipynb).`skillfactory_slq_hh_analise.ipynb`.


## Автор
Кучеревский Сергей 

## Пример SQL-запроса для анализа данных

```sql
Выборка резюме с указанием возраста и желаемой зарплаты
SELECT age, desired_salary
FROM resumes;
```


