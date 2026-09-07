# SFMS

SaaS gouvernance fédérations sportives

## Structure

```
04-sfms/
├── backend/          # Express.js API (Port 3004)
│   ├── server.js
│   ├── package.json
│   └── db.json
├── web/              # React frontend (HTML + Babel standalone)
│   └── index.html
└── mobile/           # Flutter app
    └── lib/main.dart
```

## Démarrage

```bash
# Backend
cd 04-sfms/backend
npm install
npm start

# Web — Ouvrir 04-sfms/web/index.html dans un navigateur
# ou servir avec: npx serve 04-sfms/web

# Mobile
cd 04-sfms/mobile
flutter pub get
flutter run
```

## API

| Endpoint | Description |
|----------|-------------|
| GET /api/health | Health check |
| GET /api/stats | Statistiques |
