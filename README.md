# 🎤 Voice-to-Text Conversion & Speech Analysis  

## 📌 Overview  
The **Voice-to-Text Conversion & Speech Analysis System** is a Python-based web application that converts speech to text and performs detailed text analysis. It allows users to record live audio or upload audio files in various formats, transcribes the speech into text, and provides comprehensive insights including sentiment analysis, keyword extraction, and text summarization. Users can also export a professional PDF report of the analysis.  

This project combines **speech recognition**, **NLP**, and **data visualization** to create a powerful tool for analyzing spoken content.  

---

## ⚙️ Features  
- Real-time audio recording via microphone.  
- Upload audio files in formats like WAV, MP3, MP4, M4A, FLAC.  
- Automatic transcription of speech to text using Google Speech Recognition API.  
- Editable text area for correcting or modifying transcribed text.  
- Comprehensive text analysis:  
  - Word, character, and sentence counts  
  - Sentiment analysis (Polarity & Subjectivity)  
  - Top keywords extraction  
  - Summary generation  
- Visualizations:  
  - Sentiment bar chart  
  - Word cloud for keywords  
- Export analysis results to a downloadable PDF report.  
- Interactive and user-friendly interface built with Streamlit.  

---

## 📊 Tech Stack  
- **Programming Language:** Python 🐍  
- **Web Framework:** Streamlit  
- **Libraries & Tools:**  
  - `speech_recognition` → Speech-to-text conversion  
  - `TextBlob` → Sentiment analysis and NLP  
  - `nltk` → Natural language processing utilities  
  - `wordcloud`, `matplotlib` → Visualization of keywords and sentiment  
  - `pandas` → Data handling  
  - `FPDF` → PDF report generation  
  - `st_audiorec` → Streamlit audio recording  


