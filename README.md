# Тестовое задание на стажировку "Гринатом"


![Метрики](https://github.com/Dimonius-73/1/blob/main/3.png)



Исходные данные:  открытый набор данных, который содержит в себе отзывы о фильмах, а также соответствующие им оценки рейтинга. Рейтинг может служить ориентиром для построения модели классификации отзывов.
https://ai.stanford.edu/~amaas/data/sentiment. Более подробное описание структуры файлов данных, а также сами данные можно найти по ссылке: https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz 

Задача: 
1.	Обучить модель на языке Python для классификации отзывов. 
2.	Разработать веб-сервис на базе фреймворка Django для ввода отзыва о фильме с автоматическим присвоением рейтинга (от 1 до 10) и статуса комментария (положительный или отрицательный). 

В рамках  данного задания  были проведены следующие этапы: 
1.	Загрузка и изучение данных
2.	Обработка текста
3.	Предсказание тональности отзывов (positive / negative)
4.	Предсказание рейтинга
5.	Разработка веб-сервиса на Django

#### Расчет был выполнен в Google Colaboratory


Для запуска приложения на Windows локально скачайте репозиторий и в папке выполните команды: 
1.	pip install Django  
2.	python manage.py runserver 

![Метрики](https://github.com/Dimonius-73/Grinatom/blob/main/Win.png)



Проект будет доступен локально http://127.0.0.1:8000/ .

![Метрики](https://github.com/Dimonius-73/Grinatom/blob/main/movies.png)



##### Ссылка на презентацию проекта: (https://github.com/Dimonius-73/Grinatom/blob/main/Work%20report.pdf)

##### Блокнот с обучением моделей и подготовкой данных в корневой папке (https://github.com/Dimonius-73/Grinatom/blob/main/grinatom_movies_ipynb.ipynb)



* В папке files (https://github.com/Dimonius-73/Grinatom/tree/main/rating/files) - предобученные модели.
