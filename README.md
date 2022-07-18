# Connect mysql client as phpmyadmin to mysql server

## Getting Started
Using docker-compose.yml file
```
sudo docker-compose build
sudo docker-compose up -d 
```
The **storage** directory will be created and mounted /var/lib/mysql directory in mysql container.

## Delete all
```
sudo docker-compose down
sudo rm -rf storage
```
### Phpmyadmin: http://127.0.0.1:8080
*Username & password: root*
