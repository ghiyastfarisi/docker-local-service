# Docker Local Service

## List of services:
- Elasticsearch
- Cerebro
- PostgreSQL
- MongoDB
- MySQL
- Nginx
- RabbitMQ
- NSQ

## Upcoming services to be added:
- ELK support (kibana, logstash & filebeat)

## Configuration:
NSQ instance need special configuration because its broadcast address attached to nsqd.
We should add nsqd as localhost address in hosts
- for mac or linux located in /etc/hosts
- for windows located in c:\windows\system32\drivers\etc\hosts
