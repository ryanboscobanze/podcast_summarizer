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




