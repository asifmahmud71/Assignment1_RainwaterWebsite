# Rainwater Convention — Frontend (Concise)

Prerequisites
- Node.js & npm
- Backend running (default: http://localhost:5000)

Install
```bash
cd f:\Assignment1_RainwaterWebsite\frontend
npm install
```

Env
- Optional: create `.env` with
  REACT_APP_API_URL=http://localhost:5000

Scripts
- npm start      # dev server (http://localhost:3000)
- npm run build  # production build

Backend endpoints used
- GET  /api/registrations
- POST /api/registrations
- DELETE /api/registrations/:id
- POST /api/admin/login

Notes
- Ensure CORS enabled on backend.
- Install icons if missing: npm install lucide-react
- "Register Now" navigates to the registration page via App state.
