# Backend - Apocalypse Shema

API REST pour le traitement des requêtes et l'intégration IA.

## 🚀 Stack
- **Framework** : FastAPI (Python)
- **Base de données** : PostgreSQL
- **Deploy** : Railway

## 🎯 Endpoints
- `POST /api/chat` : Envoi de messages à l'IA
- `GET /api/health` : Statut du serveur

## 📦 Installation
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
