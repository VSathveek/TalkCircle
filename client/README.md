# TalkCircle — Client

The frontend for TalkCircle, a real-time audio room platform for recording and
sharing conversations. Built with React, TypeScript, and Vite.

## Tech Stack

- React 19 + TypeScript
- Vite (dev server and build)
- Redux Toolkit (state management)
- React Router (routing)
- Tailwind CSS (styling)
- react-hot-toast (notifications)

## Getting Started

```bash
npm install
npm run dev
```

The app runs on the Vite dev server (default `http://localhost:5173`).

## Available Scripts

- `npm run dev` — start the development server with HMR
- `npm run build` — type-check and build for production
- `npm run preview` — preview the production build locally
- `npm run lint` — run ESLint

## Configuration

The backend base URL is configured in `src/services/APIs.tsx`. Update
`SERVER_URL` to point at your server deployment.
