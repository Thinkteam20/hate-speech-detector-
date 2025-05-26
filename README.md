hate-speech-detector/
├── main.py             # Main script with Gradio UI
├── README.md
└── requirements.txt    # Python dependencies

# 🛡️ Korean Hate Speech Detection with Gradio

A simple web-based hate speech classifier for the Korean language, built using Hugging Face Transformers and Gradio.

<p align="center">
  <img src="https://img.shields.io/badge/Model-smilegate--ai/kor_unsmile-blue" alt="model">
  <img src="https://img.shields.io/badge/Framework-PyTorch-orange">
  <img src="https://img.shields.io/badge/UI-Gradio-green">
</p>

---

## 📌 Overview

This project uses the pre-trained [`smilegate-ai/kor_unsmile`](https://huggingface.co/smilegate-ai/kor_unsmile) model to detect various types of hate speech in Korean text, including but not limited to:

- Gender-based (Women, Men, LGBTQ+)
- Age discrimination
- Racism/Nationality bias
- Religion-based hate
- Abusive language
- Clean content

A user-friendly Gradio interface allows anyone to test the model in real-time.

---

## 💻 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/korean-hate-speech-detector.git
cd korean-hate-speech-detector
