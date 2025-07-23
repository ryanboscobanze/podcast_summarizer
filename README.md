# 🎧 Podcast Summarizer – Whisper + GPT + Diffusers

Automatically transcribe, summarize, and visualize podcast/audio content using OpenAI Whisper, GPT-based models, and image generation. This notebook provides an end-to-end pipeline to turn long podcast episodes into digestible summaries and visuals — perfect for content creators, researchers, and productivity hackers.

---

## 🚀 Features

- 🧠 **Transcription**: High-quality speech-to-text using Whisper
- ✍️ **Summarization**: Bullet points, TL;DR, and action items via Facebook’s BART model for text summarization and refined with mistral7b via openrouter/ free llm/ limited rates/ finalized narration with gemini flash 
- 🎥 **YouTube/Podcast Support**: Download audio using `yt-dlp`
- 🖼️ **Visual Generation**: Generate images using `diffusers`
- 🔈 **Text-to-Speech**: Optional voice-based outputs
- 💾 **Save Outputs**: Transcripts and summaries saved as `.txt`

---

---
```
podcast_summarizer/
├── podcast_summarizer.ipynb # Main Colab notebook
├── sample_audio/ # Short example clips
│ └── clip.mp3
├── outputs/ # Sample summaries & transcripts
│ └── summary_clip.txt
├── requirements.txt # Python dependencies
└── README.md # This file
```
---

### 🔄 Run in Google Colab (Recommended)

---

#### 🧠 final_podcast_summarizer_1.ipynb : Whisper Transcription + Facebook Bart Summarization segments + YouTube Downloader  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18eZ3_AztekDrk_M8yov2JFZtQjHPul2J)

---

#### 🎬 final_podcast_summarizer_2.ipynb : Mistral Summary + Gemini Flash Narration + Diffusion Video Generator  + Moviepy
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Cz8mclf5B1ZcfXkkSQAgAyBKp3M0hb0k)

---

📝 **Sample Output Transcript:**  
“Today on the All-In podcast, we discuss the future of AI regulation…”

**Summary:**
- 🔹 OpenAI plans new safety board  
- 🔹 Government pressure on foundation models  
- 🔹 Investors bullish on real-time inference

Visual:
Generated image reflecting the theme of the episode (optional)
---
📜 License
MIT License – see LICENSE
---
🤝 Contributions
Pull requests, feature ideas, and issues are welcome. Let’s make this even better together.

