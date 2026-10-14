# agentic_agno
# 🎥 AI YouTube Video Analyzer

An AI-powered web application built with Streamlit that analyzes YouTube videos and generates structured analysis reports from user-provided video links.

## 🚀 Features

- Accepts YouTube video URLs as input.
- Uses an AI agent to analyze video content.
- Generates an analysis report through a simple web interface.
- Provides a loading indicator while processing the video.

## 🛠️ Tech Stack

- Python
- Streamlit
- AI Agents
- YouTube Analysis Tools

## 📁 Project Structure

```text
Youtube-Analyzer/
├── ui.py
├── youtube_analyzer.py
└── README.md
```

## ⚙️ Installation and Setup

**1. Clone the repository or download the project files.**

**2. Navigate to the project directory.**

```bash
cd Youtube-Analyzer
```

**3. Create a virtual environment.**

```bash
python -m venv venv
```

**4. Activate the virtual environment.**

Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

**5. Install the required dependencies.**

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available, install Streamlit and the additional packages required by `youtube_analyzer.py`.

```bash
pip install streamlit
```

**6. Run the application.**

```bash
streamlit run app.py
```

The application will open in your browser, usually at `http://localhost:8501`.

## 💻 How to Use

1. Launch the application.
2. Enter a valid YouTube video link.
3. Click **Analyze Video**.
4. Wait for the AI agent to process the video.
5. View the generated analysis report.

## 🔄 Workflow

`YouTube URL → User Input → AI Agent → Video Analysis → Analysis Report`

## 📌 Requirements

- Python installed on your system.
- Required AI framework and YouTube analysis dependencies.
- API keys or environment configuration, if required by the selected AI agent.

## 🎯 Objective

To simplify YouTube video analysis using AI agents and provide users with an accessible interface for generating video analysis reports.

## 👨‍💻 Author

Roshan Jain