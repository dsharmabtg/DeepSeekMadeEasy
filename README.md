# 🚀 DeepSeekMadeEasy - AI Applications Hub  

This repository showcases **end-to-end AI-powered projects** built using the **DeepSeekr1:7B model** (running locally with [Ollama](https://ollama.ai/)) and deployed with **Gradio** and **FastAPI** (`app.py` for each project).  

These projects demonstrate real-world applications of **Natural Language Processing (NLP)**, **Conversational AI**, and **Intelligent Assistants**, making it easier for developers to explore and build AI-powered solutions locally.  

---

## 🔧 Tech Stack  

- **Model**: [DeepSeekr1:7B](https://ollama.ai/library/deepseek) (runs locally with Ollama)  
- **Frontend**: [Gradio](https://www.gradio.app/) (interactive UI)  
- **Backend**: [FastAPI](https://fastapi.tiangolo.com/) (REST APIs with `app.py`)  
- **Language**: Python 3.10+  

---

## 📂 Project Structure  

Each folder in the repository contains a self-contained project with:  
- `app.py` → FastAPI backend service  
- `app_type_name.py` (if applicable) → Gradio interface for interaction  
- `requirements.txt` → Dependencies  
- `README.md` → Project-specific details  

---

## 🧩 List of Projects  

### 📝 Text Processing  
1. [**AI-Powered Text Summarizer**](https://github.com/dsharmabtg/DeepSeekMadeEasy/tree/master/01_AI-Powered_Text_Summarizer)  
2. [**AI-Based Text Generation**](https://github.com/dsharmabtg/DeepSeekMadeEasy/tree/master/02_AI-Based_Text_Generation)  
3. [**AI-Powered Grammar & Spell Checker**](https://github.com/dsharmabtg/DeepSeekMadeEasy/tree/master/03_AI-Powered_Grammer_And_SpellChecker)  
4. [**AI-Powered Named Entity Recognition (NER)**](https://github.com/dsharmabtg/DeepSeekMadeEasy/tree/master/04_AI-Powered_NamedEntityRecognition)  
5. [**AI-Powered Sentiment Analysis**](https://github.com/dsharmabtg/DeepSeekMadeEasy/tree/master/05_AI-Powered_Sentiment_Analysis)  

### 🤖 Conversational Agents  
6. **Customer Support ChatBot**  
7. **Personal AI Assistant**  
8. **AI Legal Assistant**  
9. **Medical Symptom Checker**  
10. **E-commerce Product Recommendation Bot**  
11. **Automated Email Responder**  

### 📄 Productivity Tools  
12. **AI-Powered Resume Generator**  
13. **AI-Based Meeting Minutes Generator**  
14. **Automated PDF Text Extractor**  
15. **AI Content Writer**  

### 💻 Developer Tools  
16. **Code Auto-Completer Assistant**  
17. **SQL Query Generator**  
18. **AI Code Debugger**  
19. **AI-Based Documentation Generator**  
20. **AI-Powered API Tester**  

### 📊 Business & Research Tools  
21. **AI-Based Customer Feedback Analyzer**  
22. **Realtime AI News Summarizer**  
23. **AI-Based Financial Report Analyzer**  
24. **AI-Powered Job Application Screener**  
25. **AI-Powered Research Paper Summarizer**  

---

## ⚡ Getting Started  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/dsharmabtg/DeepSeekMadeEasy.git
cd DeepSeekMadeEasy
```

### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 3️⃣ Run Any Project  
Navigate to the project folder and start the FastAPI app:  
```bash
cd 01_AI-Powered_Text_Summarizer
uvicorn app:app --reload
```

For Gradio UI (if included):  
```bash
python app_type_name.py
```

---

## 🖥️ Running DeepSeekr1:7B Locally  

1. Install [Ollama](https://ollama.ai/)  
2. Pull the model:  
   ```bash
   ollama pull deepseekr1:7b
   ```
3. Start using the model in each project’s backend (`app.py`).  

---

## 🌟 Highlights  

- ✅ **25 ready-to-use AI projects**  
- ✅ **Runs 100% locally with Ollama**  
- ✅ **Seamless FastAPI + Gradio integration**  
- ✅ **Customizable for research & production**  

---

## 📌 Future Improvements  

- Adding Docker support for easier deployment  
- Extending projects with LangChain integration  
- GPU-optimized version for faster inference  

---

## 🤝 Contributing  

Contributions are welcome!  
- Fork the repo  
- Create a feature branch  
- Submit a PR 🚀  

---

## 📜 License  

This project is licensed under the **GNU GENERAL PUBLIC LICENSE** – free to use and modify.  
