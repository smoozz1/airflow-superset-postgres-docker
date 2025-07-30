# Airflow + Superset + PostgreSQL Docker Compose Project

A ready-to-use Docker Compose setup for Apache Airflow, Apache Superset and PostgreSQL database.

## ⚙️ Prerequisites

- Docker Engine 20.10+
- Docker Compose 2.0+
- 4 GB+ free RAM
- Git (for installation)

## 🚀 Quick Start

### 1. Clone the repository:
```bash
git clone https://github.com/smoozz1/airflow-superset-postgres-docker
```
### 2. Navigate to project directory:

```bash
cd airflow-superset-postgres-docker
```

### 3. Initialize PostgreSQL database:

```bash
docker compose up db
```
*Wait 1-2 minutes for database initialization*

### 4. Start all services:

```bash
docker compose up -d
```
### 5. Stop all services:
```bash
docker compose down
```
