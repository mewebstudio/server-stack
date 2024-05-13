# Server stack for Docker Swarm

### Requirements:
* [Docker with Swarm mode](https://docs.docker.com/engine/swarm/)

### Applications:
* [NGINX Proxy Manager](https://nginxproxymanager.com)
* [Portainer](https://www.portainer.io)
* [Jenkins](https://www.jenkins.io)
* [PostgreSQL](https://www.postgresql.org)
* [PgAdmin](https://www.pgadmin.org)
* [MariaDB](https://www.mariadb.org)
* [PhpMyAdmin](https://www.phpmyadmin.net)
* [Adminer](https://www.adminer.org)
* [MongoDB](https://www.mongodb.org)
* [mongo-express](https://github.com/mongo-express/mongo-express)
* [Redis](https://redis.io)
* [Redis Commander](https://joeferner.github.io/redis-commander)
* [RabbitMQ](https://www.rabbitmq.com)
* [Elastic Search](https://www.elastic.co)
* [Kibana](https://www.elastic.co/kibana)

----------------------------------------------------------------

### Install and run with Docker
```bash
docker-compose up --build -d
````


### Docker Stack Deploy
```bash
docker stack deploy --compose-file docker-stack.yml server-stack
```
