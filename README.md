# Thrifter Second Hand Marketplace

Second Hand Marketplace is an e-commerce platform for individuals to buy and sell second-hand items. The platform offers features such as item search, user rating, chat, scheduling, and payments. It includes both web and mobile applications, backed by a microservices architecture.

## Features

- User registration and authentication
- Item listing, search, and categorization
- Order management
- Payment integration
- User rating system
- Chat functionality between users
- Scheduling meetings using third-party APIs (e.g., Google Calendar)
- Forum for user discussions (optional)
- Mobile app for Android

## Tech Stack

- Frontend: React
- Mobile: [React Native or Flutter, or other mobile framework]
- Backend: Spring Boot
- Database: MySQL
- Deployment: [Docker, Kubernetes, or cloud provider]

## Microservices

1. User Service: Handles user registration, authentication, and profile management.
2. Item Service: Manages item listings, including CRUD operations, search, and categorization.
3. Order Service: Manages the order process and related transactions.
4. Rating Service: Handles user ratings and reviews.
5. Chat Service: Manages chat functionality between users.
6. Scheduling Service: Handles scheduling and integration with external calendar APIs.
7. Payment Service: Manages payments and integrates with the chosen payment provider.
8. Forum Service (optional): Handles the forum functionality if included.

## Getting Started

### Prerequisites

- Install [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html)
- Install a Java IDE, such as [IntelliJ IDEA](https://www.jetbrains.com/idea/) or [Eclipse](https://www.eclipse.org/)
- Install [Node.js](https://nodejs.org/en/) and the [React CLI](https://reactjs.org/)
- Install a mobile app development framework, such as [React Native](https://reactnative.dev/) or [Flutter](https://flutter.dev/)
- Install [Docker](https://www.docker.com/) and [Kubernetes](https://kubernetes.io/) or a cloud provider's container orchestration service
- Install [Git](https://git-scm.com/)
- Sign up for a [GitHub](https://github.com/) account

### Installation

1. Clone the repository:

2. Follow the README files in each microservice directory for instructions on setting up and running the services.

3. Follow the README files in the frontend and mobile app directories for instructions on setting up and running the applications.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
