# 🎤 AI Interview Coach

An AI-powered mock interview assistant that conducts personalized interview sessions using resume analysis, job description understanding, speech recognition, and AI-generated feedback.

This project was developed and tested in the IBM Skills Network Lab environment as part of an academic / internship project.

---

# 📌 Project Overview

The AI Interview Coach helps users prepare for interviews by:

- Uploading a resume (PDF)
- Providing a job description
- Generating personalized interview questions
- Conducting voice-based mock interviews
- Evaluating interview performance using AI

The project demonstrates the practical implementation of AI, speech processing, resume analysis, and cloud-based APIs in career preparation applications.

---

# 🚀 Features

- 📄 Upload Resume PDF
- 🧠 AI-powered interview question generation
- 🎤 Voice-based interview interaction
- 🔊 Text-to-Speech interviewer responses
- 🗣️ Speech-to-Text answer transcription
- 📊 AI-generated interview evaluation
- 🌐 Interactive web interface using Gradio
- ☁️ Cloud-based AI via IBM watsonx.ai

---

# 🛠️ Tech Stack

### Programming Language
- Python 3.11

### Framework
- Gradio

### AI Platform
- IBM watsonx.ai

### Libraries
- ibm-watsonx-ai
- faster-whisper
- gTTS
- PyPDF2

### Frontend
- Gradio UI

### Version Control
- Git & GitHub

### Execution Environment
- IBM Skills Network Lab

---

# 📂 Project Structure

```bash
interview-coach-ai/
│
├── myapp.py                # Main application
├── README.md               # Project documentation
├── requirements.txt        # Dependencies
├── .gitignore              # Ignored files
└── temp_voice.mp3          # Generated audio output# AI Interview Coach

An AI-powered mock interview application built using Python, Gradio, IBM Watsonx AI, Whisper, and gTTS.

## Features

- Upload Resume PDF
- Paste Job Description
- AI-generated interview questions
- Voice-based interview interaction
- Speech-to-text using Faster Whisper
- Text-to-speech using gTTS
- AI performance evaluation
- Personalized interview flow

## Technologies Used

- Python
- Gradio
- IBM Watsonx AI
- Faster Whisper
- gTTS
- PyPDF2

## Installation

### Clone Repository

```bash
git clone https://github.com/Md-Soheb-Khan/interview-coach-ai.git
cd interview-coach-ai
