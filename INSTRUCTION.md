# Django TODO App with MySQL

## Run MySQL with Volume
```bash
docker run -d --name mysql-container -p 3306:3306 -v mysql_data:/var/lib/mysql mysql-local:1.0.0