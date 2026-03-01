University: [ITMO University](https://itmo.ru/ru/)\
Faculty: [FICT](https://fict.itmo.ru)\
Course: [Введение в веб технологии](https://itmo-ict-faculty.github.io/introduction-in-web-tech/)\
Year: 2025/2026\
Group: U4125\
Author: Mukhamadieva Elina Varisovna\
Lab: Lab1\
Date of create: 02.03.2026\
Date of finished:

Ход работы:
1) Docker Desktop уже установлен 
![img.png](img.png)
2) Локальные образы:
![img_1.png](img_1.png)
3) Список запущенных контейнеров:
![img_2.png](img_2.png)
4) Список всех контейнеров:
![img_3.png](img_3.png)
5) Скачала образ Ubuntu:
![img_4.png](img_4.png)
6) Запустила интерактивно контейнер и установила пакет curl:
![img_5.png](img_5.png)
7) Проверила установку curl и вышла из контейнера:
![img_6.png](img_6.png)
8) Запустила контейнер с nginx (так как образа не было, он скачался)
![img_7.png](img_7.png)
9) Проверила работу на локальном хосте, все корректно:
![img_8.png](img_8.png)
10) По логам видно успешное выполнение get запроса:
![img_9.png](img_9.png)
11) Подключилась к контейнеру и выполнила команду ls:
![img_10.png](img_10.png)
12) Список запущенных контейнеров (добавился nginx):
![img_11.png](img_11.png)
13) Список всех контейнеров:
![img_12.png](img_12.png)
14) Остановила, запустила и снова остановила контейнер web-server, удалила контейнер и образ:
![img_13.png](img_13.png)
15) Создала том, запустила контейнер с томом, подключилась к контейнеру, создала файл в томе:
![img_14.png](img_14.png)
16) Удалила контейнер и создала новый с тем же томом
17) В контейнере запустила команду ls, далее cat для проверки содержимого файла:
![img_15.png](img_15.png)