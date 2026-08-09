<div align="center">

# 🚀 SkillPraxis Experimental Internship Program (SEIP '26)
### Cohort 1: Building Project Sandbox 1.0

[![Cohort](https://img.shields.io/github/followers/skillpraxis?style=social)](https://github.com/skillpraxis-hq)
[![Status](https://img.shields.io/badge/Status-Active%20Sprint-brightgreen?style=for-the-badge)](https://github.com/skillpraxis)
[![License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)](LICENSE)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-5865F2?logo=discord&logoColor=white)](https://discord.gg/skillpraxis)

*A 4-week, execution-first engineering sprint simulating real-world startup development across 5 core technical domains.*

---

</div>

## 📌 About SEIP '26

The **SkillPraxis Execution & Internship Program (SEIP '26)** moves beyond theoretical tutorials and isolated projects. In Cohort 1, participants collaborate in multidisciplinary teams to architect, build, security-audit, and ship **Project Sandbox 1.0** — a unified open-source developer productivity and portfolio platform.

---

## 🛠️ Domain Tracks & Cohort Deliverables

| Domain | Tech Stack | Cohort Focus & Microservice Deliverable |
| :--- | :--- | :--- |
| **🤖 Generative AI** | Python, LangChain, LlamaIndex, OpenAI/Groq APIs, Vector DBs | Automated AI Code Reviewer & RAG-driven feedback bot |
| **📊 Data Science** | Python, Pandas, Streamlit, Scikit-learn, Telemetry APIs | Real-time participant activity & execution telemetry dashboard |
| **💻 Web Development** | Next.js, Node.js/Express, TypeScript, Tailwind CSS, PostgreSQL | Core web platform, REST/GraphQL endpoints, & authentication |
| **🎨 UI/UX Design** | Figma, Auto-Layout, Design Tokens, Usability Testing | Complete Design System, UI component library, & interactive prototype |
| **🛡️ Cybersecurity** | OWASP Top 10, OAuth2/JWT, Burp Suite, Python Security Scripts | System hardening, API security rate-limiting, & vulnerability audit report |

---

## 🏛️ Cohort Architecture: Project Sandbox 1.0

All five domain tracks contribute directly to a single interconnected codebase

  
## 📅 4-Week Sprint Schedule

* **Week 1: Architect & Blueprint** — Team onboarding, Git/Notion environment setup, system design approval, and Figma specs.
* **Week 2: Core Execution** — Feature building, model training, API route creation, and baseline UI deployment.
* **Week 3: Cross-Integration & Security** — Merging domain microservices, running data pipelines, and cybersecurity penetration testing.
* **Week 4: Ship & Showcase** — Final production deployment, documentation polish, and live Public Demo Day presentation.

---

## ⚙️ Local Development Quickstart

### Prerequisites
* **Node.js:** `>= 18.x`
* **Python:** `>= 3.10`
* **Git** installed on your local machine

### Setup Instructions
```bash
# 1. Clone the SEIP '26 repository
git clone [https://github.com/skillpraxis/seip26-execution.git](https://github.com/skillpraxis/seip26-execution.git)
cd seip26-execution

# 2. Configure environment variables
cp .env.example .env.local

# 3. Install core dependencies
npm install

# 4. Launch the local dev server
npm run dev

```

Navigate to `http://localhost:3000` to view the application locally.

---

## 📜 Pull Request & Branch Standards

To maintain production standards, all contributors must follow these branch guidelines:

### Branch Naming Convention

Pushes directly to `main` are restricted. Create feature branches using domain prefixes:

```bash
<domain>/<feature-description>

# Examples:
webdev/add-auth-routes
genai/rag-pipeline-setup
sec/jwt-rate-limiter

```

### PR Requirements

1. Link your PR to an open **GitHub Issue**.
2. Include screenshots, video demos, or terminal logs as proof of work.
3. Obtain approval from at least **1 Domain Lead or Maintainer** prior to merging into `main`.

---

## 👥 Contributors & Community

Thank you to all interns, mentors, and leads driving SEIP '26!

---

**SkillPraxis SEIP '26** • *Learn Together. Grow Together.*
