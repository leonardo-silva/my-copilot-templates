# 🧩 Copilot Modes (Ask, Edit, Plan, Agent, and Study)

![dio/me](https://img.shields.io/badge/dio-me-ff2d55)
![AI](https://img.shields.io/badge/IA-Intelligent%20Assistant-blue)
![Prompt](https://img.shields.io/badge/Prompt-engineering-yellow)

The Copilot offers different **interaction modes** for you to choose how you want to work: from **asking questions without touching the code**, to **editing specific snippets**, **planning larger changes**, or **delegating more complex tasks** with a more autonomous mode. The idea is simple: you select the mode that best matches your current goal and gain speed with more control.

---

# ❓ Ask
The **Ask** mode is for asking questions and understanding things, **without altering your code**. You can ask about a specific file, an error, a function, a stack trace, or even general concepts.

The Copilot reads the project context (open files, selection, etc.) and responds like a **"technical mentor"**, explaining what is happening and why. **It does not modify anything** — it only analyzes and explains.

📄 **Prompt:** [prompts/prompt-ask.md](prompts/prompt-ask.md)

---

# ✏️ Edit
The **Edit** mode is used to **change existing code**. You select a snippet (or an entire file), describe what you want to change, and the Copilot applies the modification directly.

Ideal for:
- refactors
- logic adjustments
- performance improvements
- style changes
- language conversion
- adding logs
- error handling

The focus here is: **"take what already exists and transform it"**.

📄 **Prompt:** [prompts/prompt-edit.md](prompts/prompt-edit.md)

---

# 🧭 Plan
When you ask for something more complex, the Copilot can enter a **planning** mode, where it **thinks and describes the steps before it starts coding**.

It:
- breaks the problem down into steps
- explains what it is going to do
- only executes afterward

This is very useful for **large changes**, **new features**, or when you want to **validate the approach** before changing the code.

📄 **Prompt:** [prompts/prompt-plan.md](prompts/prompt-plan.md)

---

# 🤖 Agent
The **Agent** is the most "autonomous" mode. It can **navigate the project**, **create files**, **modify multiple points**, and **keep context between steps**, just like a junior dev working with you.

You give it a goal (e.g., "implement login with JWT") and it decides what needs to be done across multiple files to get there.

📄 **Prompt:** [prompts/prompt-agent.md](prompts/prompt-agent.md)

---

# 📚 Study
The **Study** mode is focused on **active learning**, not just getting to the answer or the final code.

Instead of simply explaining or executing, it:
- teaches and guides reasoning
- highlights concepts and trade-offs
- asks reflective questions
- advances in a gradual progression of difficulty

It works almost like a **private tutor**.

📄 **Prompt:** [prompts/prompt-study.md](prompts/prompt-study.md)

---

# 🧠 Quick mental summary
- **Ask** → understand  
- **Plan** → plan before acting  
- **Edit** → change code  
- **Agent** → execute large tasks alone  
- **Study** → active understanding
