🌍 India Address API SaaS Platform

A production-ready SaaS platform providing structured Indian geographical data (State → District → Subdistrict → Village) via secure REST APIs.

## 🚀 Features

- 4.5L+ village records
- Hierarchical location APIs
- Secure API Key Authentication
- Rate Limiting (Free vs Premium)
- Usage Tracking
- Analytics Dashboard
- Fast Search API
- Modern React UI

## 🛠 Tech Stack

- Backend: FastAPI (Python)
- Database: PostgreSQL
- Frontend: React.js
- Data Processing: Pandas

## 📡 API Endpoints

- `GET /states`
- `GET /districts/{state_id}`
- `GET /subdistricts/{district_id}`
- `GET /villages/{subdistrict_id}`
- `GET /search/villages?q=keyword`
- `GET /analytics`

## 🔐 Security

- API Key Authentication
- Request Tracking
- Rate Limiting System

## ▶️ Run Locally

### Backend
```bash
uvicorn main:app --reload
Frontend
cd frontend
npm start