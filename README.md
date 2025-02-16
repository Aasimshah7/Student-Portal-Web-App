# Student Portal Web App

## Overview  
This project sets up a web application using Flask, an API using FastAPI, and a PostgreSQL database. The entire application is containerized using Docker for easy deployment and management.  

## Features  
- Flask-based frontend  
- FastAPI backend  
- PostgreSQL database integration  
- Containerized using Docker  
- Managed with Docker Compose  

## Setup Instructions  

### Prerequisites  
Ensure you have the following installed on your system:  
- Docker  
- Docker Compose  

### Steps to Run  

#### **1. Clone the Repository**  
```sh  
git clone <repository-url>  
cd <repository-name>  
```

#### **2. Build and Run with Docker Compose**  
```sh  
docker-compose up --build  
```

#### **3. Access the Services**  
- Web Application: [http://127.0.0.1:8090](http://127.0.0.1:8090)  
- API Documentation: [http://127.0.0.1:8080/docs](http://127.0.0.1:8080/docs)  
- Database Adminer: [http://127.0.0.1:8091](http://127.0.0.1:8091)  

## Project Structure  
```
├── web-app/           # Flask frontend application  
├── api/               # FastAPI backend service  
├── database/          # PostgreSQL database setup  
├── docker-compose.yaml # Docker Compose configuration  
├── .env               # Environment variables  
```

