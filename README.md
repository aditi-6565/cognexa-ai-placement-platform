# COGNEXA V2 — AI Placement Preparation & Assessment Platform

A polished frontend prototype focused on the multi-agent AI Group Discussion experience.

## Run locally

```powershell
cd C:\cognexa-v2
npm install
npm run dev
```

Open the local Vite URL shown in the terminal.

For a production build:

```powershell
npm run build
npm run preview
```

## Prototype features

- Student dashboard
- Aptitude practice and assessment flow
- Multi-agent AI Group Discussion visualization
- AI personas with distinct roles
- Animated speaking state and conversation timeline
- Student text contribution
- Browser Speech Recognition integration when supported
- AI evaluation report
- Live student-to-student GD UI
- Performance analytics
- Admin / placement dashboard
- Responsive dark glassmorphism interface

## Important

This is a frontend demonstration prototype. The AI responses are simulated locally for the demo.

For the full system, connect:
- Groq API through a Node/Express backend
- PostgreSQL + Prisma
- Socket.IO for real-time events
- WebRTC for live student audio/video
- Web Speech API for browser speech recognition

Never place a Groq secret key directly in the React frontend.
