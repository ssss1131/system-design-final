# Cloud File Storage System

This is a cloud file storage system with a Spring Boot backend and Angular frontend. The system provides secure file storage and management capabilities.
![image](https://github.com/user-attachments/assets/34376c1c-7181-46ab-a86b-3a7fe2d5e052)


minimum you need to have
Docker Desktop
Git
Java 17+
Node.js (with npm)

## Backend Setup

1. Clone the repository:
```bash
git clone https://github.com/ssss1131/Filo-backend
cd Filo-backend
```

2. Start the required services using Docker Compose:
```bash
docker-compose up -d
```
This will start:
- PostgreSQL database (port 5433)
- Redis server (port 6379)
- MinIO object storage (ports 9000 and 9090)

3. Build and run the Spring Boot application:
```bash
./gradlew bootRun
```

The backend will start on the default port 8080.

## Frontend Setup

1.clone
```bash
git clone https://github.com/ssss1131/Filo-frontend
cd Filo-frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
ng serve
```
if error try:
```bash
npm install -g @angular/cli
```

you can access throw localhost:4200

when you do some operation it may require reloading page to see the result and number that show progress bar is placeholder(I did not have time to do it)
