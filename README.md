# 🗣️ Mini Kinyarwanda Voice Assistant

A simple voice assistant that listens to Kinyarwanda audio, transcribes it, matches it with a known question, and responds using speech.

---

## 🚀 What It Does

- Transcribes `.wav` audio using [Whisper-Small-Kinyarwanda](https://huggingface.co/mbazaNLP/Whisper-Small-Kinyarwanda)
- Matches the text to answers using a Python dictionary
- Speaks the answer using [facebook/mms-tts-kin](https://huggingface.co/facebook/mms-tts-kin)
- Saves the output in `outputs/` and plays it automatically (Windows)

---



---

## ✅ How to Run

1. Install packages:

```bash
pip install torch torchaudio soundfile transformers huggingface_hub python-dotenv
```


2. Create a .env file

```bash
HUG_TOKEN=your_huggingface_token_here
```


3. Add .wav files in audio/ and run:

```bash
python main.py
```

---


 ## 👤 Author
Isimbi Nina Henriette
Intelligent Robotics — Rwanda Coding Academy
Instructor: Gabriel Baziramwabo


---

Let me know if you need a matching `requirements.txt` or help pushing it to GitHub!

