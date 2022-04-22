# 5_3
# 1
Сделал, добавил тег `<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />`, чтобы апостроф отображался корректно.
`https://hub.docker.com/repository/docker/pashicop/new-index`

# 2

Посмотрите на сценарий ниже и ответьте на вопрос: "Подходит ли в этом сценарии использование Docker контейнеров или лучше подойдет виртуальная машина, физическая машина? Может быть возможны разные варианты?"

Детально опишите и обоснуйте свой выбор.

--

Сценарий:

    Высоконагруженное монолитное java веб-приложение;
    Nodejs веб-приложение;
    Мобильное приложение c версиями для Android и iOS;
    Шина данных на базе Apache Kafka;
    Elasticsearch кластер для реализации логирования продуктивного веб-приложения - три ноды elasticsearch, два logstash и две ноды kibana;
    Мониторинг-стек на базе Prometheus и Grafana;
    MongoDB, как основное хранилище данных для java-приложения;
    Gitlab сервер для реализации CI/CD процессов и приватный (закрытый) Docker Registry.

# 3
Всё получилось.
```
root@94769e10385c:/data# ls
centos_file  host_file
root@94769e10385c:/data# cat centos_file 
text from centos
root@94769e10385c:/data# cat host_file 
text from host machine
root@94769e10385c:/data# 
```
# 4
Получилось
`https://hub.docker.com/repository/docker/pashicop/ansible`
