<div align="center">

# Hi there, I'm G. Jagadeesh 👋
### **I build backends that AI can talk to.**

**Backend & AI Software Engineer** specializing in **Python, Django, PostgreSQL, and AWS**  
📍 Hyderabad, India · 🎓 B.Tech CSE '26 (8.16 CGPA)

[![Portfolio](https://img.shields.io/badge/Portfolio-jaggu.dev-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-phi-neon-24.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jagadeesh_Gobburi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jagadeesh-gobburi-31b10b311)
[![Email](https://img.shields.io/badge/Email-jagadeeshsagar40%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jagadeeshsagar40@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-View_PDF-10B981?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1JnEX8M8P6LoNtNCB7Is5UOjgTbqc6bSi/view?usp=sharing)

</div>

---

### ⚡ About Me

- 🛠️ **Backend & AI Focus:** I design and build production-ready REST APIs, real-time WebSocket systems, autonomous CLI coding agents, and AI-callable **Model Context Protocol (MCP)** servers.
- 🤖 **Agentic Systems:** Built a terminal-based autonomous AI coding agent from scratch in Python featuring multi-provider LLM routing, RAG, Docker sandboxing, and persistent session memory.
- ☁️ **Cloud & Infra:** Experienced deploying containerized backends on **AWS EC2** with **Docker** and **Nginx**, utilizing **AWS S3** (presigned media uploads), **SQS**, **SNS**, **Lambda**, and **RDS**, plus workflow automation with **n8n**.
- 💼 **Status:** Open to Full-Time Backend & AI Engineering roles.

---

### 🚀 Flagship Production Systems

#### 1. [Autonomous AI Coding CLI Agent](https://github.com/jagadeesh-sagar/cli_agent)
> *A modular, terminal-based autonomous AI coding assistant built from scratch in Python.*
- **Agent Loop & Tooling:** Interactive Rich-formatted REPL that reads, diffs, writes, and edits files, searches codebases with `ripgrep`, fetches web content, and executes bash commands with configurable loop hard caps.
- **Provider-Agnostic LLM Layer:** Lazy-loading registry supporting **Anthropic** (with prompt caching), **Groq (Llama 3.3)**, **DeepSeek**, **Sarvam AI**, and **OpenAI** via a single-line config switch in `.agent.yaml`.
- **RAG & MCP Support:** Vector database-backed Retrieval-Augmented Generation for codebase context and runtime Model Context Protocol (MCP) tool discovery.
- **Sandboxing & Memory:** Isolates bash execution inside a **Docker** container and persists session logs & architectural notes (`memory/AGENT.md`) to **SQLite** across sessions (`--history`, `--search`, `--notes`).

#### 2. [Chatram — E-Commerce Backend API & MCP Server](https://github.com/jagadeesh-sagar/django-ecommerce-app) · [🌐 Live](https://ecommerce.chatram.in/) · [📐 Architecture](https://portfolio-phi-neon-24.vercel.app/blog/chatram-ecommerce-architecture)
> *Production-deployed Django REST e-commerce backend with real-time chat and 31 AI-callable MCP tools.*
- **Core Backend:** Built with **Django**, **Django REST Framework (DRF)**, and **PostgreSQL**, implementing JWT authentication and role-based access control (RBAC) for customer and seller workflows.
- **Real-Time & Async:** Real-time customer-seller chat powered by **Django Channels & WebSockets**, background task processing with **Celery & Redis**, and direct-to-**AWS S3** media uploads using presigned URLs.
- **AI-Callable MCP Server:** Exposed **31 FastMCP tool endpoints** (`ecommerce_mcp`), enabling autonomous AI agents to browse inventory, manage carts/wishlists, place orders, and handle reviews in real-world agentic workflows.
- **Deployment:** Containerized with **Docker** and deployed on **AWS EC2** behind **Nginx**.

---

### 📂 Selected Engineering Projects

| Project | Description | Tech Stack | Links |
| :--- | :--- | :--- | :--- |
| **MCP E-Commerce Server** | 31 AI-callable FastMCP endpoints wrapping a production Django REST API for autonomous agent workflows. | `Python` `FastMCP` `Django` `Docker` `AI Agents` | [Repo](https://github.com/jagadeesh-sagar/django-ecommerce-app) · [Blog](https://portfolio-phi-neon-24.vercel.app/blog/mcp-server-django) |
| **StudyBud REST API** | Discord-style study platform backend featuring rooms, topics, real-time messaging, and participant management. | `Django` `DRF` `JWT` `PostgreSQL` | [Repo](https://github.com/jagadeesh-sagar/StudyBud-REST-API) |
| **Food Delivery Landing Page** | Zero-framework, mobile-first responsive landing page built with modern CSS Grid and Flexbox. | `HTML5` `CSS3` `Flexbox` `CSS Grid` | [Repo](https://github.com/jagadeesh-sagar/Food-delivery-landing-page-vanilla-CSS) · [Live](https://food-delivery-jagadeesh.netlify.app/) |

---

### 🧰 Technical Stack

```yaml
Languages:        [Python, SQL, JavaScript, C, HTML5, CSS3]
Backend & APIs:   [Django, Django REST Framework, Django Channels, WebSockets, Celery, FastMCP, JWT / RBAC, REST APIs]
AI & Agents:      [Autonomous AI Agents, Model Context Protocol (MCP), LLM Tool Calling, RAG, Vector DBs, Prompt Caching, Sandboxing]
Databases:        [PostgreSQL, SQLite, AWS RDS, AWS DynamoDB, Query Optimization]
Cloud & DevOps:   [AWS (EC2, S3, SQS, SNS, Lambda, IAM), Docker, Nginx, Linux, n8n, Git & GitHub]
Frontend:         [React, JavaScript, HTML5, CSS3]
```

---

### ✍️ Architecture & Technical Writing

* 📐 **[Deep Dive into Chatram: A Production-Grade E-Commerce Backend](https://portfolio-phi-neon-24.vercel.app/blog/chatram-ecommerce-architecture)** — Exploring the system architecture behind Chatram using Django, DRF, Celery, Redis, and Django Channels.
* 🤖 **[I gave an AI 31 tools to control my e-commerce backend](https://portfolio-phi-neon-24.vercel.app/blog/mcp-server-django)** — How I wired up FastMCP to a Django REST API so AI agents can browse products, create orders, and manage reviews via structured tool calls.
* ⚡ **[Django ORM Optimization: Lessons from Building a 31-Endpoint E-Commerce Backend](https://portfolio-phi-neon-24.vercel.app/blog/rbac-jwt-django)** — Fixing N+1 queries and optimizing PostgreSQL performance with real before/after benchmarks.
* ☁️ **[How I Reduced AWS Costs by Running Multiple Services on a Single EC2 Instance](https://www.linkedin.com/posts/jagadeesh-gobburi-31b10b311_document-to-follow-what-i-have-done-ugcPost-7413635118982168577-_7GU)** — Using Docker Compose and Nginx as a reverse proxy gateway for DRF and n8n on a single EC2 instance.
* 🪣 **[AWS S3 Presigned URLs in Django REST Framework](https://www.linkedin.com/posts/jagadeesh-gobburi-31b10b311_aws-s3-in-django-rest-framework-ugcPost-7366171893780860929-02ev)** — Offloading media uploads directly from the client to S3 without bottlenecking the backend server.

---

<div align="center">
  <sub>Built with ❤️ by <a href="https://portfolio-phi-neon-24.vercel.app/">G. Jagadeesh</a> · Let's connect on <a href="https://www.linkedin.com/in/jagadeesh-gobburi-31b10b311">LinkedIn</a>!</sub>
</div>
