# 🚀 SK CareerConnect AI
**Your Personal AI-Powered Career Assistant**

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue.svg)](Insert_Live_Link_Here)
[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)]()
[![Streamlit App](https://img.shields.io/badge/Streamlit-App-FF4B4B.svg)]()

Welcome to **SK CareerConnect AI**, an intelligent, multi-lingual web application designed to guide your career path from confusion to execution. Combining OpenAI's highly capable generative infrastructure with an incredibly intuitive dual-language setup (English/Tamil), CareerConnect acts as an all-in-one AI career counselor!

---

## ✨ Features

- 🗺️ **Personalized Career Roadmap**
  Provide your skills, interests, and goals, and instantly receive a chronological, step-by-step master plan of execution.
  
- 💬 **Voice-Interactive AI Chat**
  Built tightly alongside **Google Speech-to-Text**, simply speak your questions directly to the AI assistant perfectly natively!
  
- 🧭 **Path Discovery Engine**
  Don't know what career fits you? Describe yourself plainly and the AI will analyze your strengths to suggest 3 to 5 highly matching career choices.
  
- ⚖️ **Skill Gap Analyzer**
  Compare your current baseline explicitly against the market requirements for a target career and isolate the exact tools/skills you are missing.
  
- 🌐 **Native Bilingual Interface & Detection**
  Leveraging the **Google Translate API**, input text natively in Tamil (அல்லது ஆங்கிலம்!), and the AI dynamically replies exactly in the language you need.
  
- 📄 **1-Click PDF Report Export**
  Compile the strategy—Gap Analysis, Roadmap, and Job suggestions—into a professional, downloadable PDF file via **FPDF**.

---

## 🛠️ Tech Stack

- **Frontend/UI:** [Streamlit](https://streamlit.io/)
- **AI Core Processor:** [OpenAI API](https://platform.openai.com/) (`gpt-3.5-turbo`)
- **Speech Processing:** `audio-recorder-streamlit` + `SpeechRecognition` (Google STT)
- **Language Detection:** `googletrans`
- **Environment Settings:** `python-dotenv`
- **PDF Infrastructure:** `fpdf2`

---

## 🚀 How to Run Locally

Follow these instructions to successfully boot the application on your own machine.

**1. Clone the repository**
```bash
git clone https://github.com/your-username/SK-CareerConnect-AI.git
cd SK-CareerConnect-AI
```

**2. Install dependencies**
Use `pip` to automatically install the exact requirements needed:
```bash
pip install -r requirements.txt
```

**3. Configure your Environment Variables**
Create a `.env` file in the root directory and securely paste your OpenAI API Key:
```env
OPENAI_API_KEY=your_openai_api_key_here
```
*(Alternatively, you can completely skip this step and paste your API key directly into the application's sidebar once it launches!)*

**4. Boot the Application**
```bash
streamlit run app.py
```
*The app will automatically pop up in your default web browser at `http://localhost:8501/`.*

---

## 🌍 Live Demo
Test out the working application securely inside the browser!  
👉 **[View Live Demo Here](#)** *(Replace this link with your platform deployment)*

---

### 📝 Contributors & License
Project built and designed by Subash kumar S. Available as open-source.
