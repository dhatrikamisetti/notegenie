# 🧠 NoteGenie — AI-Powered Research Assistant

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-3.x-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Gemini AI](https://img.shields.io/badge/Gemini_AI-Flash_2.0-8E75B2?style=for-the-badge&logo=google&logoColor=white)](https://deepmind.google/technologies/gemini/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

**NoteGenie** is a powerful, AI-driven research platform inspired by Google's NotebookLM. It allows researchers, students, and professionals to upload complex documents, organize them into projects, and interact with a brilliant AI assistant to extract deep insights, generate summaries, and synthesize knowledge effortlessly.

## ✨ Features

- 📑 **Smart Document Management**: Upload PDFs, Word documents, and text files into organized workspaces.
- 🤖 **Contextual AI Chat**: Chat directly with your documents. The AI (powered by Gemini 2.0 Flash) understands your specific sources and provides cited answers.
- 📝 **AI Summarization**: Instantly generate structured summaries and key findings from long, technical papers.
- 📂 **Project Workspaces**: Keep your research organized with customizable project folders.
- 🎨 **Premium UI/UX**: A state-of-the-art, glassmorphism-inspired interface with Dark Mode support and smooth micro-animations.
- 🔐 **Secure & Personal**: User authentication, private database, and localized storage.

## 🚀 Getting Started

### Prerequisites

- Python 3.9 or higher
- A Google Gemini API Key (Get one for free at [Google AI Studio](https://aistudio.google.com/))

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/dhatrikamisetti/notegenie.git
   cd notegenie
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv .venv
   # On Windows
   .venv\Scripts\activate
   # On macOS/Linux
   source .venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up your environment variables:**
   Create a `.env` file in the root directory and add your Gemini API key:
   ```text
   GEMINI_API_KEY=your_api_key_here
   ```

5. **Run the application:**
   ```bash
   python app.py
   ```

6. **Open your browser:**
   Navigate to `http://127.0.0.1:5000` to start using NoteGenie!

## 🛠️ Tech Stack

- **Backend**: Python (Flask)
- **AI/LLM**: Google Gemini 2.0 Flash API
- **Database**: SQLite with SQLAlchemy ORM
- **Frontend**: HTML5, Vanilla JavaScript, Tailwind CSS
- **Parsing**: PyPDF2 (PDF), python-docx (Word)

## 📸 Screenshots

*(Add your screenshots here to show off the beautiful UI!)*

---

Built with ❤️ by [Dhatri Kamisetti](https://github.com/dhatrikamisetti)
