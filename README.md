# Inventory Management System (IMS) - Backend

A robust and scalable backend API for managing product inventory, suppliers, purchase orders, and warehouse operations. Built with [NestJS](https://nestjs.com/) and [Fastify](https://www.fastify.io/) for high performance, this project is designed for learning and practical implementation of advanced backend concepts such as RBAC, interceptors, testing, and modular architecture.

---

## 🚀 Project Overview

The **Inventory Management System (IMS)** enables small to mid-sized businesses to efficiently track, manage, and optimize their inventory processes. The primary goal is to reduce errors, automate stock tracking, and provide actionable insights to streamline business operations.

**Key Features:**
- Product and category management (CRUD)
- Real-time inventory tracking with history/audit trail
- Multi-location stock management
- Supplier and purchase order management
- Role-based access control (RBAC)
- Comprehensive reporting and analytics
- Secure authentication & authorization (JWT)
- Modular, extensible backend architecture

---

## 🎯 Business Goal & Objectives

- **Optimize Inventory Levels**: Prevent overstocking and stockouts
- **Streamline Operations**: Automate repetitive inventory processes
- **Enable Data-Driven Decisions**: Actionable analytics for purchasing and stock management
- **Reduce Manual Errors**: Digitize and centralize inventory tracking
- **Enhance Security & Accountability**: Role-based permissions and audit logs

---

## 🏗️ MVP Scope

- User authentication (JWT)
- RBAC: Admin, Inventory Manager, Warehouse Staff, Purchasing Agent, Readonly
- Product & category endpoints
- Inventory transactions and stock adjustments
- Supplier CRUD and purchase order endpoints
- Basic reporting (stock levels, reorder recommendations)
- Unit and integration testing

---

## 👤 Roles & Responsibilities

| Role               | Example Responsibilities                                                  |
|--------------------|--------------------------------------------------------------------------|
| **Admin**          | Manage users & roles, full access, system config                         |
| **Inventory Manager** | Product CRUD, inventory adjustments, manage suppliers, place orders    |
| **Warehouse Staff**   | View products, log stock movements, process receipts                   |
| **Purchasing Agent**  | Create/manage purchase orders, supplier communication                  |
| **Readonly**          | View inventory and reports only                                        |

---

## 🛠️ Tech Stack

- **Backend Framework:** [NestJS](https://nestjs.com/) + [Fastify](https://www.fastify.io/)
- **Language:** TypeScript
- **Database:** PostgreSQL
- **Caching (optional):** Redis
- **Authentication:** Passport.js & JWT
- **Testing:** Jest, Supertest, Pactum
- **Documentation:** Swagger/OpenAPI
- **CI/CD:** GitHub Actions
- **Dev Tools:** ESLint, Prettier, Docker

---

## 📚 Learning Highlights

- Modular NestJS architecture with Fastify adapter
- Secure JWT authentication & RBAC implementation
- Custom NestJS interceptors (logging, RBAC, transformation, caching)
- Real-world business logic endpoints (e.g., predictive reordering, inventory balancing)
- Comprehensive unit, integration, and e2e tests

---

## 📦 Getting Started

> **Note:** This project is a backend API only. Frontend and deployment guides may be added in the future.

### Prerequisites

- Node.js (v18+ recommended)
- PostgreSQL (local or Docker)
- [Yarn](https://yarnpkg.com/) or [npm](https://www.npmjs.com/)
- (Optional) Docker & Docker Compose

### Installation

```bash
# Clone the repo
git clone https://github.com/DhakalYukesh/inventory-management-system.git
cd inventory-management-system

# Install dependencies
yarn install

# Copy and configure environment variables
cp .env.example .env
```

### Running the App

```bash
# Run development server
yarn start:dev

# Or run with Docker (recommended for DB)
docker-compose up --build
```

### Testing

```bash
# Run unit & integration tests
yarn test

# Run e2e tests
yarn test:e2e

# Check test coverage
yarn test:cov
```

---

## 📝 Documentation

- Full API documentation available at `/api/docs` when running the server.
- See [`docs/`](./docs/) for architecture and design notes.
- [MVP/Product Spec](./inventory_management_system_project.md)

---

## 📄 License

This project is for educational and non-commercial use. See [LICENSE](./LICENSE) for details.

---

## ✨ Acknowledgements

Inspired by real-world business needs, built as a comprehensive backend learning project using modern Node.js tools. Special thanks to the open source community.

---