<div align="center">
  <h1>🚀 SK CareerConnect AI</h1>
  <h3>Empowering Careers with AI-Driven Clarity</h3>
  
  <p>
    <a href="Insert_Live_Link_Here"><img src="https://img.shields.io/badge/Live_Demo-Click_Here-blue?style=for-the-badge&logo=vercel" alt="Live Demo" /></a>
  </p>
  <p>
    <img src="https://img.shields.io/badge/Python-3.8+-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
    <img src="https://img.shields.io/badge/Gemini_AI-8E75B2?style=flat-square&logo=google&logoColor=white" alt="Gemini AI" />
    <img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License" />
  </p>
</div>

---

## 🛑 The Problem
Choosing a career path and figuring out *how* to get there is overwhelming. Millions of students and professionals struggle with a lack of mentorship, confusing industry requirements, and language barriers that prevent them from accessing quality career guidance. 

## 💡 Our Solution
**SK CareerConnect AI** is an intelligent, multi-lingual career assistant that democratizes career planning. By combining the power of **Google Gemini AI** with native bilingual support (English/Tamil) and voice interaction, we transform confusion into execution. 

We don't just give generic advice; we generate personalized, actionable, step-by-step master plans.

---

## ✨ Hackathon Highlights & Core Features
- 🎯 **AI Path Discovery**: Don't know what to do? The AI analyzes your strengths and recommends 3–5 highly tailored career paths.
- ⚖️ **Skill Gap Analyzer**: Pinpoints exactly what you lack by explicitly comparing your current skills against strict industry requirements.
- 🗺️ **Chronological Roadmaps**: Generates a clear, milestone-driven execution plan (e.g., 3-month and 6-month timelines).
- 🗣️ **Voice-Interactive Chat**: Speak your questions naturally using Google Speech-to-Text integration.
- 🌐 **Native Bilingual Support**: Seamlessly switch between Tamil and English. The AI automatically detects your language and replies natively.
- 📄 **1-Click PDF Export**: Instantly compile your personalized strategy into a professional, downloadable PDF report.

---

## 🛠️ Architecture & Tech Stack
Built for speed, accessibility, and scalability:
- **Frontend**: [Streamlit](https://streamlit.io/) — *Clean, responsive, and data-driven UI*
- **AI Engine**: [Google Gemini API](https://aistudio.google.com/) (`gemini-2.5-flash`) — *Lightning-fast generative inference*
- **Speech Processing**: Google STT (`SpeechRecognition`, `audio-recorder-streamlit`)
- **Language Detection**: `langdetect`
- **Document Generation**: `fpdf2`

---

## ⚙️ How It Works (The User Journey)
1. **Input**: User shares their skills, interests, and goals via Text or Voice.
2. **Detect**: The system instantly identifies the user's preferred language (English or Tamil).
3. **Analyze**: The Gemini AI processes the profile to structure paths, identify skill gaps, and build timelines.
4. **Execute**: The user interacts with the UI breakdown and downloads their finalized strategy as a PDF report.

---

## 🚀 Quick Start Guide

**1. Clone the repository**
```bash
git clone https://github.com/SubashKumarS/sk-careerconnect-ai.git
cd sk-careerconnect-ai
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Configure Environment**
Create a `.env` file in the root directory and add your Google Gemini API key:
```env
GEMINI_API_KEY=your_gemini_api_key_here
```

**4. Boot the Application**
```bash
streamlit run app.py
```
*The app will automatically launch at `http://localhost:8506/`.*

---

## 👨‍💻 Developer
**Subash kumar S**  
[GitHub Profile](https://github.com/SubashKumarS)

---

## 📜 License
This project is licensed under the MIT License. Built for the hackathon community to inspire and innovate!
