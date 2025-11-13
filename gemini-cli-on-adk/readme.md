# 🚀 Gemini CLI Integration

This project demonstrates how **Gemini CLI’s non-interactive mode** can significantly enhance ADK development workflows.  
The integration in `app/agent.py` introduces a powerful `gemini_cli` tool that enables **automated and intelligent development tasks**.

---

## 🌟 Key Benefits

- **Automated Code Analysis:**  
  Analyze entire codebases without manual file selection using Gemini CLI’s intelligent file discovery.

- **Streamlined Development:**  
  Removes the need to manually specify which files to send for analysis.

- **Command Execution:**  
  Automatically runs relevant development commands based on code insights.

- **Intelligent File Editing:**  
  Modifies files contextually based on recommendations from code analysis.

- **Robust Error Handling:**  
  Built-in timeouts and exception management ensure reliable and stable execution.

---

## ⚡ Development Efficiency Gains

Gemini CLI’s non-interactive mode delivers substantial productivity improvements by providing:

- **Smart File Selection:** Automatically identifies relevant files for each development task.  
- **Automated Code Generation:** Generates boilerplate code, test cases, and documentation.  
- **Command Automation:** Executes development and build commands automatically.  
- **Contextual Analysis:** Delivers deep project-level insights with complete context awareness.

---

## 💡 Usage Examples

The integrated `gemini_cli` function supports tasks such as:

- “Explain this codebase”  
- “Generate a test plan”  
- “Create unit tests for the agent module”  
- “Analyze code quality and suggest improvements”

This integration showcases how Gemini CLI can act as a **development accelerator** within ADK agents.

---

## 🧱 Project Structure

gemini-cli-on-adk/
├── app/ # Core application code
│ ├── agent.py # Main agent logic
│ ├── server.py # FastAPI backend server
│ └── utils/ # Utility functions and helpers
├── deployment/ # Infrastructure and deployment scripts
├── notebooks/ # Jupyter notebooks for prototyping and evaluation
├── tests/ # Unit, integration, and load tests
├── Makefile # Common build and development commands
├── GEMINI.md # AI-assisted development guide
└── pyproject.toml # Dependencies and configuration


---

## ☁️ Deployment

The ADK agent is designed to run on **Google Cloud Run**, with a preconfigured `Dockerfile` and `cloudbuild.yaml` for seamless deployment via **Google Cloud Build**.

### 🔧 Prerequisites

- Vertex AI API must be **enabled** in your Google Cloud project.  
- Cloud Run service account must have **Vertex AI service access**.

---

## 🚀 Cloud Run Deployment

Build the container image using Cloud Build:

```bash
gcloud builds submit --config cloudbuild.yaml

