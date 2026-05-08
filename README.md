# SaaS CRM – AI Powered CRM & Sales Pipeline Platform

## Features
- Role-based authentication (Admin/Manager/User)
- Leads & Deals management
- Contacts and Activities tracking
- AI-powered lead scoring & email generation
- JWT authentication with refresh tokens
- Swagger API documentation

## Tech Stack
Frontend:
- React (Vite)
- Tailwind CSS
- React Query
- Zustand

Backend:
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Swagger/OpenAPI

## Installation

### Frontend
```bash
cd frontend
npm install
npm run dev
```

### Backend
```bash
cd backend
npm install
npm run dev
```

## Environment Variables

Create a `.env` file in backend:

```env
PORT=5000
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret
REFRESH_TOKEN_SECRET=your_secret
```

## API Docs
`/api/v1/docs`
