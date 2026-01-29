# order-processing 

this project is a sample event-driven application built with: 
- .net 8; 
- rabbitmq;
- ddd;
- gitflow practices;
- docker to provision local infrastructure.

## the principal purpose of this project is practice and consolidate knowledge around: 
- event driven architecture;
- async communication;
- retry, dlq and consumer resilience;
- ddd patterns and clean architecture;

## the architecture is: 
- order.api
  - receives http request; 
  - persists data in postgresql
  - publish message
- workers
  - proccess and consumes message from rabbitmq;
  - process async bussines logic;
- rabbitmq
  - topic exchange for event;
  - queues retry and dlq strategy
 
## tech stacks, architecture and priciples: 
- .net 8;
- rabbitmq;
- postgresql;
- docker and docker-compose;
- gitflow;
- clean architecture;
- ddd.


lets bora? :) 
