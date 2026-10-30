# 🏭 Agent Factory: The Master Orchestrator

Welcome to the **Agent Factory**, a specialized Gem (Meta-Orchestrator) designed to dynamically generate teams of ultra-specialized AI agents.

Instead of entrusting entire complex projects to a single language model — risking hallucinations and Context Window saturation — this tool acts as a **System Architect and HR Department**. It transforms your project idea into the exact *System Prompts* needed to instantiate a perfectly balanced IT team.

## 🧠 Architecture and Logic (Prompt Engineering)
This Gem was built by rigorously applying academic and operational principles of advanced Prompt Engineering:

*   **Meta-Orchestration:** The Orchestrator does not write code or execute operational tasks. Its sole job is domain analysis and creating prompts for sub-agents.
*   **Single Responsibility Principle (SRP):** To avoid overlap and hallucinations, the Orchestrator is constrained to generate a team at a single depth level: one Sub-Orchestrator (Project Manager) and a maximum of 3-4 Specialists (e.g., Frontend, Database, QA).
*   **Chain of Thought (CoT):** Before outputting the prompts, the Gem is instructed to show its logical process, analyzing the required technologies and justifying the selection of specialists.
*   **Role & Contextual Prompting:** Every System Prompt generated for the child agents contains clear roles, contexts limited to their domain, and structured positive instructions.

## 🚀 How to use the Gem
1.  **Launch the Orchestrator:** Provide the Gem with the description of your project. (e.g., *"I want to develop a Python app for managing encrypted databases"*).
2.  **Wait for the Analysis:** The Gem will evaluate the domain and deduce which professional figures (agents) are strictly necessary.
3.  **Get the System Prompts:** You will receive a complete configuration card for each agent on the team.
4.  **Instantiate your Team:** Copy and paste the received System Prompts to create your new Gems (or to populate your agents in Python frameworks like CrewAI or LangChain), setting the suggested Temperature to maximize the effectiveness of each role.

## ⚙️ Output Template
For each specialist, the Orchestrator will automatically provide you with:
*   Agent Name
*   Task Objective
*   Suggested Temperature (from 0.0 for logic/security to 0.4 for design)
*   The complete and formatted System Prompt

---
*Project developed optimizing Prompt Engineering best practices for hallucination mitigation in LLM models.*
