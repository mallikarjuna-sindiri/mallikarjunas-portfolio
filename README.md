# Sindiri Mallikarjuna – Portfolio

Full-stack personal portfolio with a React + Vite + Tailwind + Framer Motion frontend (`client`) and a minimal Express backend (`server`).

## Structure

- `client` – Vite React SPA with Tailwind CSS, animated hero, skill radar, journey timeline, project case-study modals, floating dock and contact form.
- `server` – Simple Express API with `/health` endpoint, suitable for deployment on Render or similar platforms.

## Getting Started

### Client

```bash
cd client
npm install
npm run dev
```

### Server

```bash
cd server
npm install
npm start
```

## Build & Deploy

- **Vercel (frontend)**: Point Vercel to the `client` folder. Build command: `npm run build`. Output directory: `dist`. Vercel uses `vercel.json` and exposes `/api/health`.
- **Render (backend)**: Create a new Node web service from `server`. Start command: `npm start`.

## Contact

- Email: `mallikarjuna.sindiri@gmail.com`
- GitHub: `mallikarjuna-sindiri`
- LinkedIn: `mallikarjuna-sindiri`
