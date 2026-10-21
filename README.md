
# 🦥 SlothTask AI

### Slow down. Let AI organize your to-do list.

SlothTask AI turns messy notes, tasks, and reminders into a clear, prioritized action plan using an open-weight AI model.

## ✨ Features

- Organizes unstructured notes into a task plan
- Prioritizes tasks by urgency and importance
- Suggests time estimates
- Identifies information that needs clarification
- Provides a downloadable task plan
- Validates input and handles API errors

## 🛠️ Tech Stack

- Python
- Streamlit
- Groq API
- Open-weight model: `openai/gpt-oss-20b`
- python-dotenv

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/SlothTask-AI.git
cd SlothTask-AI
```

### 2. Create a virtual environment

Windows:

```powershell
python -m venv .venv
.\.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure your API key

Create a `.env` file in the project root:

```dotenv
GROQ_API_KEY=your_groq_api_key_here
```

Get your API key from:
https://console.groq.com/keys

Never commit your `.env` file or share your API key.

### 5. Run the app

```bash
streamlit run app.py
```

Open the local URL shown in your terminal.

## 🔐 Privacy

Notes submitted through the app are sent to the Groq API for processing. An internet connection and a valid API key are required. Do not submit passwords, financial secrets, or sensitive personal information.

This application uses hosted inference; it does not run the AI model locally.

## 🌱 Why Open-Weight AI?

SlothTask AI demonstrates how developers can build practical applications using an openly available model rather than relying exclusively on closed-model ecosystems. Open-weight models give developers more flexibility to experiment, evaluate, and adapt AI-powered tools.

Open weights do not automatically mean unrestricted use or fully open-source training data. Review the model's license and provider terms before redistributing or deploying it.

## ⚠️ Disclaimer

AI-generated priorities and time estimates may be inaccurate. Review the suggested plan before relying on it.

## 📄 License

MIT
