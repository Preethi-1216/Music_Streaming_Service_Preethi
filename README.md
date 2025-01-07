# Music_Streaming_Service_Preethi
A modern music streaming platform built with Node.js, React, and PostgreSQL.
Features
User authentication and profiles
Music playback with playlist management
Artist and album browsing
Search functionality
User library management
Social features (following, sharing)
Tech Stack
Frontend: React, Redux, Tailwind CSS
Backend: Node.js, Express
Database: PostgreSQL
Authentication: JWT
Storage: AWS S3
Caching: Redis
Setup
Clone repository
Install dependencies:
cd frontend && npm install
cd ../backend && npm install
Configure environment variables:
cp .env.example .env
Start services:
docker-compose up -d    # Start PostgreSQL and Redis
npm run dev            # Start development server
API Documentation
See api-docs.md for detailed API documentation.

Project Structure
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   └── services/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   └── services/
└── docker/
