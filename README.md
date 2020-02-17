# Docker Local Service

Docker local service is a repo which contains services wrapped in docker-compose. So need to install those services manually into your development environment or server. 
<br/>Just perform `docker-compose up -d` or `docker-compose up -d container-name-1 container-name-2` 

## List of available services:
- Elasticsearch
- Kibana
- Logstash
- Cerebro
- PostgreSQL
- MongoDB
- Mariadb (support myrocks db engine)
- Nginx
- RabbitMQ
- NSQ
- Gogs (lightweight git repo like github) visit https://gogs.io/

## Upcoming services to be added:

## Configuration:
* NSQ instance need special configuration because its broadcast address attached to nsqd.
We should add nsqd as localhost address in hosts
  - for mac or linux located in /etc/hosts
  - for windows located in c:\windows\system32\drivers\etc\hosts
* PostgreSQL and MariaDB or MySQL default password is `example`
* MongoDB default user is `root` and password is `example`
