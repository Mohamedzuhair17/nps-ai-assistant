<!-- EFFECTS-BLOCK:START -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=F6F1EA&height=180&section=header&text=Nps%20Ai%20Assistant&fontSize=44&fontColor=111111&desc=End-to-end%20AI%20assistant%20pipeline%20for%20NPS%20intelligence%2C%20response%20generation%2C%20and%20workflow%20orchestration.&descSize=14&descAlignY=68" alt="Nps Ai Assistant" />
</p>

<p align="center">
  <a href="https://github.com/Mohamedzuhair17/nps-ai-assistant"><img src="https://img.shields.io/badge/Repository-111111?style=for-the-badge&logo=github" alt="repo" /></a>
  <img src="https://img.shields.io/github/stars/Mohamedzuhair17/=for-the-badge&color=111111" alt="stars" />
  <img src="https://img.shields.io/github/forks/Mohamedzuhair17/=for-the-badge&color=111111" alt="forks" />
  <img src="https://img.shields.io/github/last-commit/Mohamedzuhair17/=for-the-badge&color=111111" alt="last commit" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Stack-TypeScript-F6F1EA?style=for-the-badge&labelColor=111111&color=F6F1EA" alt="stack" />
  <img src="https://img.shields.io/badge/Engineering-Production%20Grade-111111?style=for-the-badge" alt="engineering" />
</p>
<!-- EFFECTS-BLOCK:END -->

---


# NPS - AI Assistant 🚀

An intelligent, multilingual AI-powered assistant designed to simplify information access for the National Pension System (NPS). Built with a focus on accessibility and ease of use, this platform uses state-of-the-art AI to help users navigate their pension planning in their native language.

## 🌟 Overview

The **NPS - AI Assistant** is a comprehensive solution that combines a modern frontend with a powerful RAG (Retrieval-Augmented Generation) backend. It's designed to provide accurate, context-aware information about NPS through a natural chat interface.

### 🤖 Intelligent Chat Assistant
- **Multilingual Support**: Communicates in 10+ major Indian languages (Tamil, Hindi, Telugu, Malayalam, Bengali, etc.).
- **Automatic Language Detection**: Seamlessly switches to the user's preferred language.
- **RAG Architecture**: Responses are grounded in a verified NPS knowledge base, ensuring high accuracy.
- **Local LLM Inference**: Powered by Llama 3 running locally via Ollama for privacy and speed.
- **High-Quality Translation**: Integrates Facebook's NLLB-200 model for precise cross-language communication.

### 📊 Key Features
- **Information Portal**: Access structured data on NPS rules, tiers, and benefits.
- **Pension Calculator**: Estimate future returns and monthly pension amounts.
- **Tax Guide**: Specialized assistance for tax-saving benefits under Section 80C and 80CCD.
- **Responsive Design**: Premium UI built with Tailwind CSS and shadcn/ui.

## 🏗️ Technical Stack

### Frontend
- **React 18** (TypeScript)
- **Vite** (Build Tool)
- **Tailwind CSS** (Styling)
- **shadcn/ui** (Components)
- **Framer Motion** (Animations)

### Backend
- **FastAPI** (Python 3.10+)
- **Ollama** (Llama 3 Local Inference)
- **ChromaDB** (Vector Database)
- **Sentence Transformers** (BGE Embeddings)
- **NLLB-200** (Machine Translation)
- **langdetect** (Language Identification)

## 🚀 Quick Setup

### Prerequisites
1. **Ollama**: [Download Ollama](https://ollama.ai/) and pull the model:
   ```bash
   ollama pull llama3
   ```
2. **Environment**: Python 3.10+ and Node.js 18+ are required.

### 1. Backend Configuration
Navigate to the `backend` folder and run the automated setup script:
```powershell
cd backend
.\start.ps1
```
*Note: This script initializes the virtual environment, installs dependencies, and prepares the vector database.*

### 2. Frontend Launch
Return to the project root and start the development server:
```bash
npm install
npm run dev
```

### 3. Usage
- **Frontend**: http://localhost:5173
- **API Documentation**: http://localhost:8000/docs

## 📂 Project Structure

```
nps-ai-assistant/
├── backend/              # Python FastAPI backend & RAG pipeline
│   ├── app/              # Core application logic
│   ├── scripts/          # DB initialization and test scripts
│   └── main.py           # API Entry point
├── src/                  # React Vite frontend
│   ├── components/       # UI Components
│   └── pages/            # Application views
├── SETUP_GUIDE.md        # Detailed installation steps
└── QUICK_START.md        # 5-minute fast track
```

## 🌍 Supported Languages
The assistant is optimized for:
- English (en), Tamil (ta), Hindi (hi), Telugu (te), Malayalam (ml), Bengali (bn), Marathi (mr), Gujarati (gu), Kannada (kn), Punjabi (pa).

---

**Developed by [Mohamed Zuhair](https://github.com/Mohamedzuhair17)**

**Crafted with passion to make NPS information accessible to everyone.**
Testing CodeRabbit review
