# Textual Numeric Analysis Engine

Full-stack text analysis engine that indexes words with numeric values and enables fast lookup and contextual search across a large dataset.

---

## 🚀 Features
- Numeric indexing of textual data
- Fast search by numeric value
- Contextual results including word and source location
- REST API for structured queries
- Web interface for interactive exploration
- Optimized database queries for efficient lookups

---

## 🛠 Tech Stack

### Backend
- Node.js
- Express.js
- TypeScript
- MongoDB Atlas

### Frontend
- React
- TypeScript
- Tailwind CSS

### DevOps
- Render (Backend)
- Vercel (Frontend)
- Git & GitHub
- Environment variables (.env)
- CORS configuration

---

## 🧠 Architecture Overview
Textual data is preprocessed and stored in MongoDB with numeric indexes to allow fast lookup by value.  
The backend exposes a REST API that performs indexed queries and returns contextual results, which are consumed by a React-based frontend.

---

## 🌍 Live Demo
- Frontend: [https://gematria-explorer.vercel.app](https://react-express-fullstack-app.vercel.app/)
- Backend API: [https://gematria-explorer-backend.onrender.com](https://gematria-explorer-backend.onrender.com/api/words/gematria/)

---

## 🧪 Local Development

```bash
# Clone repository
git clone https://github.com/KingZahard01/textual-numeric-analysis-engine.git

# Backend
cd backend
npm install
npm run dev

# Frontend
cd frontend
npm install
npm run dev

