# Multi-Agent Stock Advisor using AutoGen and GPT-4o-mini

This project showcases a **Multi-Agent System** built with [Microsoft AutoGen](https://github.com/microsoft/autogen), where two agents — a **User Proxy Agent** and an **Assistant Agent** — collaborate to answer financial questions. The LLM backend is powered by **GPT-4o-mini**.

The example scenario predicts **NVIDIA stock trends** and provides suggestions for **buying/selling** decisions.

---

## How It Works

- **User Proxy Agent**: Takes the user's query and initiates communication.
- **Assistant Agent**: Processes the query using `gpt-4o-mini` and performs reasoning or data-based analysis.
- **Agent Dialogue**: Agents interact in a loop until the objective is complete (e.g., "Should I buy NVDA stock?").



