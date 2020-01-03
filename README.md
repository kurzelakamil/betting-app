# betting-app

Microservices Project. So far there is created Spring Cloud architecture:

* config-server
* discovery-server
* api-gateway

* oauth2 authorization server

and:
* user-service
* saga-orchestrator

Services are created in Java (SpringBoot, SpringCloud, SpringSecurity, SpringData), build in Gradle.

There is also docker-compose containing PostgreSQL database with environment variables loading from .env file and RabbitMQ message-broker

There is no any business logic and frontend at this step, both will be added later. 
