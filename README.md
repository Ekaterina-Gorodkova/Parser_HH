# Parser_HeadHunter

Я поставила перед собой задачу собрать данные с сайта hh.ru  и проанализировать их, чтобы выявить актуальную информацию по вакансиям 

Часть 1. Сбор данных с сайта  

В данном разделе представлен код для сбора данных о вакансиях с сайта hh.ru, которые нам потребуются для дальнейшей работы. 
Поиск вакансий осуществляется по указанному тексту, содержащему название вакансии или интересующую сферу работы. 
Проект ориентирован на вакансии, доступные в России.

Часть 2. Создание DataFrame  

Для наглядности и удобства был создан DataFrame с следующими столбцами: vacancy_name, city, lat, lng, company_name, experience, skills, salary_from, salary_to и description. 
Кроме того, был добавлен столбец average_salary. 
В этом блоке также проведена обработка столбца description, включающая удаление html-символов и знаков препинания.

Часть 3. Анализ данных и построение графиков  

В анализе используются параметры, такие как необходимые навыки, средняя зарплата, города, координаты и опыт работы. Построены следующие графики:

1) Круговая диаграмма, отражающая распределение наиболее часто встречающихся навыков.
2) Распределение вакансий на карте.
3) Гистограмма, отображающая зависимость между количеством вакансий, средней зарплатой и городом.
4) Гистограмма распределения вакансий в зависимости от опыты работы.

Основная цель проекта заключалась в создании парсера и визуализации результатов анализа, позволяя лаконично представить актуальную информацию о вакансиях на основе данных с сайта hh.ru.




