# Study Assistant — AI-Powered Academic Learning Companion

An AI-powered study assistant designed to make learning easier, smarter, and more engaging. Ask academic questions, explore complex concepts, and get personalized explanations using Generative AI — with the ability to choose between Friendly and Academic teaching styles.

🔗 **Live Demo:** https://studyassistent-1.onrender.com

---

## Overview

Study Assistant is a Generative AI-powered application that helps students understand academic concepts through interactive conversations.

Whether you're learning a new topic, struggling with a complex concept, or looking for a structured academic explanation, Study Assistant adapts its response style to your needs.

Built using Python, Gradio, and Google's Gemini API, the application provides a simple and interactive interface for AI-assisted learning.

---

## Features

- **AI-Powered Answers** — Get responses to academic questions using Google's Gemini AI.
- **Dual AI Personalities** — Switch between Friendly and Academic explanation styles.
- **Beginner-Friendly Learning** — Understand difficult concepts through simple explanations and examples.
- **Academic Explanations** — Get structured and formal explanations for study and exam preparation.
- **Interactive Interface** — Easy-to-use interface built with Gradio.
- **Live Deployment** — Hosted online and accessible through a web browser.
- **Secure API Configuration** — API key managed through environment variables.

---

## AI Personalities

| Personality | Description |
|---|---|
| Friendly | Explains concepts in simple language using analogies, examples, and an encouraging tone. |
| Academic | Provides structured, formal, detailed explanations using academic terminology. |

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Python | Backend logic and application development |
| Gradio | Interactive user interface |
| Google Gemini API | AI-powered response generation |
| Google GenAI SDK | Integration with Gemini models |
| Render | Application hosting and deployment |
| Git & GitHub | Version control and project management |

---

## Architecture

User submits a question and selects a personality → Gradio passes the input to the Python backend → Gemini API generates a response based on the selected system instruction → The answer is displayed in the interface.

---

## Project Structure

```text
StudyAssistant/
│
├── app.py
├── requirements.txt
├── README.md
└── .gitattributes
```

---

## How It Works

1. The user enters an academic question.
2. The user selects a response personality.
3. The application constructs a system instruction based on the selected personality.
4. The question and instructions are sent to the Gemini API.
5. Gemini generates a contextual response.
6. The answer is displayed to the user through the Gradio interface.

---

## Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/gowtham-varikuntla/StudyAssistent
```

### 2. Navigate to the Project Directory

```bash
cd StudyAssistant
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Key

Set your Gemini API key as an environment variable.

**Windows PowerShell:**

```powershell
$env:GEMINI_API_KEY="your_api_key_here"
```

**Linux / macOS:**

```bash
export GEMINI_API_KEY="your_api_key_here"
```

### 5. Run the Application

```bash
python app.py
```

Open the local URL shown in the terminal to start using Study Assistant.

---

## Environment Variables

| Variable | Description |
|---|---|
| `GEMINI_API_KEY` | API key required to access Google's Gemini API |
| `PORT` | Port used by the hosting environment (if configured) |

> Never commit your API key or expose it publicly.

---

## Deployment

Study Assistant is deployed on Render and connected to GitHub for deployment.

🔗 **Try it here:** https://studyassistent-1.onrender.com

## Author

**Gowtham**  
B.Tech — Computer Science & Engineering (AI & ML)

