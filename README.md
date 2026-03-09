🤖 AI Agent Framework (From Scratch)
This project demonstrates how to build an interactive AI agent framework from scratch using Python.
It is designed for beginners who want to understand how agents work internally, without magic libraries.

📌 What This Project Does
Builds an interactive terminal-based agent
Uses a simple framework design
Clearly separates:
Agent logic
Memory
Execution control
Logging
Helps you understand how real AI frameworks are structured
📂 Project Structure
📁 ai_agent/ ← Main project folder (run from here) │ ├── 📄 main.py ← (Optional) Entry file │ ├── 📁 core/ ← Core agent logic │ ├── 📄 init.py │ ├── 📄 state.py ← Agent memory │ ├── 📄 flow.py ← Task execution logic │ └── 📄 orchestrator.py ← Controls execution + state │ ├── 📁 sdk/ ← Agent definition │ ├── 📄 init.py │ └── 📄 agent.py ← Agent class │ ├── 📁 observability/ ← Logging utilities │ ├── 📄 init.py │ └── 📄 logger.py ← log_event() function │ ├── 📁 reference_agents/ ← Example agents │ ├── 📄 init.py │ └── 📄 interactive_agent.py ← Interactive terminal agent

🧠 Folder Explanation
Folder	Purpose
core/	Brain of the agent (memory, flow, execution)
sdk/	Defines what an agent is
observability/	Logging and debugging
reference_agents/	Ready-to-run example agents
▶️ How to Run the Agent
Step 1: Open terminal in the main folder
cd ai_agent
Step 2: Run the interactive agent
python -m reference_agents.interactive_agent

💬 Example Output
🤖 Interactive Agent Started
Type 'exit' to stop

You: hello
[LOG] Running flow with input: hello
Agent: I heard you say: hello

🧠 Key Concepts Learned

What an AI agent is

How agents store memory

How execution flows work

How Python packages & imports work

How real AI frameworks are structured internally

🚀 Future Enhancements

Add real AI (LLM / ChatGPT)

Add multi-agent collaboration

Add file-based logging

Convert to web or GUI app

Deploy as a service

📌 Requirements

Python 3.8+

No external libraries required
