# ⚡ Agentic Vibe Stack

An open-source, multi-agent boilerplate for rapid vibe coding. Turn your prompts into production-ready, full-stack applications in minutes.

## 🚀 Why This Exists
Writing boilerplate code slows down the creative process. This repository provides a pre-configured environment where AI agents handle the heavy lifting of UI creation and backend integration, letting you focus on the core logic and user experience. 

## ✨ Features
* **Multi-Agent Orchestration:** Specialized Python scripts to handle distinct coding tasks.
* **Seamless API Integration:** Native support for Google AI Studio to power the generation engine.
* **Serverless Backend Ready:** Firebase integration built-in for instant database and authentication deployment.
* **Cross-Platform Output:** Structured to output clean, deployable code for mobile and web.

## 🛠️ Tech Stack
* **Orchestration:** Python
* **AI Engine:** Google AI Studio API
* **Backend:** Firebase
* **Frontend Output:** Flutter / Dart 

## 📦 Getting Started

### Prerequisites
* Python 3.10+
* Firebase CLI
* An active Google AI Studio API Key

### Quick Start
1. Clone the repository:
   `git clone https://github.com/yourusername/agentic-vibe-stack.git`
2. Navigate to the directory:
   `cd agentic-vibe-stack`
3. Install dependencies:
   `pip install -r requirements.txt`
4. Set up your environment variables:
   `cp .env.example .env` (Add your API keys here)
5. Run the primary agent:
   `python agents/main_orchestrator.py --prompt "Build a task manager"`

## 🤝 Contributing
Contributions are welcome! Whether it's adding new AI "skills" to the `/skills` folder or optimizing the Firebase deployment scripts, please submit a pull request.
