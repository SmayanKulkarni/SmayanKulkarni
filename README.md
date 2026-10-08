<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=240&color=0:000000,50:0B3D3A,100:40E0D0&text=Smayan%20Kulkarni&fontColor=40E0D0&fontSize=60&fontAlignY=38&desc=AI%20%2F%20ML%20Developer%20%7C%20Agentic%20AI%20%7C%20Backend%20Engineering&descColor=B2FFF5&descSize=20&descAlignY=60&animation=fadeIn" width="100%" alt="Smayan Kulkarni banner"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3200&pause=900&color=40E0D0&background=00000000&center=true&vCenter=true&width=820&height=50&lines=AI+Engineering+Intern+at+Cadila+Pharmaceuticals;Building+production+agentic+systems;Fine-tuning+LLMs+with+LoRA%2C+DPO+and+GRPO;RAG+%7C+MCP+%7C+LangGraph+%7C+Observability;Open+to+AI%2FML+and+Backend+roles" alt="Typing animation"/>
</a>

</div>

---

## About

```json
{
  "name": "Smayan Kulkarni",
  "location": "Mumbai, India",
  "current_role": "AI Engineering Intern, Cadila Pharmaceuticals",
  "education": "B.Tech CSE (Data Science), DJ Sanghvi College of Engineering, CGPA 9.2/10",
  "mentoring": "Machine Learning Mentor, DJS Compute",
  "interests": [
    "Deep Learning",
    "Agentic AI",
    "Large Language Models",
    "Backend Engineering",
    "System Design"
  ],
  "open_to": ["AI / ML Engineer", "Backend Engineer"]
}
```

I build ML systems that survive contact with production. I train and evaluate the model, connect it to tools and memory, then run it with tenant isolation, access control, tracing, and cost tracking.

At Cadila Pharmaceuticals I work on two systems:

- An enterprise RAG platform that answers questions from large internal document sets. It uses context-aware chunking, semantic retrieval, index tuning, and custom evaluations.
- An internal small language model that learns company terminology and document formats. It runs behind access controls, with observability, horizontal scaling, and inference-cost optimization.

---

## Interests

<table>
<tr>
<td width="50%" valign="top">

**Deep Learning**
CNNs, LSTMs, Transformers, and Vision Transformers. I read the architecture closely enough to fine-tune it, quantize it, and evaluate it.

**Agentic AI**
Tool-using agents, harness and context engineering, durable workflows, MCP servers, and agent memory. I want agents I can trace, bound, and audit.

**Large Language Models**
Prompt and context engineering, RAG, LoRA and QLoRA, DPO, GRPO, RLHF, and inference optimization for small models.

</td>
<td width="50%" valign="top">

**Backend Engineering**
Node.js, Express, FastAPI, and TypeScript services with validated boundaries, typed errors, idempotent writes, structured logs, and tests for failure paths.

**System Design**
Multi-tenant isolation, replay-safe execution, queues, caching, horizontal scaling, secrets handling, and access control.

**Observability and MLOps**
OpenTelemetry, Grafana, MLflow, Docker, and CI/CD. I count latency, errors, token cost, and approvals before I call a system done.

</td>
</tr>
</table>

---

## Projects

### Threadline: Enterprise Agent Automation Platform
`TypeScript` `React` `Azure Durable Functions` `MCP` `OpenTelemetry`

- Each workflow runs as a durable, replay-safe execution on Azure Durable Functions and Azure SQL. A React canvas compiles into an immutable definition of up to 100 nodes.
- Agents call up to 16 schema-validated tools. A judgment node routes each decision into act, review, or escalate. Upstash Vector memory ranks items by relevance, recency, and type.
- MCP and signed webhooks connect agents to external systems. Risk tiers and approvals gate every action. In a live GitHub PR gate, the reviewer agent found seven issues in one PR, including a hardcoded key.
- More than 20 metrics and 19 log events flow to Grafana and Application Insights across four dashboards. The system has tenant isolation, AES-256-GCM secrets, and 1,099 tests.

### Fine-Tuning Small Language Models for Tool Use
`PyTorch` `LoRA / QLoRA` `DPO` `GRPO`

- QLoRA and DPO fine-tuning of Qwen2.5-Coder-3B on 10,680 curated trajectories raised tool-selection accuracy from 28% (zero-shot) to 96-100%. The failure rate dropped from 71% to 0% in the evaluation setup.
- A multi-turn GRPO training loop runs against an evaluation harness with seven metrics and statistical significance tests.

