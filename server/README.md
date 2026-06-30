# TalkCircle — Server

The backend for TalkCircle. Handles real-time signaling, recording processing,
video pre-rendering with FFmpeg, asset storage on S3, and email notifications.

## Tech Stack

- Node.js + Express 5 + TypeScript
- Socket.IO (real-time signaling)
- FFmpeg (`fluent-ffmpeg` / `ffmpeg-static`) for video rendering
- AWS S3 (`@aws-sdk/client-s3`) for asset storage
- Nodemailer for transactional email
- node-cron for scheduled cleanup

## Getting Started

```bash
npm install
npm run dev
```

`npm run dev` compiles the TypeScript sources and runs `dist/index.js`.

## Available Scripts

- `npm run build` — install dependencies and compile TypeScript
- `npm run dev` — build and run the server
- `npm start` — run the compiled server

## Environment Variables

Create a `.env` file in this directory with at least:

- Mail credentials for Nodemailer (host, user, password)
- AWS credentials and bucket/region for S3 asset storage
- The client origin allowed by CORS
