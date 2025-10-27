# Patient Management System

A microservices-based **Patient Management System** built with **Spring Boot**, **PostgreSQL**, **Kafka**, and **Docker**.  
It provides modular services for managing patient data, authentication, billing, and analytics — all connected through a centralized **API Gateway**.

---

## Overview

This system demonstrates a **distributed microservices architecture**, where each service handles a specific domain:
- **Auth Service** → User authentication and JWT token management
- **Patient Service** → Patient data management and billing integration
- **Billing Service** → Handles patient billing and invoices
- **Analytics Service** → Processes and consumes Kafka events for analytics
- **API Gateway** → Acts as the entry point (frontier) to route external API calls to respective backend services
- **Infrastructure Module** → Manages container orchestration, networks, databases, and Kafka configuration
