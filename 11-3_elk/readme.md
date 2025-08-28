
# Домашнее задание к занятию "`ELK`" - `Девятов Илья`

### Задание 1 Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.
Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

**Решение**

![тест1](images/1.png)



### Задание 2 Kibana
Установите и запустите Kibana.
Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

![тест2](images/2.png)

### Задание 3 Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

![тест3](images/3.png)

### Задание 4 Filebeat.

![тест4](images/4.png)
![тест5](images/5.png)

### Задание 5*. Работа с числами

нет пока

