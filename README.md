# AI Code Generation & Execution Agents

A modular set of Jupyter notebooks demonstrating two LangChain‑powered AI agents that generate and run code on demand:

1. **CodeGen Agent (LangGraph)**  
   - Stateful, intent‑based code generator using LangGraph  
   - Integrates memory to build upon previous code  
   - Executes via Judge0 and streams results back to user  

2. **Zero‑Shot REACT Agent**  
   - Classic LangChain zero‑shot REACT agent  
   - Two‐tool setup: code generation + Judge0 execution  
   - Demonstrates agent reasoning traces and automated execution

---

## 🚀 Features

- **Multi‑language support**: Python (default), JavaScript, Java, C++, C  
- **Intent‑based memory**: Build incremental code via previous context  
- **Seamless execution**: Judge0 integration for compile/run  
- **Interactive chat loops**: Converse with your AI agent in notebook  
- **Clear separation**: Generator vs. executor tools for reuse  

---

## 📋 Table of Contents

- [Prerequisites](#-prerequisites)  
- [Installation](#-installation)  
- [Configuration](#-configuration)  
- [Usage](#-usage)  
  - [CodeGen Agent (LangGraph)](#codegen-agent-langgraph)  
  - [Zero‑Shot REACT Agent](#zero-shot-react-agent)  
- [Project Structure](#-project-structure)  
- [Extending & Contributing](#-extending--contributing)  
- [License](#-license)  

---

## ✅ Prerequisites

- Python 3.9+  
- Jupyter Notebook / Google Colab  
- OpenAI API key (for GPT‑4o‑mini access)  
- RapidAPI key for Judge0 (code execution)  

---

## 🛠️ Installation

1. **Clone this repository**  
   ```bash
   git clone https://github.com/your‑org/AI-CodeGen-Agents.git
   cd AI-CodeGen-Agents
