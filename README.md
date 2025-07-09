# 🎬 ReelForgeAI

> Turn your text, voice, and images into social media-ready video reels — powered by Python, Flask, AI Voice, and FFmpeg.

---

## 🚀 Features

- 🧠 AI Text-to-Speech using ElevenLabs API  
- 📸 Image Sequencing into 9:16 vertical video reels  
- 🔊 Auto-generated voiceover from user description  
- 🎬 Full reel generation pipeline (images + voice → MP4)  
- ⚙️ Real-time folder watching and processing  
- 🌐 Flask web interface to upload & preview reels  

---

## 📸 Demo Preview

> _(Coming soon — you can upload a demo video GIF later)_

---

## 🛠️ Tech Stack

- Python 3.10+
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

yaml
Copy
Edit

---

## ⚙️ How to Run Locally

```bash
git clone https://github.com/vishvas2001/ReelForgeAI.git
cd ReelForgeAI
pip install -r requirements.txt
python main.py
⚠️ Requires FFmpeg installed and added to system PATH

🔐 ElevenLabs API Setup
Get your API key from: https://www.elevenlabs.io/

Create a file named config.py and add:

python
Copy
Edit
ELEVENLABS_API_KEY = "your_api_key_here"
📦 Requirements
Python 3.10+

FFmpeg

Flask

elevenlabs (Python SDK)

💡 Upcoming Features
🎙️ Voice style selection (male, female, robotic, etc.)

👤 User login & profile-based video storage

☁️ Firebase or AWS integration for cloud media storage

📝 Auto-subtitles generation from voice

🎵 Background music and video themes

📊 Reel generation statistics dashboard

🙋‍♂️ Author
Vishwas Parmar
📧 Contact
🔗 LinkedIn ← (Add your real profile link)

⭐ Show Your Support
If you liked this project, drop a ⭐ on the repo — it really helps!

yaml
Copy
Edit

---

## ✅ What You Should Do Now:

1. Create or open your `README.md` in VS Code.
2. Paste the above clean content.
3. Save it.
4. Then run:

```bash
git add README.md
git commit -m "Add clean and structured README"
git push
