Исследование аренды велосипедов в Нью-Йорке. Citibike за сентябрь-октябрь 2022
========================

### Задачи:
* Сделать исследовательский анализ данных велопроката в Нью-Йорке (США) за сентябрь-октябрь 2022 года. 
* Исследовать корреляции с внешними данными. 
* Построить дашборд в DataLens с основными показателями и выводами

### Технические этапы проделанной работы
1. Предобработка и склеивание датасетов + небольшая EDA через [google colab](https://github.com/timurka/citybike-NY/blob/main/citibike_NY.ipynb).
2. Загрузка данных в БД MySQL на удалённый сервер
3. Подключение БД к DataLens и создание [дашборда](https://datalens.yandex.ru/3oe7x2bnzxtcu-dashboard-ny-bike?tab=1M)

### Источники данных
* [Citi Bike Trip Histories](https://ride.citibikenyc.com/system-data) - данные аренды велосипедов Citibike
* [NYC REAL TIME TRAFFIC SPEED DATA FEED(ARCHIVED) FIVE MINUTE INTERVALS](https://data.beta.nyc/dataset/nyc-real-time-traffic-speed-data-feed-archived) - данные о скорости трафика на основных дорогах. Архив с интервалами 5 минут
* [NOAA](https://www.ncei.noaa.gov/cdo-web/) - данные о погоде

### Используемые библиотеки
pandas, numpy, seaborn, matplotlib, scipy, glob, os, geopy.distance, sqlalchemy, pymysql

[Посмотреть Jupyter notebook проекта](https://github.com/timurka/citybike-NY/blob/main/citibike_NY.ipynb) 

Как выглядит дашборд
-------------------------
[Готовый дашборд с выводами (DataLens)](https://datalens.yandex.ru/3oe7x2bnzxtcu-dashboard-ny-bike?tab=1M)

### Вкладка "Общее"
![](https://github.com/timurka/citybike-NY/blob/main/dashboard_screenshots/dashboard1_main.png?raw=true)

### Вкладка "Погода и трафик"
![](https://github.com/timurka/citybike-NY/blob/main/dashboard_screenshots/dashboard_weather.png?raw=true)

### Вкладка "На карте"
![](https://github.com/timurka/citybike-NY/blob/main/dashboard_screenshots/dashboard_map.png?raw=true)
