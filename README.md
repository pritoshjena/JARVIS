# 🧠 Jarvis Voice Assistant (Python)

A Python-based voice assistant that responds to the wake word "Jarvis", plays music, fetches news, opens websites, and answers questions using OpenAI.

## 🎯 Features

- Wake word: "Jarvis"
- Voice recognition (using SpeechRecognition & Google API)
- Text-to-speech via gTTS & pyttsx3
- Answers questions using OpenAI GPT-3.5
- Plays YouTube music from a custom library
- Opens common websites (Google, YouTube, Facebook, LinkedIn)
- Reads news headlines using NewsAPI

## 🛠 Requirements

Install with:

```bash
pip install speechrecognition gtts pyttsx3 pygame openai requests

Also install:

pocketsphinx (for offline recognition — optional)

a working microphone
