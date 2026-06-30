# TalkCircle

TalkCircle is a real-time audio room platform where users can create rooms, talk,
record their conversations, and receive a downloadable rendered video of each
session by email.

## Project Structure

```
TalkCircle/
├── client/   # React + TypeScript + Vite frontend
└── server/   # Node.js + Express + TypeScript backend
```

## Features

- Create and join real-time audio rooms
- Record room sessions
- Server-side video pre-rendering of recordings
- Email delivery of rendered video download links
- Recordings access page

## Getting Started

Run the client and server separately. See each package's README for details:

- [client/README.md](client/README.md)
- [server/README.md](server/README.md)

### Quick start

```bash
# Frontend
cd client && npm install && npm run dev

# Backend
cd server && npm install && npm run dev
```

## Environment Variables

The server requires a `.env` file with credentials for the mail service and the
S3-compatible storage used for rendered assets. See `server/README.md`.
