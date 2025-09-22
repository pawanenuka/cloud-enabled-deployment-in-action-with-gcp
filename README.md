# Course Details — Quick Start

Demo video: [How this project should work](https://drive.google.com/file/d/1oxquqLTIVec9id1bHCdJvJ0UWEHCgvke/view?usp=drive_link)

Prereqs: Java 17+, Maven/Gradle, Node.js 18+, npm
## Student Information

- **Name:** Pawan Enuka
- **Student Registration Number:** 2301671111
- **Email Address:** enukapawan@gmail.com
---

## Backend (API)
```bash
cd backend           # or: cd course-details / course-details-service
# Ensure DB/GCP config is set (e.g., gcp.properties or env vars)
./mvnw spring-boot:run    # or: ./gradlew bootRun
# Runs on http://localhost:8080
```

## Frontend (UI)
```bash
cd frontend         # or: cd ui
npm install
# Optional (set backend URL):
# export VITE_API_BASE_URL=http://localhost:8080
# or: export REACT_APP_API_BASE_URL=http://localhost:8080
npm run dev         # or: npm start
# Opens on http://localhost:5173 or http://localhost:3000
```