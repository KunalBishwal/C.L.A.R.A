# C.L.A.R.A – Conversational Learning AI for Recruitment Assistance

**C.L.A.R.A** (Conversational Learning AI for Recruitment Assistance) is an AI-powered **mock interview assistant** that helps students and job seekers practice job interviews in a realistic environment.  
It uses **voice interaction, AI feedback, and real-time streaming** to simulate interview scenarios and provide constructive feedback.

👉 Live Demo: [clara-ai-interviewer.vercel.app](https://clara-ai-interviewer.vercel.app/)

---

## ✨ Features

- 🎙️ **Voice-based Interview Practice** – Speak naturally, get real-time AI responses.
- 🤖 **AI Feedback** – Instant analysis on your answers (tone, clarity, relevance).
- 🔄 **WebRTC/WebSocket Streaming** – Low-latency voice streaming with reconnect support.
- 🧩 **Next.js + Node.js Backend** – Fast, scalable, and production-ready.
- 🎨 **Modern UI** – Built with TailwindCSS and Framer Motion.
- 🔐 **Authentication** – Secure sign-in/sign-up flow.
- 📊 **Feedback Dashboard** – Review transcripts and performance insights.

---

## 🛠️ Tech Stack

- **Frontend**: [Next.js 14](https://nextjs.org/) + [React](https://reactjs.org/)  
- **Styling**: [TailwindCSS](https://tailwindcss.com/) + custom theme tokens  
- **Fonts**: Google Fonts (Mona Sans)  
- **Auth**: NextAuth.js (Email/Password)  
- **Backend**: Node.js + Express  
- **Database**: MySQL (eventually with Prisma ORM)  
- **AI/Voice**:
  - Whisper (Speech-to-Text)  
  - TTS (Text-to-Speech)  
  - VAD (Voice Activity Detection)  
  - LangChain / LiveKit / Pipecat (for orchestration & real-time streaming)

---

## 📂 Project Structure

```bash
.
├── app/                 # Next.js App Router pages & layouts
│   ├── layout.tsx       # Root layout with global styles & dark mode
│   ├── page.tsx         # Landing / auth entry
│   └── ...
├── components/          # UI components (buttons, cards, etc.)
├── styles/
│   └── globals.css      # Tailwind + theme tokens + dark mode
├── public/              # Static assets (patterns, logos, etc.)
└── README.md
