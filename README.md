Исследование аренды велосипедов в Нью-Йорке. Citibike за сентябрь-октябрь 2022
========================

### Задачи:
* Сделать исследовательский анализ данных велопроката в Нью-Йорке (США) за сентябрь-октябрь 2022 года. 
* Исследовать корреляции с внешними данными. 
* Построить дашборд в DataLens с основными показателями и выводами

### Технические этапы проделанной работы
1. Предобработка и склеивание датасетов + небольшая EDA через google colab.
2. Загрузка данных в БД MySQL на удалённый сервер
3. Подключение БД к DataLens и создание дашборда

### Источники данных
* [Citi Bike Trip Histories](https://ride.citibikenyc.com/system-data)
* [NYC REAL TIME TRAFFIC SPEED DATA FEED(ARCHIVED) FIVE MINUTE INTERVALS](https://data.beta.nyc/dataset/nyc-real-time-traffic-speed-data-feed-archived)
* [NOAA](https://www.ncei.noaa.gov/cdo-web/)

### Используемые библиотеки
pandas, numpy, seaborn, matplotlib, scipy, glob, os, geopy.distance, sqlalchemy, pymysql

[Посмотреть Jupyter notebook проекта](https://github.com/timurka/citybike-NY/blob/main/citibike_NY.ipynb) 

Как выглядит дашборд
-------------------------
[Готовый дашборд с выводами (DataLens)](https://datalens.yandex.ru/3oe7x2bnzxtcu-dashboard-ny-bike?tab=1M)

### Вкладка "Общее"
![](https://github.com/timurka/citybike-NY/blob/main/dashboard-screenshots/dashboard_main.png?raw=true)

### Вкладка "Погода и трафик"
![](https://github.com/timurka/citybike-NY/blob/main/dashboard-screenshots/dashboard_weather.png?raw=true)

### Вкладка "На карте"
![](https://github.com/timurka/citybike-NY/blob/main/dashboard-screenshots/dashboard_maps.png?raw=true)
