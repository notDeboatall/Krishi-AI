# Krishi AI - Personal Enhanced Version 🌾

Krishi AI is a comprehensive digital ecosystem designed to empower farmers with AI-driven insights, real-time data, and traditional wisdom. This project is an independent, enhanced version of an earlier team collaboration, refined to demonstrate advanced full-stack development and AI integration.

## 🌟 Project Overview

Krishi AI bridges the gap between traditional farming and modern technology. It provides a centralized platform where farmers can access critical information—from disease diagnosis to market prices—using an intuitive, multi-lingual interface.

## 🚀 Key Features

- **Intelligent Crop Doctor**: A state-of-the-art diagnostic tool that uses Hugging Face vision models to identify crop diseases from leaf images and provide actionable treatment advice.
- **AI Agriculture Chat**: A multi-lingual (Hindi, Odia, English) assistant powered by Groq and Llama 3, offering expert advice on farming practices.
- **Live Mandi Prices**: Real-time market data fetched via the `Data.gov.in` API, featuring granular state and district-level filtering.
- **Hyper-Local Weather**: Precise weather forecasts to help farmers optimize harvesting and irrigation schedules.
- **Regional Voice Assistant**: Specialized support for regional Odia-speaking farmers using Google Cloud's Speech-to-Text and Text-to-Speech services.
- **Government Schemes Directory**: A curated database of agricultural schemes with direct links for application.

## 🛠️ Tech Stack

- **Frontend**: React.js, Vite, TypeScript, Tailwind CSS, Framer Motion (for smooth animations), Lucide Icons.
- **Backend**: Node.js, Express.js, Multer (robust file handling).
- **AI/ML Integration**: Groq (Llama 3), Hugging Face (Vision Models), Google Gemini API.
- **Third-Party Services**: Google Cloud Platform (STT/TTS), Data.gov.in Open API.

## 💡 My Contributions & Refinements

- **AI Model Integration**: Orchestrated the integration of multiple AI providers (Groq, HF, Gemini) to provide a seamless user experience for both text and image-based queries.
- **API Optimization**: Refined the backend logic for fetching and filtering real-time mandi data, ensuring low latency and reliable fallback mechanisms.
- **Enhanced UX/UI**: Polished the frontend components using Tailwind CSS and Framer Motion to create a professional, "premium" feel suitable for a portfolio.
- **Multi-lingual Support**: Implemented robust handling for regional languages to ensure accessibility for the primary user base.
- **Codebase Cleanup**: Standardized the project structure, optimized environment variable management, and established a clean development workflow.

## 📈 Future Improvements

- **IoT Integration**: Supporting real-time soil moisture and nutrient sensors for precision agriculture.
- **Direct Marketplace**: Developing a peer-to-peer marketplace for farmers to sell produce directly to consumers.
- **Community Hub**: A forum for farmers to share local knowledge and peer-to-peer advice.

---

## ⚙️ Setup & Installation

### 1. Prerequisites
- Node.js 18+
- API Keys: Groq, Hugging Face, Gemini, Data.gov.in.

### 2. Environment Variables

**Root Directory (`.env`):**
```env
VITE_GEMINI_API_KEY=your_key
```

**Backend Directory (`backend/.env`):**
```env
GROQ_API_KEY=your_key
HF_API_KEY=your_key
GEMINI_API_KEY=your_key
DATA_GOV_IN_API_KEY=your_key
PORT=3001
```

### 3. Running Locally

```sh
# Install Frontend dependencies
npm install

# Install Backend dependencies
cd backend
npm install

# Start development servers (in separate terminals)
# Frontend:
npm run dev

# Backend:
npm run dev
```