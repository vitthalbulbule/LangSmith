# LangSmith Masterclass — Learning Repository

This repository documents my hands-on learning journey with **LangSmith**, a platform for tracing, debugging, monitoring, and evaluating applications built with Large Language Models (LLMs).

## 🎯 Learning Objectives

- Understand the purpose and importance of LangSmith.
- Learn to trace and monitor LLM applications.
- Debug LLM calls and identify errors.
- Inspect prompts, model responses, and execution details.
- Understand LLM evaluation and application performance.
- Explore observability in LangChain-based applications.

## 🧠 What Is LangSmith?

LangSmith is a developer platform that helps developers trace, debug, monitor, and evaluate LLM applications. It provides visibility into application execution, including prompts, model outputs, latency, and errors, making it easier to build reliable AI applications.

## 🛠️ Technologies Used

- Python
- LangChain
- LangSmith
- Large Language Models (LLMs)
- Python Virtual Environment
- Environment Variables

## ⚙️ Setup and Configuration

### 1. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment on Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 2. Install Dependencies

```bash
pip install langchain langsmith python-dotenv
```

### 3. Configure Environment Variables

Create a `.env` file in the project root directory:

```env
LANGSMITH_TRACING=true
LANGSMITH_API_KEY=your_langsmith_api_key
LANGSMITH_PROJECT=langsmith-masterclass
```

Replace the placeholder with your LangSmith API key.

**Security:** Never upload your `.env` file or API keys to GitHub. Add `.env` to your `.gitignore` file.

## 🔍 Key Concepts Learned

| Concept | Description |
|---|---|
| Tracing | Records the execution of an LLM application. |
| Observability | Provides visibility into application behavior. |
| Debugging | Helps identify errors in prompts and model calls. |
| Evaluation | Measures the quality of LLM-generated outputs. |
| Monitoring | Helps track application performance and behavior. |
| Projects and Runs | Organize traces and individual execution records. |

## 📚 Learning Progress

This repository contains practical examples and experiments developed while learning LangSmith. The code and documentation will evolve as I explore additional concepts.

## 🚀 Future Learning Goals

- Implement tracing in LangChain applications.
- Inspect and debug LLM execution traces.
- Explore datasets and evaluation workflows.
- Compare the performance of different LLM applications.
- Integrate LangSmith with RAG and Agentic AI projects.

## 👨‍💻 About Me

I am a Computer Engineering student interested in Artificial Intelligence, Machine Learning, Generative AI, and Agentic AI. This repository is part of my continuous learning journey toward building practical and reliable LLM applications.

---

*Learning, experimenting, and building with Generative AI.*
