# Домашнее задание к занятию "`«ELK»`" - `Вернигоров Дмитрий`



---

### Задание 1

### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

![image](https://github.com/Wernigerode23/11-03.md/assets/153208339/7f2772c9-ae7e-4386-9b81-91aa8055c0aa)



### Задание 2

Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.Nginx.
![image](https://github.com/Wernigerode23/11-03.md/assets/153208339/e5ca98fa-cc23-4e72-9149-914fc4947a45)


---

### Задание 3

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.


![image](https://github.com/Wernigerode23/11-03.md/assets/153208339/28ffe474-bf09-4acc-bcb3-51b211eec2cc)
![image](https://github.com/Wernigerode23/11-03.md/assets/153208339/51670bcc-2934-4b82-9fc4-8600fd4c3e41)



### Задание 4

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

![image](https://github.com/Wernigerode23/11-03.md/assets/153208339/880fac74-82d4-432e-872b-bf9f9bf36122)
![image](https://github.com/Wernigerode23/11-03.md/assets/153208339/c0463a74-5df7-4ae3-bb80-e2d4cbcd694a)


