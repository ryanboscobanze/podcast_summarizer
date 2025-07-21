# 🎧 Podcast Summarizer – Whisper + GPT + Diffusers

Automatically transcribe, summarize, and visualize podcast/audio content using OpenAI Whisper, GPT-based models, and image generation. This notebook provides an end-to-end pipeline to turn long podcast episodes into digestible summaries and visuals — perfect for content creators, researchers, and productivity hackers.

---

## 🚀 Features

- 🧠 **Transcription**: High-quality speech-to-text using Whisper
- ✍️ **Summarization**: Bullet points, TL;DR, and action items via GPT
- 🎥 **YouTube/Podcast Support**: Download audio using `yt-dlp`
- 🖼️ **Visual Generation**: Generate images using `diffusers`
- 🔈 **Text-to-Speech**: Optional voice-based outputs
- 💾 **Save Outputs**: Transcripts and summaries saved as `.txt`

---

## 📂 Folder Structure

podcast_summarizer/
├── podcast_summarizer.ipynb # 💻 Main Colab notebook
├── sample_audio/ # 🎧 Short example clips
│ └── clip.mp3
├── outputs/ # 📝 Sample summaries & transcripts
│ └── summary_clip.txt
├── requirements.txt # 📦 Python dependencies
└── README.md # 📘 This file
---

## 🛠️ Installation

### 🔄 Run in Google Colab (**recommended**)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/podcast-summarizer/blob/main/podcast_summarizer.ipynb)

Once the notebook opens, run the **first cell** to install all required libraries.

Colab will also install:
```bash
apt-get update && apt-get install -y ffmpeg espeak
```
You’ll be prompted to enter your OpenAI API key securely at runtime.

🖥️ Run Locally
```bash
git clone https://github.com/YOUR_USERNAME/podcast_summarizer.git
cd podcast_summarizer
pip install -r requirements.txt
```

System-level packages also need to be installed locally:
```bash
sudo apt install ffmpeg espeak
```

🔐 API Key Management
```bash
import os
from getpass import getpass
os.environ["OPENAI_API_KEY"] = getpass("🔑 Enter your OpenAI API key:")
```
📊 Sample Output
Transcript:
“Today on the All-In podcast, we discuss the future of AI regulation…”

Summary:
🔹 OpenAI plans new safety board
🔹 Government pressure on foundation models
🔹 Investors bullish on real-time inference

Visual:
Generated image reflecting the theme of the episode (optional)

📜 License
MIT License – see LICENSE

🤝 Contributions
Pull requests, feature ideas, and issues are welcome. Let’s make this even better together.

