# Real-Time Collaboration Platform

A Notion-style team workspace with real-time document editing, commenting, and task management.

## Features
- Real-time multi-user editing
- Commenting system
- Task assignments
- Version history
- User authentication and roles

## Tech Stack
- Frontend: React + Next.js
- Backend: Node.js + Express
- Database: PostgreSQL
- Real-time: Socket.io
- Caching: Redis

## Setup Instructions
1. Clone the repo: `git clone <repo-url>`
2. Install dependencies: `npm install` in both `/frontend` and `/backend`
3. Setup environment variables using `.env.example`
4. Seed the database: `node backend/seed.js`
5. Start backend: `npm run dev` in `/backend`
6. Start frontend: `npm run dev` in `/frontend`
7. Open `http://localhost:3000`

## Notes
- Secrets have been removed for submission
- Demo data included in `/backend/seed.js`
