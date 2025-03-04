# Assignments_Automated

![image](https://github.com/user-attachments/assets/bbb28634-829c-484f-a19f-3b78cf62d403)

Microservices is an architectural style that structures an application as a collection of small, autonomous services modeled around a business domain. Each microservice is self-contained and implements a specific business capability, allowing for independent development, deployment, and scaling.

**Building Microservices Introduction:**
Transitioning from a monolithic architecture to microservices involves decomposing the application into distinct services, each responsible for a specific functionality. This approach enhances modularity, scalability, and maintainability. 

**Creating a Question Service:**
In a microservices-based application, a Question Service would handle operations related to questions, such as creation, retrieval, updating, and deletion. This service operates independently, managing its own data and logic.

**Running the Question Service:**
Once developed, the Question Service can be deployed independently, allowing it to be started, stopped, or scaled without affecting other services. This independence facilitates continuous deployment and integration.

**Creating a Quiz Service:**
Similarly, a Quiz Service would manage functionalities related to quizzes, such as assembling questions into quizzes, scheduling, and scoring. This service operates autonomously but can interact with the Question Service as needed.

**Need for Eureka Server:**
In a microservices architecture, services need to discover and communicate with each other dynamically. Netflix's Eureka Server acts as a service registry, enabling services to register themselves and discover other registered services, facilitating load balancing and failover.

**Creating a Service Registry:**
Implementing a service registry like Eureka involves setting up a central server where all microservices register upon startup. This registry maintains information about service instances and their locations, enabling efficient service discovery.

**Working with Feign:**
Feign is a declarative HTTP client developed by Netflix, simplifying the process of making HTTP requests in microservices. By using Feign, developers can define interfaces and annotate them to specify the web service calls, reducing boilerplate code. 

**Microservice Calling a Microservice:**
Inter-service communication is fundamental in microservices architectures. Services can communicate synchronously via HTTP/REST or asynchronously using messaging queues, depending on the use case and performance requirements.

**Completing the Two Microservices:**
After implementing both the Question and Quiz Services, they can function independently while collaborating through well-defined APIs. This separation allows for individual scaling, deployment, and maintenance.

**Load Balancing:**
To distribute incoming requests evenly across multiple instances of a service, load balancing is employed. This ensures high availability and reliability by preventing any single instance from becoming a bottleneck.

**API Gateway:**
An API Gateway serves as a single entry point for clients accessing multiple microservices. It handles request routing, composition, and protocol translation, simplifying client interactions and enhancing security.

For a practical implementation of these concepts, you can refer to the "Assignments_Automated" repository, which provides code examples and further explanations.

Citation : Telusko 
