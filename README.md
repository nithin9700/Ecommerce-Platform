# Microservices Based Ecommerce Platform

## Description
Architected a Microservices Based Platform with functionalities like Login , Authorization , Product Catalog , Payment Gateway Integration (Razorpay) , Service Discovery , Notification Service (Email Notification) etc.

Deployed whole Ecosystem on AWS Elastic Beanstalk leveraging RDS for Data Persistence, CloudWatch for efficient Logging and Monitoring.

Implemented Event Driven Email Service using Kafka to allow sending emails at large scale across different services within the Platform.

Implemented powerful sorting , filtering and paging to allow for efficient discovery of products.

Optimized the response time of APIs from ~500 ms to ~20 ms by making effective usage of Caching for static data using Redis Cache.


## Microservices code Links used in the Project
Ecommerce Product Service [here](https://github.com/nithin9700/EcomProductBackEnd).

User Authorization Service [here](https://github.com/nithin9700/UserOAuth).

Payment Gateway Service [here](https://github.com/nithin9700/PaymentService).

Email Notification Service [here]().

Service Discovery Eureka client [here]().

## Tools and Frameworks used :
    SpringBoot , SpringCloud , MySQL , Hibernate , Redis , Razorpay Payment Gateway , Stripe Payment Gateway , JUnit , Kafka 

