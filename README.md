<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./docs/images/header-dark.svg">
    <img src="./docs/images/header-light.svg" alt="Manuel Stolze: full-stack developer turned agentic engineer" width="100%">
  </picture>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/focus-agentic%20coding-7c3aed?style=for-the-badge" alt="Focus: agentic coding">
  <img src="https://img.shields.io/badge/agents-Claude%20Code%20%C2%B7%20Pi-22d3ee?style=for-the-badge" alt="Agents: Claude Code and Pi">
  <img src="https://img.shields.io/badge/based%20in-Germany-3fb950?style=for-the-badge" alt="Based in Germany">
</p>

---

### 🤖 What I do now

I used to write most of my code myself. Now I design the **systems that let coding agents write it well**.

I care about the parts that make agents reliable:

- **Specs come before code.** Every change gets a specification, a plan, and a task list. A human approves each one.
- **Skills, not prompts.** I write reusable agent skills and workflows that encode how I want work done.
- **Delegation with guardrails.** I hand approved tasks to implementation agents in isolated worktrees. Lint, types, and tests act as gates.
- **Memory that lasts.** I keep knowledge bases and logbooks so agents (and I) remember why decisions were made.

### 🔁 My agent loop

```mermaid
flowchart LR
    A([💡 Idea]) --> S[📝 Specify]
    S --> P[🧭 Plan]
    P --> T[✅ Tasks]
    T --> D[🤖 Delegate]
    D --> V[🧪 Verify]
    V --> R{👀 Review}
    R -- changes --> D
    R -- merged --> L[(📚 Learn)]
    L -. context .-> S
```

### 🛠️ Things I'm building

| Project | What it is |
| --- | --- |
| 🐚 **Nautilus** *(private, in progress)* | A modular, agent-driven development workflow. A *Bridge* drafts specs, plans, and tasks with me and delegates the work. A *Logbook* tracks every change, *Charts* map my repositories, and a *Library* keeps what I've learned. |
| 🏮 [**ai-lantern**](https://github.com/manuelstolze/ai-lantern) | A workspace for technical spikes. Agent skills research, map systems, and write evidence-backed drafts. |
| 🧠 [**cortex-baseline**](https://github.com/manuelstolze/cortex-baseline) | Cortex, a Markdown second brain and developer memory system driven by agent skills. |
| 🧩 **pi-integrations** *(private)* | Extensions and skills for the Pi coding agent, published as independent npm packages, including a Jira integration. |

### 🧰 Toolbox

**Agentic:**
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=claude&logoColor=white)
![Pi](https://img.shields.io/badge/Pi%20agent-7c3aed?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-111111?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![Agent Skills](https://img.shields.io/badge/Agent%20Skills-22d3ee?style=flat-square)
![Git worktrees](https://img.shields.io/badge/git%20worktrees-F05032?style=flat-square&logo=git&logoColor=white)

**Foundations:**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white)

### 💬 Ask me about

Spec-driven development with agents, writing agent skills, multi-agent delegation, and keeping humans in the loop. Full-stack React and Java also still count.

### 📫 Reach me

<a href="mailto:manuel.stolze93@hotmail.com"><img src="https://img.shields.io/badge/Email-manuel.stolze93%40hotmail.com-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white" alt="Email"></a>
<a href="https://www.linkedin.com/in/manuel-stolze"><img src="https://img.shields.io/badge/LinkedIn-Manuel%20Stolze-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>

<p align="center"><sub><code>$ agent status</code> → <i>always learning, always delegating 🤖</i></sub></p>
