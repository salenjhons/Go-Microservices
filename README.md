# Go-Microservices
Projet to learn how to create app through microservice archtecture.

To start the project:


cd /project // folder with with make and docker-compose file 

make up_buld // To start backend part of the app

make up  // To start frontend part of the app


To shut the project:

make down // shutdown backend

make stop // shutdown frontend

29.01.23 
Added listener-service and rabbitmq using next command


cd listnere-service & cd broker-service

go get github.com/rabbitmq/amqp091-go

added rabbitmq image into docker-compose file
"rabbitmq:3.9-alpine"

