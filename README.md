# 🏥 CareBot AI — Healthcare Assistant for PIMS Hospital

<div align="center">

[![FastAPI](https://img.shields.io/badge/FastAPI-0.104+-009688.svg?style=for-the-badge&logo=fastapi)](https://fastapi.tiangolo.com)
[![Groq Cloud](https://img.shields.io/badge/Groq-LLaMA%203-F55036.svg?style=for-the-badge)](https://groq.com)
[![LangChain](https://img.shields.io/badge/LangChain-Clinical%20Prompts-1C3C3C.svg?style=for-the-badge)](https://langchain.com)
[![Healthcare AI](https://img.shields.io/badge/Healthcare%20AI-PIMS%20Hospital-2196F3.svg?style=for-the-badge)](https://github.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

**An AI-powered clinical assistant grounded in real-world healthcare guidelines from the Pakistan Institute of Medical Sciences (PIMS) for instant patient support.**

</div>

---

## 📌 Overview

**CareBot** provides 24/7 patient guidance by answering queries related to **PIMS Hospital** policies, outpatient department (OPD) clinic hours, specialist doctor schedules, and emergency admission procedures with near-zero latency.

---

## ⚡ Key Features

- **🏥 Domain Grounding**: Strictly grounded in official PIMS hospital operational datasets to minimize hallucination.
- **⚡ Ultra-Fast Groq Inference**: Powered by the Groq LPU engine for instantaneous patient query resolution.
- **💬 Structured Medical Triage**: Clear instructions on appointment scheduling, fee policies, and pharmacy locations.
- **💻 Responsive Web UI**: Clean interface built with modern HTML/CSS/JS that cleanly renders medical Markdown guides.

---

## 🛠️ Installation & Setup

1. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Configure Environment**:
   ```env
   GROQ_API_KEY=your_groq_api_key_here
   ```

3. **Launch Server**:
   ```bash
   uvicorn main:app --reload --port 8000
   ```

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.
