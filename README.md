# 📖 VisionReader AI

**Snap a page, see the story unfold.**
VisionReader AI transforms bilingual novel text into breathtaking, hyper-accurate cinematic landscapes using pure OCR and landscape-first generative AI.

## 🚀 Live Demo
[Try VisionReader AI Here](https://visionreaderai.streamlit.app/)

## ⚙️ Features
* **Bilingual Pure OCR:** Extracts exact text from physical book pages (English & Chinese) using Google Gemini 2.5 Flash, strictly forbidding AI commentary.
* **Landscape-First Render Logic:** Utilizes a custom V8.5 Elite Composition Guard via Pollinations AI. It forces the visual engine to dedicate >70% of the canvas to epic geological landscapes, crushing AI hallucinations and keeping characters as tiny, scale-establishing accents.
* **Dynamic UI:** A heavily customized, cyberpunk-themed Streamlit interface featuring in-situ component morphing and 3D tactile pixel buttons.

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
