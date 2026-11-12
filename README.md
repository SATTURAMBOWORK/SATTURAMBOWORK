<h1 align="center">Hi, I'm Satvik Singh 👋</h1>

<p align="center">
  <b>CS (AI/ML) undergrad @ NIE Mysore · Full-stack MERN developer · Competitive programmer (C++)</b>
</p>

<p align="center">
  <a href="https://leetcode.com/u/SATTURAMBO/"><img src="https://img.shields.io/badge/LeetCode-SATTURAMBO-FFA116?style=flat&logo=leetcode&logoColor=white" /></a>
  <a href="https://github.com/SATTURAMBOWORK"><img src="https://img.shields.io/badge/GitHub-SATTURAMBOWORK-181717?style=flat&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Open%20to-SDE%20%2F%20AI%20Engineer%20roles-2ea44f?style=flat" />
</p>

---

### 🚀 About me

- 🎓 Pre-final year B.E. Computer Science (AI/ML) at **The National Institute of Engineering, Mysore** (2023–2027)
- 🤖 Previously **AI/LLM Engineering Intern at Neura AI**, where I built a LangGraph customer-support workflow with LLM function calling
- 🛠️ I build production-style full-stack systems: multi-tenant backends, real-time features, RAG pipelines, containerized deployments
- 🏆 **2nd place** in a college-wide DSA competition (Aug 2025) · **Rank 11 / 800** on Codolio
- 💼 Looking for **fresher SDE / AI engineering roles and internships**

---

### 🧩 Featured projects

| Project | What it does | Stack |
|---|---|---|
| **[AI Interview Prep Platform](https://github.com/SATTURAMBOWORK/interview-platform)** | AI mock interviews plus an online code judge: compiles and runs user C++ in Docker against visible and hidden test cases | React · Node.js · MongoDB · Docker · Groq (Llama 3.3 70B) |
| **[AptHive](https://github.com/SATTURAMBOWORK/hive)** | Multi-tenant society management platform: visitor OTPs, amenity booking, SOS alerts, polls, guard management | MERN · Redis · Socket.IO · PM2 · Cloudinary |
| **[AI DevOps Incident Assistant](https://github.com/SATTURAMBOWORK/ai-devops-incident-assistant)** | Turns application and Docker logs into structured root-cause analysis using RAG over incident runbooks plus an ML classifier | MERN · FastAPI · scikit-learn · Voyage AI · Groq · Docker Compose · GitHub Actions |

<details>
<summary><b>🔍 Engineering highlights</b></summary>

**AptHive**
- Tenant isolation with `tenantId` carried in the JWT and enforced in middleware
- Race-free amenity booking: Redis distributed lock plus a compound unique index on `(tenantId, amenityId, date, startTime)`
- PM2 cluster mode with Redis for shared atomic counters and rate limiting (fixed window and sliding window log)
- Real-time SOS and force-logout over Socket.IO with tenant-level and per-user rooms
- Cache-aside with invalidate-on-write for read-heavy data

**AI Interview Prep Platform**
- Sandboxed code judge: user code is merged with driver code, compiled with `g++` inside Docker, and run against hidden test cases, with compile errors sent back to the editor

**AI DevOps Incident Assistant**
- LLM output constrained by a JSON schema and validated with Zod
- TF-IDF + Logistic Regression incident classifier (trained partly on Loghub) served as a FastAPI microservice
- 4 services behind nginx with Docker Compose; CI runs tests, trains the model and pushes images to GHCR

</details>

---

### 🛠️ Tech stack

**Languages**
<p>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</p>

**Frontend and backend**
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white" />
</p>

**Data and infrastructure**
<p>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

**AI / ML**
<p>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-6E40C9?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LLM%20Function%20Calling-412991?style=for-the-badge" />
</p>

---

### 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=SATTURAMBOWORK&show_icons=true&hide_border=true&theme=tokyonight" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SATTURAMBOWORK&layout=compact&hide_border=true&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://leetcard.jacoblin.cool/SATTURAMBO?theme=dark&font=Inter&ext=heatmap" />
</p>

---

<p align="center"><i>Building things that scale, one commit at a time.</i></p>
