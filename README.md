# Frontend

This folder contains the React + Vite frontend for the AI-First Healthcare CRM HCP Module.

## Run locally

```bash
npm install
copy .env.example .env
npm run dev
```

Set the frontend environment variable in `frontend/.env`:

```env
VITE_API_BASE_URL=http://localhost:8000/api
```

## Main areas

- `src/app/components`
  UI for form entry, chat-assisted logging, and interaction history
- `src/app/services`
  API client, AI agent adapter, and local extraction helpers
- `src/app/store`
  Redux slices for form and chat state
- `src/styles`
  Theme, Tailwind, and font styles
