# E-commerce Microservices Architecture

A robust backend infrastructure for e-commerce platforms built using Node.js, implementing microservices architecture with RabbitMQ for message queuing and Docker for containerization.

## Architecture Overview

The platform is divided into the following microservices:

- **Customer Service**: Handles user authentication, authorization, and profile management
- **Product Service**: Manages product catalog, inventory, and pricing
- **Shoping Service**: Processes orders, manages shopping carts, and handles checkout

## Technology Stack

- **Runtime**: Node.js
- **Message Broker**: RabbitMQ
- **Containerization**: Docker & Docker Compose
- **Database**: MongoDB (for each service)
- **API Gateway**: Express.js
- **Authentication**: JWT (JSON Web Tokens)

## Prerequisites

- Node.js (v16 or higher)
- Docker & Docker Compose
- RabbitMQ
- MongoDB

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/sahilf637/Nature_cart.git
cd Nature_cart
```

2. Start the services using Docker Compose:
```bash
docker-compose up -d
```

3. Verify the services are running:
```bash
docker-compose ps
```

## Author  
**Sahil Singh Fartyal**  

- **GitHub:** [@sahilf637](https://github.com/sahilf637)  
- **Email:** [sahilf637.work@gmail.com](sahilf637.work@gmail.com)  