### Agentic Dev Guardian: Context Layer for AI Coding Agents
`GraphRAG` `MCP` `LangGraph` `PyPI`

- Combines semantic search with dependency-graph traversal. An MCP server and a CLI expose it for code review, security audit, and refactoring.
- Published on PyPI. CI regression tests run on every change, and blast-radius-aware context limits what an agent can touch.

### Decision Graph: Agent Traceability
- Records agent decisions, tool calls, and file edits with no extra model calls. Each changed line of code links to the decision that produced it. A session harness tests the flow end to end.

---

## Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,c,cpp,js,ts,java,html,css&theme=dark" alt="Languages"/>

**ML and Data**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn&theme=dark" alt="ML frameworks"/><img src="https://www.educative.io/api/edpresso/shot/6048535705026560/image/5096293455888384" width="48" alt="NumPy"/> <img src="https://assets.streamlinehq.com/image/private/w_300,h_300,ar_1/f_auto/v1/icons/2/pandas-187ap5b4rnewum3e0kwot.png/pandas-d7d1sqnks3dbdy0lu80am4.png?_a=DATAiZAAZAA0" width="48" alt="Pandas"/> <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSEVqffai1A2Wrwxo4OKuVdPtQnGOtb7LUk8quKFJtmDA&s=10" width="48" alt="Hugging Face"/> <img src="https://miro.medium.com/1*_zS2qyJ-rDFe1w3P37w2ag.png" width="48" alt="LangChain and LangGraph"/> <img src="https://ih1.redbubble.net/image.5611428487.0532/st,small,507x507-pad,600x600,f8f8f8.jpg" width="48" alt="Ollama"/> <img src="https://images.chainguard.dev/logos/mlflow.svg" width="48" alt="MLflow"/>

**Backend and Cloud**

<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,react,postgres,redis,docker,kubernetes&theme=dark" alt="Backend"/>

<img src="https://skillicons.dev/icons?i=azure,aws,gcp,vercel,grafana,githubactions&theme=dark" alt="Cloud"/><img src="https://assets.streamlinehq.com/image/private/w_300,h_300,ar_1/f_auto/v1/icons/2/opentelemetry-66777cop50ua88dptcss0b.png/opentelemetry-qjp9r1tqogqgmxtl6tduv.png?_a=DATAiZAAZAA0" width="48" alt="OpenTelemetry"/>

**Tools**

<img src="https://skillicons.dev/icons?i=git,github,linux,ubuntu,bash,vscode&theme=dark" alt="Tools"/>

</div>

---

## GitHub Activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=SmayanKulkarni&show_icons=true&bg_color=000000&title_color=40E0D0&icon_color=40E0D0&text_color=C9D1D9&border_color=40E0D0&hide_rank=true" alt="GitHub stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SmayanKulkarni&layout=compact&bg_color=000000&title_color=40E0D0&text_color=C9D1D9&border_color=40E0D0" alt="Top languages"/>

<img src="https://streak-stats.demolab.com?user=SmayanKulkarni&background=000000&ring=40E0D0&fire=40E0D0&currStreakLabel=40E0D0&currStreakNum=FFFFFF&sideNums=FFFFFF&sideLabels=40E0D0&dates=8B949E&stroke=40E0D0&border=40E0D0" alt="GitHub streak"/>

</div>

---

## Education and Certifications

- **B.Tech, Computer Science Engineering and Data Science**, SVKM's Dwarkadas J. Sanghvi College of Engineering, 2023 to present. CGPA 9.2/10.
- **Machine Learning Mentor, DJS Compute**, Jul 2025 to Jun 2026. I trained 10+ students in CNNs, transformers, and MLOps. A student team under my lead built an end-to-end ML system and co-authored a research paper.
- **Certifications:** Google AI Leader, Agentic AI with LangChain and LangGraph (IBM), Machine Learning Specialization (DeepLearning.AI and Stanford), Adversarial AI: Attacking, Defending and Governing ML Systems (Macquarie University).

---

## Connect

<div align="center">

<a href="https://www.linkedin.com/in/smayan-kulkarni-792520296/"><img src="https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=40E0D0" alt="LinkedIn"/></a>
<a href="https://leetcode.com/u/SmayanKulkarni/"><img src="https://img.shields.io/badge/LeetCode-000000?style=for-the-badge&logo=leetcode&logoColor=40E0D0" alt="LeetCode"/></a>
<a href="https://github.com/SmayanKulkarni"><img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=40E0D0" alt="GitHub"/></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:40E0D0,50:0B3D3A,100:000000&section=footer" width="100%" alt="footer"/>
