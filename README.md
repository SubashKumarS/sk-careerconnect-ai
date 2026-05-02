<div align="center">
  <h1>🚀 SK CareerConnect AI</h1>
  <h3>Your Intelligent, Multi-Lingual Career Assistant</h3>
  
  <p>
    <a href="Insert_Live_Link_Here"><img src="https://img.shields.io/badge/Live_Demo-Click_Here-blue?style=for-the-badge&logo=vercel" alt="Live Demo" /></a>
  </p>
  <p>
    <img src="https://img.shields.io/badge/Python-3.8+-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
    <img src="https://img.shields.io/badge/AI-Google_Gemini-8E75B2?style=flat-square&logo=google&logoColor=white" alt="Gemini AI" />
    <img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License" />
  </p>
</div>

---

## 🌍 Live Demo
**[Test the application live!](Insert_Live_Link_Here)**  
*(Replace this with your deployed Streamlit/Vercel link)*

---

## 💡 Why This Project Matters
Navigating career choices can be overwhelming. **SK CareerConnect AI** bridges the gap between ambition and execution by providing personalized, AI-driven guidance. It removes the language barrier by seamlessly supporting both Tamil and English, ensuring users get actionable career advice, skill gap analysis, and structured roadmaps in their native language.

---

## ✨ Key Features
- 🗺️ **Personalized Career Roadmap**: Generates a chronological, step-by-step master plan based on your skills and goals.
- 🎯 **AI Path Suggestions**: Analyzes user strengths and interests to recommend 3–5 highly suitable career choices.
- ⚖️ **Skill Gap Analyzer**: Explicitly compares your current skills against industry requirements to isolate what you need to learn.
- 💬 **Voice-Interactive Chat**: Speak your questions naturally using built-in Google Speech-to-Text integration.
- 🌐 **Native Bilingual Support**: Enter text or speak in Tamil or English. The AI automatically detects the language and replies natively.
- 📄 **PDF Report Export**: Compile your personalized strategy into a professional, downloadable PDF file in one click.

---

## 🛠️ Tech Stack
- **Frontend**: [Streamlit](https://streamlit.io/) (Fast, responsive UI)
- **AI Core**: [Google Gemini API](https://aistudio.google.com/) (`gemini-2.5-flash`)
- **Speech Processing**: Google Speech-to-Text (`SpeechRecognition`, `audio-recorder-streamlit`)
- **Language Detection**: `langdetect`
- **PDF Generation**: `fpdf2`
- **Environment Management**: `python-dotenv`

---

## ⚙️ How It Works
1. **Input Profile**: User enters their current skills, interests, and target goals (Text or Voice).
2. **Language Detection**: The system identifies if the user is communicating in Tamil or English.
3. **AI Processing**: The Gemini API acts as an expert counselor, structuring paths, identifying missing skills, and building timelines.
4. **Actionable Output**: The user receives an interactive UI breakdown and can download the finalized strategy as a PDF.

---

## 📸 Screenshots
*(Add your application screenshots here)*
> ![Dashboard](https://via.placeholder.com/800x400?text=Dashboard+Screenshot)
> ![Chat Interface](https://via.placeholder.com/800x400?text=Chat+Interface+Screenshot)

---

## 🚀 Installation & Setup

**1. Clone the repository**
```bash
git clone https://github.com/SubashKumarS/sk-careerconnect-ai.git
cd sk-careerconnect-ai
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Set up your Environment Variables**
Create a `.env` file in the root directory and add your Google Gemini API key:
```env
GEMINI_API_KEY=your_gemini_api_key_here
```

**4. Run the Application**
```bash
streamlit run app.py
```
*The app will automatically launch in your browser at `http://localhost:8506/`.*

---

## 👨‍💻 Author
**Subash kumar S**  
[GitHub Profile](https://github.com/SubashKumarS)

---

## 📜 License
This project is licensed under the MIT License. Feel free to fork, build upon, and use it for your own projects!
