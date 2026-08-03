# 📖 VisionReader AI

**Snap a page, see the story unfold.**
VisionReader AI transforms novel text into breathtaking, hyper-accurate cinematic landscapes using pure OCR generative AI.

## 🚀 Live Demo
[Try VisionReader AI Here](https://vision-reader-ai.onrender.com/)

<img width="300" height="560" alt="Demo Preview" src="https://github.com/user-attachments/assets/358cd9bd-036c-4c05-a8e8-830dbbbcf2d3" />

## ⚙️ Features
* **Bilingual OCR:** Extracts exact text from physical book pages (English & Chinese) using Google Gemini 2.5 Flash.
* **Landscape-First Render Logic:** Utilizes a custom V8.5 Elite Composition Guard via Pollinations AI.
* **Dynamic UI:** A heavily customized, cyberpunk-themed Streamlit interface.

## 🛠️ Tech Stack
* **Frontend:** Python, Streamlit, Custom CSS/HTML
* **AI & OCR:** Google GenAI SDK (Gemini 2.5 Flash)
* **Generative Art:** Pollinations AI

## 💻 Local Installation
```bash
git clone [https://github.com/Weililuo/VisionReader-AI.git](https://github.com/Weililuo/VisionReader-AI.git)
cd VisionReader-AI
pip install -r requirements.txt
# Add your GEMINI_API_KEY to .streamlit/secrets.toml
streamlit run app.py
