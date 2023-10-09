# Microservices Chat Application

This project presents a robust chat application engineered using a microservice architecture to effectively distribute its services. The architecture is structured as follows:

* **Frontend:** The user interface for interactive communication.
* **API Gateway (Ocelot):** Serves as the entry point for client requests, routing them to the respective microservices.
* **Publish-Subscribe Service (MassTransit):** A messaging system that facilitates asynchronous communication among microservices.
* **Database Service:** Responsible for data persistence and retrieval, ensuring a reliable state across the application.

By adopting a microservice architecture, this chat application demonstrates scalability, resilience, and ease of maintenance, which are pivotal for real-time communication platforms.
