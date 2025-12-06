# 📸 InstaLite – Instagram Benzeri Uygulama

Bu proje; FastAPI backend, React Native mobil uygulama ve React web frontend içeren tam bir Instagram benzeri uygulama başlangıç paketidir.

## 🚀 Kurulum

### Backend
```bash
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload
cd mobile
npm install
npm start
cd web
npm install
npm run dev
backend/
mobile/
web/
docker-compose.yml
README.md
.gitignore
POST /api/auth/register
POST /api/auth/login
GET /api/posts/feed
