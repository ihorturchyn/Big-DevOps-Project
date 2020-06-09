# Big-DevOps-Project

1) In docker-compose.yml file you can find general build, which includes ElasticSearch, Logstash, Kibana (ELK stack), TeamCity CI/CD with PostgreSQL and Zabbix monitoring server.

How to build that:
docker-compose up -d. 

i recommended to build docker containers without "-d" flag, because very often you have to read the logs when building containers.

2) In separated directories you can find simple builds for mentioned systems.

Again, how to build that:
docker-compose up. 
