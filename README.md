# https-github.com-6-4-Docker.-2
Домашнее задание к занятию «Docker. Часть 2» Гнедин Максим




Задание 1
Напишите ответ в свободной форме, не больше одного абзаца текста.
Установите Docker Compose и опишите, для чего он нужен и как может улучшить вашу жизнь.
Решение : 
1. Помогает автоматизировать задачи управления контейнерами, что позволяет повысить производительность.
2. Упрощает разработку, тестирование и разработку и развертывание многонтейнерных приложений.
3. Упрощает управление нашими контейнерами с помощью всего лишь одного файла yaml.
4. Помогает обеспечить надежность  приложений за счет автоматизации восстановления после сбоев.


Задание 7
Выполните действия.

Выполните запрос в Pushgateway для помещения метрики <ваши фамилия и инициалы> со значением 5 в Prometheus: echo "<ваши фамилия и инициалы> 5" | curl --data-binary @- http://localhost:<внешний порт выбранный вами в задании 4>/metrics/job/netology.
Залогиньтесь в Grafana с помощью логина и пароля из предыдущего задания.
Cоздайте Data Source Prometheus (Home -> Connections -> Data sources -> Add data source -> Prometheus -> указать "Prometheus server URL = http://prometheus:9090" -> Save & Test).
Создайте график на основе добавленной в пункте 5 метрики (Build a dashboard -> Add visualization -> Prometheus -> Select metric -> Metric explorer -> <ваши фамилия и инициалы -> Apply.
В качестве решения приложите:

docker-compose.yml целиком;
скриншот команды docker ps после запуске docker-compose.yml;
скриншот графика, постоенного на основе вашей метрики.


1. ![docker-compose целиком](https://github.com/maxgn87/https-github.com-6-4-Docker.-2/blob/main/docker-compose.yml)
2. ![скриншот команды docker ps](https://github.com/maxgn87/https-github.com-6-4-Docker.-2/blob/main/image/docker%20ps.png)



3. ![cкриншот метрики](https://github.com/maxgn87/https-github.com-6-4-Docker.-2/blob/main/image/screen%20metrica.png) 







