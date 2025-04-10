# 🏥 Patient Management System

A full-stack, production-grade Patient Management System built with **Spring Boot**, **React**, **gRPC**, **Kafka**, **Docker**, and **AWS**. Designed to demonstrate enterprise-level architecture using microservices, CI/CD, and best practices.

---

## 🚀 Tech Stack

### Backend
- Java 17
- Spring Boot (REST + Spring Security)
- gRPC
- Kafka (asynchronous messaging)
- MySQL / PostgreSQL (production), H2 (dev)
- Docker, Docker Compose
- AWS CloudFormation + LocalStack

### Frontend
- React + TypeScript
- Redux Toolkit
- Tailwind CSS
- Jest, React Testing Library

### DevOps / Infra
- Git, GitHub
- Maven
- GitHub Actions (CI/CD)
- API Gateway
- Eureka Service Discovery (if applicable)

---

## 🛠️ Project Structure

```
patient-management/
├── backend/
│   ├── gateway/
│   ├── patient-service/
│   └── notification-service/
├── frontend/
│   └── react-app/
├── docker/
├── docs/
├── .gitignore
├── docker-compose.yml
├── README.md
└── ...
```

---

## 🏗️ Getting Started

### Backend

```bash
# Navigate to a service and run
./mvnw spring-boot:run
```

> Make sure `application-dev.yml` is active and DB is set to H2 for local.

### Frontend

```bash
cd frontend/react-app
npm install
npm run dev
```

---

## 🌱 Branching Strategy

- `main`: Production-ready code
- `develop`: Active development
- `feature/*`: Feature-specific branches
- `fix/*`: Bug fixes

> All pull requests go to `develop`, and are merged into `main` during release.

---

## 🧪 Running Tests

### Backend
```bash
./mvnw test
```

### Frontend
```bash
npm run test
```

---

## 🧰 Useful Commands

```bash
# Run Spring Boot service
./mvnw spring-boot:run

# Run Docker stack
docker-compose up --build

# Format code with Maven plugin
./mvnw fmt:format
```

---

## 📸 Screenshots (optional later)
_Add UI screenshots here_

---

## 📚 Documentation

Refer to `/docs` for architecture diagrams, workflows, and other technical notes.

---

## 👤 Author

- **Ajay Nag**
- [GitHub](https://github.com/ajaynag123)

---

## 📄 License

This project is licensed under the MIT License.
```