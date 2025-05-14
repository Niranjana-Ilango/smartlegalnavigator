# smartlegalnavigator
An AI-driven legal assistant built to guide Indian citizens—both educated and uneducated—through legal procedures in a simple, accessible, and multilingual manner. Whether you're involved in an accident, seeking legal advice, or need to understand IPC, CrPC, or the Indian Constitution, this system provides instant guidance via text and voice support.

## 🚀 Project Overview

Smart Legal Navigator is a multilingual, voice-enabled AI chatbot that:
- Answers legal queries related to **IPC, CrPC, and the Constitution of India**
- Supports **text and voice input/output**
- Translates responses into **multiple Indian languages**
- Aims to assist users in understanding **basic legal rights and procedures**

## 🧰 Features

- ✅ Legal Q&A from structured datasets
- 🗣 Voice Input using **Wav2Vec2**
- 🗨 Audio Output using **Text-to-Speech**
- 🌐 Multilingual translation with **IndicTrans** and other tools
- 💬 Gradio-based user-friendly interface (GUI)
- 🧠 Trained on fine-tuned models (BERT, RoBERTa, etc.)
- 📁 Dataset support: `reduced_combined_qa.json`, `constitution_qa.json`, `ipc_qa.json`, `crpc_qa.json`

---

## 🛠️ Tech Stack

| Component         | Technology Used         |
|------------------|-------------------------|
| Backend / NLP     | Python, Hugging Face Transformers |
| Datasets          | Custom JSON-based legal QA sets  |
| Translation       | IndicTrans, Google Translate API |
| Voice Recognition | Wav2Vec2                |
| Voice Output      | gTTS / pyttsx3          |
| Interface         | Gradio / Tkinter        |
| Platform          | Google Colab, VS Code   |





