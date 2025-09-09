# README.md contents

# AstroAlert Project

This project is an AI-Powered Space Debris Early Warning System MVP, designed to monitor and alert users about space debris. It consists of a frontend built with React, TypeScript, and Tailwind CSS, and a backend powered by FastAPI.

## Project Structure

```
astreoalert
├── frontend
│   ├── src
│   │   ├── components
│   │   │   ├── ui
│   │   │   ├── layout
│   │   │   └── debris
│   │   ├── hooks
│   │   │   └── useDebrisData.ts
│   │   ├── types
│   │   │   └── index.ts
│   │   ├── utils
│   │   │   └── index.ts
│   │   ├── pages
│   │   │   ├── dashboard
│   │   │   └── alerts
│   │   ├── app.tsx
│   │   └── main.tsx
│   ├── package.json
│   ├── tailwind.config.js
│   └── tsconfig.json
├── backend
│   ├── src
│   │   ├── api
│   │   │   └── routes.py
│   │   ├── models
│   │   │   └── debris.py
│   │   ├── services
│   │   │   └── prediction.py
│   │   └── main.py
│   ├── requirements.txt
│   └── Dockerfile
├── docker-compose.yml
└── README.md
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd astreoalert
   ```

2. **Frontend Setup:**
   - Navigate to the frontend directory:
     ```
     cd frontend
     ```
   - Install dependencies:
     ```
     npm install
     ```
   - Start the frontend application:
     ```
     npm start
     ```

3. **Backend Setup:**
   - Navigate to the backend directory:
     ```
     cd backend
     ```
   - Install dependencies:
     ```
     pip install -r requirements.txt
     ```
   - Start the FastAPI application:
     ```
     uvicorn src.main:app --reload
     ```

4. **Docker Setup:**
   - To run the application using Docker, ensure Docker is installed and running, then execute:
     ```
     docker-compose up --build
     ```

## Usage

After running the application, you can access the frontend at `http://localhost:3000/` and the backend API at `http://localhost:8000/`.

## License

This project is licensed under the MIT License.