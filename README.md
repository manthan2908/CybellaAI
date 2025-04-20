# 🧠 CybellaAI - Voice Therapy Assistant

**CybellaAI** is an AI-powered therapy assistant designed to provide emotional support through natural conversation. It uses real-time **facial emotion recognition** and **voice interaction** to respond intelligently to the user's emotional state.


---

## 🌟 Features

- 🎭 Facial emotion detection using face-api.js
- 🗣️ Voice transcription and text-to-speech response
- 💬 Combined voice + face emotion analysis
- 📊 Real-time emotion feedback display
- 💻 Fully responsive interface (desktop + mobile)
- 🚀 Deployable via AWS Amplify or GitHub Pages

---

## 🧠 Technologies Used

| Area | Stack |
|------|-------|
| Frontend | React + TypeScript |
| UI Library | Tailwind CSS + shadcn/ui + Radix UI |
| Facial Recognition | face-api.js (TinyFaceDetector, FaceExpressionNet, FaceLandmark68Net) |
| Voice Interface | Web Speech API (SpeechRecognition + SpeechSynthesis) |
| Charting | Recharts |
| Tooling | Vite, ESLint, PostCSS |

---

## 🛠️ Getting Started

### Prerequisites
- Node.js (v18+)
- npm

### Installation

```bash
# Clone the repo
git clone https://github.com/GajeraRishi/CybellaAI.git
cd CybellaAI

# Install dependencies
npm install

# Start development server
npm run dev
