# 🚀 All-in-One AI Utility App

An AI-powered productivity toolkit that combines 8 essential tools into one seamless interface — built using **HTML, CSS, JavaScript**, and a **pure Python backend (no frameworks)**.

---

## 🧩 Features

### 1. 📄 PDF Summarizer
- Upload PDF → Get:
  - TL;DR summary
  - Key bullet points
  - 3 Q&A pairs
  - (Optional) Audio summary

### 2. 🔗 PDF Merger
- Upload multiple PDFs → Merge → Download single file

### 3. ✂️ PDF Splitter
- Upload PDF + Select page range → Extract and download new PDF

### 4. 📝 Text Extractor (PDF/Image)
- Upload PDF/Image → OCR → Extracted clean text output

### 5. 🎧 Text-to-Speech
- Enter or paste text → Listen to audio → Download MP3

### 6. 🧠 Notes to Flashcards
- Paste notes or upload → Convert to Q/A format → Export CSV

### 7. 🗣 Voice to Text
- Upload voice note/audio → Transcribe + optional summary

### 8. 🌐 Language Translator + Simplifier
- Paste paragraph → Translate to chosen language (e.g., Hindi, Marathi) + simplify to 9th-grade level

---

## 🛠️ Tech Stack

### Frontend:
- HTML, CSS, JavaScript (Vanilla)
- Fetch API for backend communication
- Responsive UI with clean utility-based styling

### Backend:
- Python (No frameworks like Flask/Django)
- Libraries used:
  - `PyPDF2`, `pdfminer.six` – PDF handling
  - `pytesseract`, `Pillow` – OCR
  - `pyttsx3` or API (e.g., Google TTS) – Text-to-speech
  - `speech_recognition` – Audio transcription
  - `openai`, `googletrans` – AI and translation

---

## 📤 Export Options

Each tool supports:
- ✅ Download as PDF
- ✅ Copy to Clipboard
- ✅ Audio Download (MP3)
- ✅ Share via Email

---
