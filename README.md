# 11_03 - Домашнее задание к занятию "ELK" - Тимохин Максим

### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

**Ответ:**

<img width="700" height="497" alt="Screenshot from 2026-05-04 19-34-22" src="https://github.com/user-attachments/assets/edbbc02a-1e2b-419b-a46f-b12329414c29" />

---

### Задание 2. Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.

**Ответ:**

<img width="1360" height="736" alt="Screenshot from 2026-05-04 19-39-11" src="https://github.com/user-attachments/assets/ca0b884a-e26b-482a-85a3-5deb5c4cea34" />

---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

**Ответ:**


---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*

**Ответ:**

