<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:58a6ff,100:a371f7&height=200&section=header&text=Satvik%20Singh&fontSize=56&fontColor=ffffff&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20Full-Stack%20Developer&descAlignY=58&descSize=18&animation=fadeIn" />
</p>

<p align="center">
  <a href="https://github.com/SATTURAMBOWORK">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=800&color=A371F7&center=true&vCenter=true&width=600&lines=Building+LLM+agents+with+LangGraph;Shipping+scalable+MERN+backends;RAG+%2B+ML+for+real-world+DevOps;Open+to+SDE+%2F+AI+Engineer+roles" />
  </a>
</p>

<p align="center">
  <a href="https://leetcode.com/u/SATTURAMBO/"><img src="https://img.shields.io/badge/LeetCode-SATTURAMBO-FFA116?style=flat&logo=leetcode&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/NIE%20Mysore-CSE%20(AI%2FML)%20'27-58a6ff?style=flat" />
  <img src="https://img.shields.io/badge/Open%20to-SDE%20%2F%20AI%20Engineer%20roles-2ea44f?style=flat" />
  <img src="https://komarev.com/ghpvc/?username=SATTURAMBOWORK&color=a371f7&style=flat&label=Profile+views" />
</p>

---

### 🚀 About me

- 🎓 Pre-final year B.E. Computer Science (AI/ML) at **The National Institute of Engineering, Mysore** (2023–2027)
- 🤖 Former **AI/LLM Engineering Intern at Neura AI**, building production LLM agents
- 🛠️ I build production-style systems: multi-tenant backends, real-time features, RAG pipelines, containerized deployments
- 🏆 2nd place in a college-wide DSA competition (Aug 2025) · Rank 11 / 800 on Codolio
- 💼 Looking for **fresher SDE / AI engineering roles and internships**

---

### 💼 Experience

#### 🤖 AI/LLM Engineering Intern · **Neura AI**

<p align="center">
  <img src="./assets/neura-agent.svg" width="100%" alt="LangGraph agent pipeline built at Neura AI" />
</p>

- Built a **LangGraph state machine** for a customer-support agent covering **intent classification → parameter extraction → tool selection → response generation**
- Integrated **5 internal tools** through **LLM function calling**
- Made agent execution reliable with **Pydantic-validated tool arguments**, **retries with exponential backoff** and **controlled fallbacks**

<p>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" />
  <img src="https://img.shields.io/badge/Function%20Calling-412991?style=flat-square" />
</p>

---

### 🧩 Featured projects

| Project | What it does | Stack |
|---|---|---|
| **[AI Interview Prep Platform](https://github.com/SATTURAMBOWORK/interview-platform)** | AI mock interviews, randomized MCQ tests and resume analysis, plus a custom C++ code judge running in isolated Docker containers | React · Node.js · MongoDB · Docker · Groq (Llama 3.3 70B) |
| **[AptHive](https://github.com/SATTURAMBOWORK/hive)** | Multi-tenant society management platform with 10+ modules and four-tier RBAC: visitor OTPs, amenity booking, SOS alerts, polls | MERN · Redis · Socket.IO · PM2 · Cloudinary |
| **[AI DevOps Incident Assistant](https://github.com/SATTURAMBOWORK/ai-devops-incident-assistant)** | Turns logs into structured root-cause analysis using RAG plus an ML classifier (84.9% test accuracy) | MERN · FastAPI · scikit-learn · Voyage AI · Groq · Docker · GitHub Actions |

<details>
<summary><b>🔍 Engineering highlights</b></summary>

**AptHive**
- Tenant isolation with `tenantId` carried in the JWT and enforced in middleware
- Race-free booking and voting: Redis distributed locks plus MongoDB compound unique indexes
- PM2 cluster mode with Redis for shared atomic counters and rate limiting (fixed window and sliding window log)
- Real-time SOS and force-logout over Socket.IO with tenant-level and per-user rooms
- Cache-aside with invalidate-on-write for read-heavy data

**AI Interview Prep Platform**
- Sandboxed code judge: user code is merged with driver code, compiled with `g++` inside Docker, and run against hidden test cases

**AI DevOps Incident Assistant**
- TF-IDF + Logistic Regression classifier: **84.9%** held-out accuracy, **81.8%** 5-fold CV, served via FastAPI
- LLM output constrained by a JSON schema and validated with Zod
- 4 services behind nginx with Docker Compose; CI runs tests, trains the model and pushes images to GHCR

</details>

---

### 🧠 LeetCode

<p align="center">
  <a href="https://leetcode.com/u/SATTURAMBO/">
    <img src="https://leetcard.jacoblin.cool/SATTURAMBO?theme=dark&font=Fira%20Code&ext=heatmap&border=0&radius=12&colors=0d1117,161b22,e6edf3,8b949e,a371f7,58a6ff,3fb950,d29922,f85149" width="49%" />
  </a>
  <a href="https://leetcode.com/u/SATTURAMBO/">
    <img src="https://leetcard.jacoblin.cool/SATTURAMBO?theme=dark&font=Fira%20Code&ext=contest&border=0&radius=12&colors=0d1117,161b22,e6edf3,8b949e,a371f7,58a6ff,3fb950,d29922,f85149" width="49%" />
  </a>
</p>

---

### 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,js,python,react,nodejs,express,mongodb,redis,fastapi,docker,nginx,githubactions,git,linux&perline=7" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-6E40C9?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge" />
</p>

---

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:a371f7,100:58a6ff&height=110&section=footer" />
</p>
