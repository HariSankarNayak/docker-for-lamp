# Docker-LAMP

Docker example with Apache, MySql 8.0, PhpMyAdmin and Php


I use docker-compose as an orchestrator. To run these containers:

```
docker-compose up -d
```

Open phpmyadmin at [http://localhost:9000](http://localhost:8000)
Open web browser to look at a simple php example at [http://localhost:9001](http://localhost:8001)

Run mysql client:

- `docker-compose exec db mysql -u root -p` 


