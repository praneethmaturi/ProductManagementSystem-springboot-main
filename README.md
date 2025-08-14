The application is built on a microservices-based design, with the following core functionalities:

Add Product: Create and save new product entries with all necessary details (e.g., name, description, price, and stock quantity).

Update Product: Modify the information of an existing product, such as its price or description.

Delete Product: Permanently remove a product from the system.

View Products: Retrieve and display a list of all products currently in the database.

Architecture
This project is built using a microservices pattern to ensure high availability, scalability, and independent deployment of services. The key architectural components are:

Eureka Discovery Server: Provides dynamic service registration and discovery, allowing microservices to locate and communicate with each other.

Config Server: Centralizes and manages the configuration for all services, simplifying environment-specific settings.

API Gateway: Acts as the single entry point for all client requests, routing them to the correct microservice and providing standardized security and rate limiting.
