# 🏭 Agent Factory: The Master Orchestrator

Welcome to the **Agent Factory**, a specialized Gem (Meta-Orchestrator) designed to help generate teams of focused AI agents.

Instead of entrusting an entire complex project to a single language model, this tool helps organize the work into focused roles. It acts as a **System Architect and HR Department**, turning your project idea into draft *System Prompts* for a team tailored to the task. This approach can help manage context and reduce role overlap, but it cannot eliminate hallucinations or guarantee complete or suitable prompts.

## 🧠 Architecture and Logic (Prompt Engineering)
The design uses commonly applied prompt-engineering concepts:

*   **Meta-Orchestration:** The Orchestrator does not write code or execute operational tasks. Its sole job is domain analysis and creating prompts for sub-agents.
*   **Single Responsibility Principle (SRP):** To reduce role overlap and help manage hallucination risk, the Orchestrator generates one Sub-Orchestrator (Project Manager) and only the specialists needed, up to a maximum of four. Clear scopes can help coordination, but do not ensure error-free results.
*   **Team rationale:** The Orchestrator provides a concise explanation of role selection and relevant assumptions, without requiring disclosure of private internal reasoning.
*   **Role & Contextual Prompting:** Generated System Prompts define each agent's role, relevant context, responsibilities, boundaries, and expected outputs.

## 🚀 How to use the Gem
1.  **Launch the Orchestrator:** Provide the Gem with the description of your project. (e.g., *"I want to develop a Python app for managing encrypted databases"*).
2.  **Wait for the Analysis:** The Gem will evaluate the domain and deduce which professional figures (agents) are strictly necessary.
3.  **Get the System Prompts:** You will receive a complete configuration card for each agent on the team.
4.  **Instantiate your Team:** Copy and paste the received System Prompts to create your new Gems (or to populate your agents in Python frameworks like CrewAI or LangChain). Apply an optional temperature suggestion only if your platform supports it; it does not guarantee better results.

## ⚙️ Output Template
For the team, the Orchestrator provides:
*   Agent Name
*   Objective and responsibilities
*   Optional suggested temperature, if supported by the target platform (not a measure of accuracy or safety)
*   A complete, formatted System Prompt for each agent

See the [example generated team](./examples/test-output.md) for a sample project and copy-ready prompts.

## ⚠️ Disclaimer
This project and its AI-generated prompts are provided "as is," without warranties of any kind. AI-generated content may be inaccurate, incomplete, or unsuitable for your needs. Review and validate all prompts and outputs before relying on them, especially for security-sensitive, legal, medical, or business-critical decisions. This project does not provide professional advice, and its authors accept no liability for actions taken based on its outputs to the extent permitted by applicable law.

## 📄 License
This project is licensed under the [MIT License](./LICENSE).

---
*Project developed using Prompt Engineering practices intended to reduce hallucination risks in LLM outputs.*
