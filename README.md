# About Student List Application

This project demonstrates a **Dockerized microservices architecture** using Docker Compose to orchestrate a multi-container application.  It showcases Docker best practices for containerization, networking, and service orchestration.

## 🐳 Docker-Powered Architecture

The Student List application is built entirely with **Docker** and **Docker Compose**, featuring:

- **Multi-container orchestration** - Seamless coordination between frontend and backend services
- **Custom Docker networking** - Isolated bridge network for secure inter-container communication
- **Volume mounting** - Persistent data management and live code updates
- **Environment-based configuration** - Containerized environment variables for flexibility
- **Service dependencies** - Proper startup order management with `depends_on`

## Technology Stack

- **Frontend**: PHP/Apache web server (Dockerized)
- **Backend**: Python API (Custom Docker image)
- **Orchestration**: Docker Compose v3. 3
- **Networking**: Docker Bridge Network

## Key Docker Features Demonstrated

✅ Multi-stage service deployment  
✅ Custom Docker image creation (`api-pozos:1`)  
✅ Volume mapping for development workflow  
✅ Container networking and service discovery  
✅ Port exposure and mapping  
✅ Environment variable injection  
✅ Container dependency management  

This project serves as an excellent learning resource for understanding Docker containerization, microservices architecture, and Docker Compose orchestration patterns. 
