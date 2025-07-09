# ReelForgeAI
AI-powered tool to convert text &amp; images into short video reels

> Turn your text, voice, and images into social media-ready video reels — powered by Python, Flask, AI Voice, and FFmpeg.

![ReelForgeAI Banner](https://github.com/vishvas2001/ReelForgeAI/assets/banner-placeholder.png)

---

## 🚀 Features

- 🧠 **AI Text-to-Speech** using ElevenLabs API
- 📸 **Image Sequencing** into 9:16 videos using FFmpeg
- 🔊 Auto-generates **voiceover** from user description
- 🎬 Full **reel generation** pipeline: images + audio → MP4
- 💾 Automatic input & output folder handling
- 🧪 Background script runs in real time to detect new uploads

---

## 📸 Demo Preview

> 🧪 (You can upload a demo reel later or replace this with a GIF)

![Demo](https://github.com/vishvas2001/ReelForgeAI/assets/demo-placeholder.gif)

---

## 🛠️ Tech Stack

- Python 3
- Flask
- FFmpeg
- ElevenLabs TTS API
- HTML/CSS (Jinja2 Templates)
- Git & VS Code

---

## 📁 Project Structure
ReelForgeAI/
├── static/reels/ # Final output videos
├── templates/create.html # Upload form UI
├── user_upload/ # Incoming image + text folders
├── main.py # Flask server
├── generate_process.py # Background reel generator
├── text_to_audio.py # ElevenLabs TTS
├── config.py # API Key (ignored in .gitignore)
├── requirements.txt
└── README.md
