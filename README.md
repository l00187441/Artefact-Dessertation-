# Artefact-Dissertation-
# 📚 Book Sync

Book Sync is a **microservices-based system** for managing books, borrowing, and user authentication.  
It also includes a monitoring stack using **Prometheus**, **Telegraf**, and **Grafana** for observability.  

---

## 🚀 Features

- **Auth Service** – Handles user authentication and authorization  
- **Books Service** – Manages book data and availability  
- **Borrow Service** – Tracks borrowing/returning of books  
- **Gateway** – API Gateway entry point for routing requests  
- **Proxy** – Reverse proxy for managing service traffic  
- **Monitoring Stack** – Prometheus, Telegraf, and Grafana dashboards  

---

## 🗂 Project Structure

book-sync-main/
│── auth/ # Authentication microservice
│── books/ # Books management microservice
│── borrow/ # Borrow/return tracking service
│── gateway/ # API Gateway
│── proxy/ # Reverse proxy
│── dashboards/ # Grafana dashboards
│── docs/ # Documentation
│── postman/ # Postman collections for testing
│── prometheus-data/ # Prometheus data storage
│── provisioning/ # Grafana provisioning
│── docker-compose.yml # Docker Compose configuration
│── prometheus.yml # Prometheus configuration
│── telegraf.conf # Telegraf configuration
│── collector-config.yaml # Metrics collector configuration
│── commands.txt # Helpful commands
│── Userdata.txt # Example test data
