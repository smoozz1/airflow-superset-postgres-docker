# Airflow + Superset + PostgreSQL Docker compose Setup

A ready-to-use Docker Compose setup for Apache Airflow, Apache Superset and PostgreSQL database.

## Quick Start

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
