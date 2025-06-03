# 📚 Smart-Note-Summarizer
#🧠 Multilingual Smart Note Summarizer with GPT-3.5

**Live Demo:** [Try it on Hugging Face Spaces](https://huggingface.co/spaces/Talip7/smart_note_summarizer)  
**Author:** [Talip7](https://huggingface.co/Talip7)

---

## 🚀 Overview

**Smart Note Summarizer** is an AI-powered app that lets you upload any PDF or paste a text block, select your summary language and style, and get:

- ✂️ A clear, concise **summary**
- 🏷️ An auto-generated **title**
- 🔑 **5 relevant keywords**
- 📘 **Two multiple-choice quiz questions** (optional)
- 🌐 **Automatic translation** if source and summary languages differ

Everything runs on **OpenAI GPT-3.5** in a user-friendly Gradio interface.

---

## 🧰 Features

- **PDF & Text Input:** Supports copy-paste or file upload
- **6 Languages:** English, Turkish, French, German, Spanish, Arabic
- **Summary Styles:** Academic, Child-Friendly, Tweet
- **Custom Summary Length:** Set your preferred character limit
- **Quiz Generation:** Instantly create two MCQ quiz questions from your summary
- **Auto-Translation:** Summarize in any target language, even if source differs
- **Error Handling:** Explains if PDF/text couldn't be read or summarized

---

## 📝 How To Use

1. **Paste text** or **upload a PDF**
2. **Choose summary language & style**
3. **Set character limit**
4. **(Optional) Check 'Generate Quiz Questions'**
5. **Click 'Summarize'** — Get summary, title, keywords & quiz!

---

## ⚙️ Technologies

- [OpenAI GPT-3.5](https://platform.openai.com/)
- [Gradio](https://gradio.app/)
- [pdfplumber](https://github.com/jsvine/pdfplumber)
- [langdetect](https://pypi.org/project/langdetect/)

---

## 🛠️ Installation

```bash
git clone https://github.com/7Talip/smart-note-summarizer.git
cd smart-note-summarizer
pip install -r requirements.txt
