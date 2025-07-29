# 🧠 Prompt Engineering Playground

👉 Based on the course [ChatGPT Prompt Engineering for Developers](https://learn.deeplearning.ai/courses/chatgpt-prompt-eng)

---

## 📘 Overview

An interactive Jupyter Notebook for experimenting with prompt engineering using OpenAI's GPT-3.5/4.

### ✅ What’s inside?

- `prompt_playground.ipynb` – A well-structured interactive notebook
- `.env` support – API key management via environment variables
- Prompt examples:
  - Sentiment and emotion detection  
  - JSON data extraction  
  - Entity recognition  
  - Inference and classification
- `requirements.txt` file for quick setup

---

## 🚀 Quick Start

1. **Clone the repo**
```bash
git clone https://github.com/your-username/prompt-playground.git
cd prompt-playground
```

2. **Create `.env` file**
```ini
OPENAI_API_KEY=sk-...
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Launch Jupyter Lab**
```bash
jupyter lab
```

---

## 📦 Requirements

```
openai>=1.0.0
python-dotenv
```

---

## 🔐 Security

The `.env` file is excluded via `.gitignore` to keep your API key safe.

---

## 📄 License

MIT License
