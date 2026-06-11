# Agentic-Research-Assistant
readme_content = """# Agentic-Research-Assistant

An intelligent, agentic research assistant built with **LangChain 0.3+**, designed to perform complex reasoning, real-time web information retrieval, and persistent data management. This project demonstrates an advanced transition from simple conversational chains to **ReAct agents** capable of using external tools to solve multi-step problems.

---

## 🚀 Key Architectural Highlights
* **Agentic Reasoning**: Implements the **ReAct (Reasoning + Acting)** framework, allowing the agent to "think" before taking actions and self-correct based on real-time observations.
* **Intelligent Tooling**: Integrated **Google Search (SerpAPI)**, **Wikipedia**, and **Python REPL** for real-time information gathering and autonomous code execution.
* **Multi-Layered Memory**:
    * **Buffer Memory**: Efficiently manages short-term conversational context.
    * **Vector Memory (ChromaDB)**: Provides semantic search capabilities across previous research sessions.
* **Persistence**: Uses **SQLite** for robust, long-term conversation logging and topic storage.

---

##  System Performance & Results

![Multi-Step Agent Reasoning](Multi_Step_Anonymous_Agent.jpg)
*The agent demonstrates multi-step reasoning by decomposing complex queries into logical tool-use actions, following the "Thought-Action-Observation" loop.*

![Memory Efficiency](Conversation_Message_Length.png)
*Monitoring memory efficiency through conversation message length analysis ensures the system maintains optimal context without exceeding token limits.*

![Database Integration](DB_Tool_Test_Results.png)
*Validation of the SQLite integration, confirming that research findings and user interactions are successfully logged for persistent retrieval.*

---

##  Tech Stack
| Component | Technology |
|-----------|------------|
| **LLM** | Google Gemini 1.5 Pro |
| **Agent Logic** | LangChain ReAct / Zero-shot |
| **Memory** | ChromaDB (Vector) + SQLite (SQL) |
| **Search** | SerpAPI & Wikipedia |
| **Code Execution** | Python REPL |

---

##  Setup & Reproduction
1. **Clone the repository**: `git clone <your-repo-url>`
2. **Install requirements**: 
   ```bash
   pip install -r requirements.txt
