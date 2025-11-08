# 🧠 TubeWise — Intelligent Learning from YouTube Videos

**TubeWise** is an AI-powered platform developed by **Amir Khosravi** that helps users quickly summarize, interact with, and generate new content from YouTube videos.

---

## 🚀 Key Features

- **Smart Summarization:** Generate accurate summaries of YouTube videos with key points and timestamps.  
- **Multi-Video Comparison:** Compare multiple videos to identify shared topics and key differences.  
- **Interactive Chat:** Ask natural-language questions about a video and receive precise, time-linked answers.  
- **Content Generation:** Automatically create new content (tweets, blog drafts, LinkedIn posts, etc.) from video summaries.  
- **Personal Dashboard:** Manage saved videos, summaries, and interactions in one place.  
- **Multilingual Support:** Interface available in English, Spanish, and Portuguese.




---

## 🏗️ Technical Architecture

TubeWise follows a modern, scalable multi-service design.

### 🧩 AI Service (Backend)

- **FastAPI** – lightweight and efficient API framework for serving AI models.  
- **Multi-Agent Architecture** – built using **LangGraph** for orchestrating intelligent agent workflows.  
- **Language Models** – supports both **Hugging Face** and **OpenAI** APIs.  
- **Transcript Extraction** – powered by the **YouTube Transcript API** to fetch subtitles and video transcripts.

### 💻 Web Client (Frontend)

- **Next.js** – React-based framework for fast and SEO-friendly interfaces.  
- **Chakra UI** – elegant and responsive React UI component library.  
- **next-i18next** – full multilingual support and localization handling.  
- **TypeScript** – ensures type safety and cleaner development.

---

## ⚙️ Installation & Setup

### 🧱 Prerequisites

- Node.js (v16 or higher)  
- Python (v3.9 or higher)  
- Docker (optional, for containerized setup)

---

### 🧠 Setting Up the AI Service

1. **Install Python dependencies**
```bash
cd services/auth-service
node src/app.js

cd services/ai-service
python simple_app.py

cd web-client
npm run dev


