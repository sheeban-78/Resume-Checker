# 🚀 Resume Analyzer Based on Job Description (JD)

This project is a **Resume Analyzer Tool** built using **Python**, **Gradio**, and various NLP/vision libraries. It helps candidates evaluate how well their resumes match a given job description (JD) by computing an **ATS (Applicant Tracking System) score**, extracting relevant skills, and suggesting the most suitable roles.

## 🔍 Features

- 📄 Upload a resume in PDF format  
- 📝 Paste any job description  
- 🧠 Extracts skills using NLP techniques and OCR  
- 📊 Calculates an ATS match score based on found skills  
- 🎯 Suggests the best-fit job role from predefined categories  
- 📈 Visual representation of resume match score via pie chart  
- 🌐 Web-based interface powered by Gradio  

## 📦 Tech Stack

- Python  
- Gradio (for UI)  
- PyMuPDF (for PDF parsing)  
- Tesseract OCR (via `pytesseract`)  
- NLTK (for keyword extraction)  
- Matplotlib (for visualizing ATS score)  
- PDF2Image and PIL (for resume image conversion)  

## 🔧 Installation

```bash
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
sudo apt-get install -y poppler-utils
