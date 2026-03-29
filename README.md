# SmartHome Backend 1

> Smart home automation backend with device control and scenes

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
C++, MQTT, InfluxDB, CMake

## 🏗️ Architecture
Backend service with C++, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/smarthome-backend-1
cd smarthome-backend-1

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
