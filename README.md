# TinyThreads
This project is a microservices-based architecture implemented in Golang, designed to showcase various functionalities like authentication, logging, messaging, and database operations. The system consists of multiple services including:
- Broker service
- Auth service
- Logger service
- Mail service
- Listener service


Each service is responsible for specific tasks and communicates with others through various protocols and message brokers.

# Setup
1. Clone this repository.
2. Navigate to the root folder.
3. Run npm run install-dependencies to install project dependencies.
4. Create a .env file in the root folder.
5. Configure values for the following environment variables:
  - MONGO_URL: MongoDB connection URL.
  - JWT_SECRET: Secret key for JWT token generation.
  - JWT_LIFETIME: Lifetime of JWT tokens.
6. Start each microservice and the frontend.
7. Visit http://localhost:80/ to interact with the frontend.

# Usage
The frontend provides buttons and interfaces to interact with different microservices. Explore the functionalities and observe how the services communicate with each other.

# Communication Diagram
![fin](https://github.com/siddharth-droid/TinyThreads/assets/73477387/3b55e415-cd92-4322-824d-0aca4dcd43f1)


# Screenshots
![1](https://github.com/siddharth-droid/TinyThreads/assets/73477387/0526ed53-0550-4db2-b70b-89c01e1b38f3)
![2](https://github.com/siddharth-droid/TinyThreads/assets/73477387/39b2f9aa-6f5c-44fc-b3fc-98649cb33a3b)
![3](https://github.com/siddharth-droid/TinyThreads/assets/73477387/78a0f947-571f-4f3f-870a-46d859333596)
![4](https://github.com/siddharth-droid/TinyThreads/assets/73477387/24e37044-ea83-40cc-adfb-c1c4eddf19ed)
![5](https://github.com/siddharth-droid/TinyThreads/assets/73477387/9d4a6e93-9965-468f-8612-c735ece2398d)
![6](https://github.com/siddharth-droid/TinyThreads/assets/73477387/5dfc6729-b164-4660-bddc-13e27459d312)


