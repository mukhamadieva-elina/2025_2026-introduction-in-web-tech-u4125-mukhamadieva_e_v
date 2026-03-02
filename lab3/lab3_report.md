University: [ITMO University](https://itmo.ru/ru/)\
Faculty: [FICT](https://fict.itmo.ru)\
Course: [Введение в веб технологии](https://itmo-ict-faculty.github.io/introduction-in-web-tech/)\
Year: 2025/2026\
Group: U4125\
Author: Mukhamadieva Elina Varisovna\
Lab: Lab3\
Date of create: 02.03.2026\
Date of finished:

Ход работы:
1) Создала файл prometheus/prometheus.yml с информацией о частоте сбора метрик, метриками prometheus и метриками системы
![img.png](img.png)
2) Запустила контейнер Node Exporter и проверила его работу:
![img_1.png](img_1.png)
![img_2.png](img_2.png)
3) Создала том prometheus-data, для работы с grafana создала общую сеть monitoring
![img_3.png](img_3.png)
4) Работа prometheus на локальном хосте:
![img_4.png](img_4.png)
5) Создала том grafana-data и запустила контейнер:
![img_5.png](img_5.png)
6) На локальном хосте графана работает:
![img_6.png](img_6.png)
7) Залогинилась под админом в графане, далее добавила источник данных prometheus:
![img_7.png](img_7.png)
8) В prometheus проверила доступность node-exporter:
![img_8.png](img_8.png)
9) Добавила метрики node_cpu_seconds_total, node_memory_Active_bytes, node_memory_MemAvailable_bytes, node_disk_io_now
![img_9.png](img_9.png)
10) Проверка контейнеров:
![img_10.png](img_10.png)
11) Метрики собираются, данные визуализируются