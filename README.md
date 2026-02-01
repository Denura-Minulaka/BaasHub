# BaasHub Web Application

**BaasHub** is a web application designed to manage customer-service interactions, including contract handling, service requests, complaints, and worker management. The system is built using a **microservices architecture** for scalability and maintainability.

---

## Project Overview
BaasHub allows customers to submit service requests, lodge complaints, and interact with workers. Administrators and workers can manage services, contracts, and notifications. The application is modular, with separate backend microservices and a React frontend.

- **Frontend:** React (JavaScript)  
- **Backend Services:** Java + Spring Boot  
- **Database:** MySQL  
- **Messaging:** Kafka (for notifications)  
- **Version Control:** Git & GitHub  

---

## Microservices Architecture

| Service | Repository Link | Description |
|---------|----------------|------------|
| **Contract Service** | [GitHub](https://github.com/H1runa/contract-microservice.git) | Manages service contracts between customers and workers |
| **Complain Service** | [GitHub](https://github.com/DesanDinsanda/complain-microservice.git) | Handles customer complaints and their status |
| **Customer Service** | [GitHub](https://github.com/Denura-Minulaka/customer-ms.git) | Manages customer registration, profiles, and preferences |
| **Worker Service** | [GitHub](https://github.com/NethmiVP/worker.git) | Handles worker profiles, availability, and task assignments |
| **Service Management** | [GitHub](https://github.com/DesanDinsanda/service-ms.git) | Manages services offered, scheduling, and pricing |
| **Notification Service** | [GitHub](https://github.com/H1runa/notification-service.git) | Sends real-time notifications (requires Kafka server) |
| **Frontend Application** | [GitHub](https://github.com/DesanDinsanda/ead-frontend.git) | React-based frontend connecting all backend services |

---

## Technologies Used
- **Backend:** Java, Spring Boot, REST APIs  
- **Frontend:** React (JavaScript)  
- **Database:** MySQL  
- **Messaging Queue:** Kafka  
- **Tools:** Git, GitHub, Postman  

---

## Key Features
- Customer registration and profile management  
- Service listing and management  
- Complaint tracking and resolution  
- Worker management and task assignments  
- Real-time notifications via Kafka  
- Microservices architecture for modularity and scalability  

---

## How to Run
1. Clone each backend microservice repository.  
2. Configure database connections for each service.  
3. Start Kafka server for Notification Service.  
4. Run each microservice individually (ports configured in each repo).  
5. Clone and run the frontend application.  
6. Access the system at `http://localhost:3000`.  

---

## Project Type
- **Type:** Group Project  
- **Contribution:** Developed Customer Microservice and half frontend  

---

