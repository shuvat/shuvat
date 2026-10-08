# Hi there, I'm Shuvat Bukinski 👋

### Software Developer | 3rd-Year B.Sc. Computer Science Student @ Bar-Ilan University

I'm passionate about **backend development**, **systems programming** and **agentic AI systems**. I love building intelligent automation and efficient technical solutions that solve real-world problems — from multithreaded C++ on Linux, through Python and Node.js backends, to LLM-based multi-agent systems and MCP integrations. Experienced in real-time operational analysis and problem-solving under pressure.

🎯 **Currently looking for:** a student position in backend, systems or agentic AI development — building intelligent automation and reliable software.

📫 **Connect with me:**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shuvat-bukinski-a07510264)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shuvatbuk@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shuvat)

---

## 🛠️ Tech Stack & Tools

**Languages:**

[![My Languages](https://skillicons.dev/icons?i=cpp,c,py,java,js,ts,bash)](https://skillicons.dev)

![x86-64 Assembly](https://img.shields.io/badge/x86--64_Assembly-6E4C13?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**Backend & Frontend:**

[![My Skills](https://skillicons.dev/icons?i=fastapi,nodejs,express,postgres,mongodb,react,html,css)](https://skillicons.dev)

![asyncio](https://img.shields.io/badge/asyncio-3776AB?style=flat-square&logo=python&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-009688?style=flat-square)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Systems & Networking:**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Multithreading](https://img.shields.io/badge/Multithreading_%26_Concurrency-455A64?style=flat-square)
![TCP/UDP Sockets](https://img.shields.io/badge/TCP%2FUDP_Sockets-00599C?style=flat-square)
![IPC](https://img.shields.io/badge/IPC-607D8B?style=flat-square)
![cgroups](https://img.shields.io/badge/cgroups_v2-37474F?style=flat-square)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

**AI & Agentic Development:**

[![ML](https://skillicons.dev/icons?i=pytorch,tensorflow)](https://skillicons.dev)

![MCP](https://img.shields.io/badge/Model_Context_Protocol-D97757?style=flat-square&logo=claude&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LLM Agents](https://img.shields.io/badge/LLM_Agents-7E57C2?style=flat-square)
![Multi--Agent Architecture](https://img.shields.io/badge/Multi--Agent_Architecture-3949AB?style=flat-square)
![Deep Learning](https://img.shields.io/badge/Deep_Learning_(CNNs%2C_Transformers)-FF6F00?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Testing, Debugging & DevOps:**

[![Tools](https://skillicons.dev/icons?i=git,githubactions,docker,linux,powershell)](https://skillicons.dev)

![GoogleTest](https://img.shields.io/badge/GoogleTest-4285F4?style=flat-square&logo=google&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![TDD](https://img.shields.io/badge/TDD-2E7D32?style=flat-square)
![GDB](https://img.shields.io/badge/GDB-A42E2B?style=flat-square)
![Valgrind](https://img.shields.io/badge/Valgrind-5C2D91?style=flat-square)
![ThreadSanitizer](https://img.shields.io/badge/ThreadSanitizer-00897B?style=flat-square)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

---

## 📊 GitHub Statistics

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=shuvat&show_icons=true&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=shuvat&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=shuvat&theme=tokyonight&hide_border=true)

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=shuvat&theme=tokyo-night&hide_border=true)](https://github.com/shuvat)

---

## 📌 Featured Projects

### 📈 [SysPulse](https://github.com/shuvat/syspulse) — Distributed Linux Monitoring with AI Investigation

Multithreaded C++ agents stream Linux metrics over TCP to a Python/PostgreSQL backend that detects anomalies, with a live dashboard and an MCP server that lets Claude answer *"Which host is overloaded and why?"*

* **Tech Stack:** C++17, Python, asyncio, FastAPI, PostgreSQL, MCP, Streamlit, Docker Compose, GitHub Actions
* **Highlights:**
  * C++ agents read CPU and memory from `/proc` and their container's cgroup, with a collector/sender thread pair over a bounded queue and reconnection with exponential backoff.
  * Anomaly detection with thresholds, hysteresis and a z-score rule, plus an MCP server with four tools so an LLM can investigate the system itself.
  * Diagnosed a deadlock with GDB; 0 leaks under Valgrind and race-checked with ThreadSanitizer; 170+ tests and an end-to-end integration test in a six-job CI pipeline.

### 🤖 AIFB — Auto-Installer for Beginners, Agentic AI System

A multi-agent AI system that plans and executes Windows software installs from natural-language requests, with a clear separation between planning and execution. Built as a team at a university hackathon.

* **Tech Stack:** Python, LLMs, LangGraph, Streamlit
* **Highlights:**
  * One agent plans the installation steps; a sandboxed desktop agent runs only human-approved commands over IPC.
  * Keeps a safe boundary between AI reasoning and system access.

### 🎨 [DoodleDrive](https://github.com/shuvat/doodledrive) — Full-Stack Storage Application

A file storage app for web and mobile: create, upload, edit, search and share files, with owner, writer and reader permissions.

* **Tech Stack:** C++, Node.js, Express, MongoDB, React, React Native, JWT, Docker Compose
* **Highlights:**
  * Multithreaded C++ file server with a thread pool and RLE compression, built with TDD.
  * Node.js REST API with JWT authentication, connected to the C++ server over TCP sockets.
  * Multi-service system (C++ server, Node.js, MongoDB, React client) running with Docker Compose.

---

## 🎓 Education & Experience

* **B.Sc. Computer Science (Expanded Program)** — Bar-Ilan University (Oct 2024 – Present, expected graduation March 2028) · **GPA 86.4**
  * **Highlights:** Automata & Formal Languages (97), Calculus II (94), Advanced System Programming (93), Computer Architecture — x86-64 Assembly (92), Machine Learning (91), Safe Programming (90), Operating Systems (85)
  * **Currently studying:** Parallel System Programming, Communication Networks, Database Systems, Introduction to Robotics, Computability & Complexity
* **Operational Data Analyst** — Israel Border Police (2023 – 2026): real-time analysis of large operational datasets in a high-pressure tactical environment, awarded a **certificate of excellence** for outstanding performance.

---

## 💡 Interests

* 🤖 Agentic AI & Intelligent Automation
* ⚙️ Backend Development & System Design
* 🐧 Systems Programming & Concurrency
* 📚 Reading fiction
* ✈️ Traveling
* 🏋️ Working out

---

### ⚡ What I'm Up To

✨ Building agentic AI systems and connecting LLMs to real systems through MCP
🧵 Diving into parallel programming, networking and databases this semester
📚 Continuously learning new technologies and best practices
🤝 Open to collaboration and exciting opportunities
