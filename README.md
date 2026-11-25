# 👋 Hi, I'm Sebastian Guerra

### Technical Lead · Full-stack Developer

Full-stack developer with **3+ years** of experience building B2B products end to end, currently completing a degree in **Computer Engineering**.
Since 2026 I've been Technical Lead, owning the architecture and engineering standards for a portfolio of multi-tenant SaaS products
in legal-tech, payroll, corporate compliance, public-sector budgeting, regulated gaming and billing,
and for the AI agent platform that powers them.
I design the systems, write code across the full stack and set how the team builds and ships.

---

## 🧭 What I Do

- 🏗️ **Architecture** for multi-tenant SaaS: tenant isolation, durable processing, payment and e-invoicing integrations.
- 🤖 **AI agents in production**, grounded in business data and built to be reliable.
- 👥 **Technical leadership**: architecture decisions, code review, standards and CI/CD.

---

## 🤖 AI Agents

With my team, we've shipped agents that:

- 🛒 Close sales end to end against an ERP.
- ⚖️ Solve legal and financial calculations without guessing a single number.
- 💬 Serve customers on WhatsApp and hand off to a human when needed.
- 🎙️ Turn meetings into summaries and actionable tasks.
- 🧱 Run on a multi-tenant platform where each company manages its own agents.

```mermaid
flowchart LR
  C["Channels<br/>WhatsApp · Web · API"] --> G["Gateway<br/>auth · validation"]
  G --> R["Agent runtime<br/>multi-tenant · durable"]
  R <--> M["Models<br/>Claude · GPT · Gemini"]
  R <--> T["Tools<br/>MCP · ERP · CRM"]
  R <--> K["Knowledge<br/>pgvector · reranking"]
  R --> V["Guardrails<br/>validation · human handoff"]
  V --> C
  R -.-> O["Observability<br/>traces · evals · cost"]
```

**How they're built:** grounded in real data · deterministic guardrails · tenant isolation · durable execution · provider-agnostic · sandboxed · continuously evaluated.

---

## 🧩 Open Source

- **[Praxis](https://github.com/SebastianDevps/praxis)**: spec → build → review → ship workflow for AI coding agents (Claude Code, Codex, Cursor, Gemini CLI, Copilot).
- **[git-commit-validator](https://www.npmjs.com/package/@sebastiandevp/git-commit-validator)**: commit-convention validator on npm.
- **[Engram](https://github.com/SebastianDevps/engram)**: fixes to a persistent memory store for coding agents.

---

## 💻 Tech Stack

<p>
  <img src="https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white" alt="Go"/>
  <img src="https://img.shields.io/badge/Node.js-%23339933.svg?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/NestJS-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS"/>
  <img src="https://img.shields.io/badge/Fastify-%23000000.svg?style=for-the-badge&logo=fastify&logoColor=white" alt="Fastify"/>
  <img src="https://img.shields.io/badge/FastAPI-%23009688.svg?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-%23000000.svg?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js"/>
</p>
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Redis-%23DC382D.svg?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/AWS-%23232F3E.svg?style=for-the-badge&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/OpenTelemetry-%23425CC7.svg?style=for-the-badge&logo=opentelemetry&logoColor=white" alt="OpenTelemetry"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Claude-%23D97757.svg?style=for-the-badge&logo=claude&logoColor=white" alt="Claude"/>
  <img src="https://img.shields.io/badge/OpenAI-%23412991.svg?style=for-the-badge&logoColor=white" alt="OpenAI"/>
  <img src="https://img.shields.io/badge/Gemini-%238E75B2.svg?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini"/>
  <img src="https://img.shields.io/badge/MCP-%23000000.svg?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" alt="Model Context Protocol"/>
  <img src="https://img.shields.io/badge/pgvector-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="pgvector"/>
</p>

---

## 📊 GitHub Stats

<img src="https://streak-stats.demolab.com?user=SebastianDevps&theme=radical" alt="GitHub Streak Stats" />

---

## 🤝 Connect With Me

<p>
  <a href="https://www.linkedin.com/in/sebastiandevp/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logoColor=white" alt="LinkedIn"></a>
  <a href="https://js-webs.com/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-%23121011.svg?style=for-the-badge&logo=about-dot-me&logoColor=white" alt="Portfolio"></a>
  <a href="https://discordapp.com/users/779550358254125076" target="_blank"><img src="https://img.shields.io/badge/Discord-%237289DA.svg?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
</p>
