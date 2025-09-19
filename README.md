# Symptom-Tracker-APP-Kotlin-mobile-app-Backend

---

# Symptom Tracker App – Backend

This repository contains the **Spring Boot backend API** for the Symptom Tracker App.  
It provides secure data storage, user management, and API endpoints consumed by the Android frontend.

---

## ✨ Features
- 👤 User authentication and authorization  
- 📝 Symptom data logging and retrieval  
- 🔐 Secure REST API endpoints for the frontend  
- 🛠 Planned: AI/ML modules for pattern recognition and predictive insights  

---

## 🛠 Tech Stack
- **Language**: Java 21  
- **Framework**: Spring Boot  
- **Database**: PostgreSQL (or H2 for dev)  
- **Security**: Spring Security / JWT (planned)  
- **Build Tool**: Maven  

---

## 🚀 Getting Started

### Prerequisites
- JDK 21+  
- Maven 3.9+  
- Docker (optional, for DB and containerized testing)  

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/MarkpaulNduthu/symptom-tracker-backend.git
2. Configure environment variables in application.properties or .env:
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/symptomdb
   spring.datasource.username=yourusername
   spring.datasource.password=yourpassword

# AI integration (optional)
   OPENAI_API_KEY=your_api_key
3. Run the app:
   ```bash
   mvn spring-boot:run
   ```
## 📡 API Endpoints
   ```markdown
   Method	Endpoint	Description
   POST	/api/v1/auth/register	Register a new user
   POST	/api/v1/auth/login	Authenticate and get token
   GET	/api/v1/symptoms	Fetch user symptoms
   POST	/api/v1/symptoms	Add a new symptom entry

   (More endpoints coming soon)
   ```
## 🛤 Roadmap
   ```markdown
    JWT-based authentication
   
    Symptom analytics dashboard
   
    AI/ML-powered predictions
   
    Deployment to cloud (Render/AWS)
   ```
## 🤝 Contributing
   Contributions are welcome! Please open an issue or submit a pull request.
